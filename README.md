# Awesome Beaver Builder Extensions
Extensions for the awesome [Beaver Builder](https://www.wpbeaverbuilder.com/) plugin for WordPress

## Table Of Contents
* [Modules](#modules)
* [Custom Field Types](#custom-field-types)
* [Add-on Plugins](#add-on-plugins)
* [Layouts](#layouts)
* [BB-friendly Themes](#beaver-builder-friendly-themes)
* [Common Snippets](#common-snippets)

## Modules
Modules to add to your theme or plugin

* [SW PushMenu Module](http://fotoplugins.com/downloads/responsive-off-canvas-menu/)
* [SW Social Share Module](http://fotoplugins.com/downloads/sw-social-share/)
* [SW Responsive Tables Module](http://fotoplugins.com/downloads/sw-responsive-tables/)
* [SW Custom Footer Module](http://fotoplugins.com/downloads/sw-custom-footer/)
* [SW Countdown Module](http://fotoplugins.com/downloads/sw-countdown-module/)
* [SW PDF Viewer Module](http://fotoplugins.com/downloads/sw-pdf-viewer-module/)
* [SW Hover Card Module](http://fotoplugins.com/downloads/sw-hover-card-module/)
* [SW Tooltip Module](http://fotoplugins.com/downloads/swtooltip-module/)
* [SW Gallery Module](http://fotoplugins.com/downloads/sw-gallery-module/)

## Custom Field Types
These are additional settings field types to use in your custom modules.
* [PDF Field Type](https://github.com/ZestSMS/BB-PDF-field)
* [Date Picker](https://github.com/ZestSMS/BB-fields)
* [Location](https://github.com/ZestSMS/BB-fields)
* [Time Picker](https://github.com/ZestSMS/BB-fields)
* [Time Range](https://github.com/ZestSMS/BB-fields)
* [Post Select](https://github.com/ZestSMS/BB-fields)
* [Select2 Drop-Down](https://github.com/ZestSMS/BB-fields/tree/master/fields/select2)

## Add-On Plugins
* [Fotoplugins Modules Plugin](http://fotoplugins.com/downloads/fotoplugins-beaver-builder-modules/)
* [SW Beaver Builder Resizer](http://fotoplugins.com/downloads/sw-beaver-builder-resizer/)
* [ZestSMS Field Types Bundle](https://github.com/ZestSMS/BB-fields)
* [BB Templates as Headers](https://github.com/jatacid/bb-template-as-header/)
* [Beaver Builder TinyMCE Advanced Icon Fix](https://github.com/r3df/r3df-beaver-builder-tinymce-advanced-icon-fix)

Also see the Beaver Builder Team's [Recommended Plugins List](https://www.wpbeaverbuilder.com/knowledge-base/recommended-plugins/) for common helpful plugins that work well with Beaver Builder.

## Layouts
Have you designed a layout you'd like to share? Shoot me a link!

## Beaver Builder-friendly Themes
Know of a free or premium theme with great [Beaver Builder](http://www.wpbeaverbuilder.com) support? Send me the link!

## Common Snippets

How to check if a page is using a builder layout:
```php
<?php
// Include this function in functions.php of your theme.
function is_builder_layout() {
  if (class_exists( 'FLBuilderModel' ) && FLBuilderModel::is_builder_enabled()) return true;
  return false;
}

// Inside page.php, single.php, or singular.php use is_builder_layout() to determine what kind of layout to display.
if (is_builder_layout()) {
  // big wide open edge-to-edge space for builder to use.
} else {
  // default page layout, two column w/ sidebar maybe? Go nuts.
}
?>
```

There is also a nice collection of [CSS Snippets for the BB Plugin](https://www.wpbeaverbuilder.com/kb/css-snippets-plugin/) and [CSS Snippets for the BB Theme](https://www.wpbeaverbuilder.com/kb/css-snippets-theme/) on the [knowledge base](https://www.wpbeaverbuilder.com/knowledge-base/)

Hope this was helpful! If you have suggestions for modules/layouts/themes/plugins/snippets feel free to send them to me as ticket or message me on the [Beaver Builder Slack team](http://beaverbuilders.slack.com) @brentjett!
