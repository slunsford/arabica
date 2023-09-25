# Arabica Changelog

## 1.0.1 - Jan 20, 2015
Changed files: `assets/css/screen.css`, `package.json`, `README.md`
- Updated blog description to uppercase to be consistent with other elements
- Fixed issue with link colors and lists
- Other tweaks and fixes

## 1.0.2 - Feb 26, 2015
Changed files: `default.hbs`, `package.json`
- Updated link to Arabica in site footer

## 1.0.3 - Mar 1, 2015
Changed files: `default.hbs`, `assets/css/screen.css`, `package.json`, `README.md`
Added file: `partials\navigation.hbs`
- Support for Ghost navigation (replaces previous navigation)
- Current page highlighted in navigation (except Home)

## 1.1 - Mar 28, 2017
- Added popover footnotes
- Added option to show post excerpts
- Added support for post images
- Added support for tag pages with tag name, image, and description

## 1.1.1 - Apr 4, 2017
- Removed the top margin on the tag page header
- Changed the Twitter link in the footer to use the profile saved in settings
- Added a Facebook link in the footer using the page saved in settings

## 1.1.2 - Jun 22, 2017
- Fix for source code appearing above title

## 2.0.0 - Aug 5, 2017
- Ghost 1.0 compatibility
- **Breaks compatibility with older versions of Ghost** (Not all features will work as expected)

## 2.0.1 - Jun 17, 2018
- Hid the horizontal rule above the hidden footnotes section
- Added a `.yt-wrapper` class to scale embedded YouTube videos to post width

## 2.1 - Jun 25, 2018
- Added Koenig editor support – new image classes and captions
- Behavior of "Home" or "Blog" nav links are now the same – gray when current, only orange on hover
- Images less than the width of a post are now centered

## 2.2 - Nov 3, 2018
- Dark mode (triggered by `prefers-color-scheme: dark` media query)
- Removed Bigfoot folder, keeping just the files actually used

## 2.2.1 - March 22, 2019
- Removed visited link style

## 2.2.2 - Sept 25, 2023 (final release)
- Updated homepage and author in package.json
- Added note about archiving to readme
