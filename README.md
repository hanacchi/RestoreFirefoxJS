# RestoreFirefoxJS
userChromeJS scripts to restore Firefox features that have been removed or changed

# Installation
1. Follow the instructions for *method 3* [here](https://github.com/Aris-t2/CustomJSforFx#method-3---files-in-install-and-profile-folders).
2. Copy the scripts from this repository to the `chrome` folder in your profile directory.
3. Enable them in `userChrome.uc.js` by adding the following lines:
```javascript
load_js_script("./userChrome/view_image.uc.js");
load_js_script("./userChrome/view_video.uc.js");
load_js_script("./userChrome/copy_link_location.uc.js");
load_js_script("./userChrome/copy_image_location.uc.js");
```
