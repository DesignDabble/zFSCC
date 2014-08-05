# Template to start new Codekit using Foundation + Compass + Sass

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

Foundation File Structure (changes to make within in your text editor)
1. Open _settings.scss and comment out "@import foundation" [Uncomment functions as your project progresses]
2. Create a newfile within /stylesheets called _custom-settings.scss
3. At the end of the document type: "@import "custom-settings""
4. This is where you will input all of your custom CSS

Changes to _settings.scss that will make your life easier
1. Include custom global mixins like font and color at the top of this file use Sass mixins to incorporate them into your styles as you move along
2. This will make it easier for you to implement changes via sass files and not get compiling errors

