Firefox Revert Proton
---

Reverts Firefox Proton to Photon

### Installation
  1. In your search bar, type `about:config` and hit enter.
  2. Accept the risk and continue.
  3. Search for the preference `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true`.
  4. In your search bar again, type `about:support` and hit enter.
  5. Look for `Profile Folder` and click on `Open Folder`.
  6. Within that folder, create a new folder called `chrome` if it doesn't exist already.
  7. Drop your `userChrome.css` & `userContent.css` of preference into it. You can choose between 
  [normal](https://github.com/BGMP/firefox-revert-proton/tree/trunk/normal) and 
  [compact](https://github.com/BGMP/firefox-revert-proton/tree/trunk/compact).
  8. Restart FireFox, and everything should load as intended. 

### Thanks To
  * [intrnl](https://github.com/intrnl): For starting the project and allowing me to continue maintaining it in time.
