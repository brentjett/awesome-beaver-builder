# Awesome Beaver Builder Extensions
Awesome Extensions for the [Beaver Builder](https://www.wpbeaverbuilder.com/) plugin for WordPress

## Modules
Modules to add to your theme or plugin
[Fotoplugins](http://fotoplugins.com/) has several useful module plugins. Some free, some paid. I'll list them individually later.

## Layouts
Have you designed a layout you'd like to share? Shoot me a link!

## Beaver Builder-friendly Themes

## Common Snippets

Function to check if a page is using a builder layout:
```php
<?php
function is_builder_layout() {
  if (class_exists( 'FLBuilderModel' ) && FLBuilderModel::is_builder_enabled()) return true;
  return false;
}
?>
```
