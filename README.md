# versioning-automate
Automate Release Tagging and Versioning in Package.json

# Example
add a file in your project like writeVersion.js
  `const version = require(release-versioning);`
execute the file 
  `node writeVersion`

# Note
The script follows semantic versioning pattern. So when asked for updating version in package.json, provide output accordingly.
If you wish to have a customised version then append `rc` in the version number. 
