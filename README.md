# Awesome Beaver Builder Extensions
Awesome Extensions for the [Beaver Builder](https://www.wpbeaverbuilder.com/) plugin for WordPress

## Modules
Modules to add to your theme or plugin

[Fotoplugins](http://fotoplugins.com/) has several useful module plugins. Some free, some paid. I'll list them individually later.
* [SW PushMenu Module](http://fotoplugins.com/downloads/responsive-off-canvas-menu/)
* [SW Social Share Module](http://fotoplugins.com/downloads/sw-social-share/)
* [SW Responsive Tables Module](http://fotoplugins.com/downloads/sw-responsive-tables/)
* [SW Custom Footer Module](http://fotoplugins.com/downloads/sw-custom-footer/)
* [SW Countdown Module](http://fotoplugins.com/downloads/sw-countdown-module/)
* [SW PDF Viewer Module](http://fotoplugins.com/downloads/sw-pdf-viewer-module/)
* [SW Hover Card Module](http://fotoplugins.com/downloads/sw-hover-card-module/)
* [SW Tooltip Module](http://fotoplugins.com/downloads/swtooltip-module/)
* [SW Gallery Module](http://fotoplugins.com/downloads/sw-gallery-module/)

## Layouts
Have you designed a layout you'd like to share? Shoot me a link!

## Beaver Builder-friendly Themes

## Common Snippets

How to check if a page is using a builder layout:
```php
<?php
// Include this function in functions.php of your theme.
function is_builder_layout() {
  if (class_exists( 'FLBuilderModel' ) && FLBuilderModel::is_builder_enabled()) return true;
  return false;
}

// Inside page.php I use is_builder_layout() to determine what kind of layout to display.
if (is_builder_layout()) {
  // big wide open edge-to-edge space for builder to use. Gives user the most options.
} else {
  // default page layout, two column w/ sidebar maybe? 
}
?>
```

## Add-On Plugins
* [Fotoplugins Modules Plugin](http://fotoplugins.com/downloads/fotoplugins-beaver-builder-modules/)
* [SW Beaver Builder Resizer](http://fotoplugins.com/downloads/sw-beaver-builder-resizer/)
