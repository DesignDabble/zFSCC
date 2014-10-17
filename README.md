# Codekit + Foundation + Compass + Sass Starter Template

## Setup Instructions

Create an empty folder anywhere in your directory i.e. ../Desktop/Zurb5.3.3

<h2>In Codekit</h2>
<ul>
  <li>Click the menu-icon (top-left)</li>
  <li>Click 'New Zurb Foundation Project...' and choose the empty folder you just created</li>
  <li>Back in Codekit make sure you project is selected and click the settings icon</li>
  <li>In Frameworks>Compass change the file outputs accordingly (sass --> scss)</li>
  <li>Open config.rb in Finder </li>
  <li>Beneath "# Require any additional compass plugins here." --> paste "add_import_path "bower_components/foundation/scss"</li>
</ul>

<h2>Foundation File Structure (changes to make within in your text editor)</h2>
  <ul>
    <li>Open _settings.scss and uncomment "@import foundation" [Uncomment functions as needed]</li>
    <li>Create a newfile within /stylesheets called _custom-settings.scss</li>
    <li>At the end of the document type: "@import "custom-settings""</li>
  </ul>
  
<h2>Changes to _settings.scss that will make your life easier</h2>
  <ul>
    <li>Include custom global mixins like font and color at the top of this file use Sass mixins to incorporate them into your styles as you move along</li>
    <li>This will make it easier for you to implement changes via sass files and not get compiling errors</li>
  </ul>
