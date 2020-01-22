# Setup Angular with Bootstrap

- Setup bootstrap locally (project node_modules only) `npm install --save bootstrap`
- Add bootstrap details to script and style tags

```
"projects": {
  "mirage": {
    "projectType": "application",
    "schematics": {},
    "root": "",
    "sourceRoot": "src",
    "prefix": "app",
    "architect": {
      "build": {
        "builder": "###",
        "options": {
          "outputPath": "##",
          "index": "##.html",
          "main": "##.ts",
          "polyfills": "###",
          "tsConfig": "###",
          "aot": false,
          "assets": [
            "###",
            "##"
              ],
          "styles": [
            "src/styles.css",
            "node_modules/bootstrap/dist/css/bootstrap.min.css"
          ],
          "scripts": [
            "node_modules/jquery/dist/jquery.min.js",
            "node_modules/bootstrap/dist/js/bootstrap.min.js"
          ]
```
