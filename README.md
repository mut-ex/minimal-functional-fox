# minimal-functional-fox

If you are looking for a minimal, yet functional Firefox userChrome stylesheet...you might like this one!

## Preview

![userChrome.css preview 1](https://github.com/turing753/myuserchrome/blob/master/preview_1.png)

![userChrome.css preview 2](https://github.com/turing753/myuserchrome/blob/master/preview_2.png)

## Features

* Mimimal bloat
* Easy way to quickly change the colors to your liking
* Pinned tabs are re-styled to be easy to identify
* Tab list underneat the navigator area
* Centered URL bar, with a thinner, centered result list
* Debloated history, and bookmarks sidebars
* Fix for buggy shadows on Linux

## Instructions

* Make sure that you have enabled the userChrome.css option
  1. Go to the address `about:config` in Firefox
  2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
  3. Confirm the option is set to true

* Make sure that you have the `Dark` theme enabled
  1. Go to the address `about:addons`
  2. Select `Themes`
  3. Enable the `Dark` theme if not already enabled

* Copy the contents of this repository to `.mozilla/firefox/<your-profile-name>/chrome/`

* [You can find the new tab page extension here](https://addons.mozilla.org/en-US/firefox/addon/nighttab/)
