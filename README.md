# androidappupdate
JSON file telling users to update to new android version

For some reason the library has it that 

`  "latestVersion": "2.14",
`

is latestVersion - 1. Ie: the latest version right now is 2.15. For the pop up to not show up on 2.15. You have to put latest version as 2.14


uses this library: https://github.com/javiersantos/AppUpdater

---------------------------

If `latestVersionCode` is included in the JSON, `latestVersion` will only be used to display the latest version in the dialog and the `versionCode` will be used to compare the installed and latest update.
