steps in updating quasar version of your app:

- yarn create quasar
- commit to "quasar_tracker"
- git reset vite # gives us vite branch overwritten with quasar_tracker changes.
- make sure that sort-package-json is installed
- yarn sort-package-json
- check package.json for updates
- check rest of files for updates
- commit required new updates.