# mdc-web-custom

If you want to add a statusbar for use with the translucent plugin for phonegap:
  - Add the line `<div class="mdc-status-bar"></div>` directly under the `<body>` tag.
  - Add the `mdc-toolbar--statusbar` class to the toolbar element next to the `mdc-toolbar` class.
  - Add the line `<div class="mdc-toolbar-fixed-adjust-more">` directly under the `<main>` tag.

To correctly align the icons: 
  - Add the `align-icons` class to every `<a>` element, directly next to the `material-icons` class.
  - Add the `left-icon` class to the `<a>` class containing the menu icon.
  
  A demo file will be included in this repository, in the [demo](../../tree/master/demo) folder.
