# Toggle Function Keys

A simple AppleScript that toggles the `”Use all F1, F2, etc. keys as standard function keys"` setting found under `System Preferences > Keyboard`. Displays a message to Notification Center telling you which one is active. I use this script via [Alfred](http://www.alfredapp.com/) with an assigned keyword.

#### Alfred v2

Just doubble click the `ToggleFunctionKeys.alfredworkflow` file and you are all set. The workflow uses the keyword "fn" by default.

#### Aldred v1

Make a new AppleScript extension and Copy paste the contents of the `ToggleFunctionKeys.scpt` file into the extension.

#### System preferences

Please note that you have to have `”Enable access for assistive devices”` turned on for the application that runs this script.

* 10.9: `System Preferences > Security & Privacy > Privacy > Accessibility`
* 10.X: `System Preferences > Accessibility`

Original AppleScript by [kiodane](http://forums.macrumors.com/showpost.php?p=17106824&postcount=12).

### Language Support
Because the script invoke apple UI system based on preffered language, now it just supports English and Chinese, if you have chosen other language, please add corresponding literals to the langMapList in the applescript or the applescript in alfred workflow as the right format.
