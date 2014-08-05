# Foundation Compass Template

The easiest way to get started with Foundation + Compass.

## Requirements

  * Ruby 1.9+
  * [Node.js](http://nodejs.org)
  * [compass](http://compass-style.org/): `gem install compass`
  * [bower](http://bower.io): `npm install bower -g`

## Quickstart

  * [Download this starter compass project and unzip it](https://github.com/zurb/foundation-compass-template/archive/master.zip)
  * Run `bower install` to install the latest version of Foundation
  
Then when you're working on your project, just run the following command:

```bash
compass watch
```

## Upgrading

If you'd like to upgrade to a newer version of Foundation down the road just run:

```bash
bower update
```

## Codekit Instructions

In Codekit:

Create an empty folder anywhere in your directory i.e. ../Desktop/Zurb5.3.3

In Codekit: 
1. Click the menu-icon (top-left)
2. Click 'New Zurb Foundation Project...' and choose the empty folder you just created
3. Back in Codekit make sure you project is selected and click the settings icon
4. In Frameworks>Compass change the file outputs accordingly (sass --> scss)
5. Open config.rb in Finder 
6. Beneath "# Require any additional compass plugins here." --> paste "add_import_path "bower_components/foundation/scss"

Foundation File Structure - In your text editor
1. Open _settings.scss and comment out "@import foundation"
2. You can uncomment functions as your project progresses
3. At the bottom of the document type: "@import "custom-settings"" --> create a newfile within /stylesheets called _custom-settings.scss
4. This is where you will input all of your custom CSS

General changes _settings.scss that will make your life easier
1. Include custom global mixins like font and color at the top of this file use Sass mixins to incorporate them into your styles as you move along
2. This will make it easier for you to implement changes into the sass files and not get foundation's overrides

