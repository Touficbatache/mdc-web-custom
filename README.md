# mdc-web-custom
This edit for the [original mdc-web](https://github.com/material-components/material-components-web) adds some features to it like [adding a statusbar](#1-if-you-want-to-add-a-statusbar-for-use-with-the-translucent-plugin-for-phonegap), [correctly aligning the icons on the toolbar](#2-to-correctly-align-the-icons) and [fixing some other issues](#3-to-fix-the-issue-508-where-a-long-title-would-jump-to-the-next-line-making-it-go-out-of-the-toolbar-itself). You can ignore one of these changes by simply ignoring the steps that change the element itself.

#### 1. If you want to add a statusbar for use with the translucent plugin for phonegap:
  - Add the line `<div class="mdc-status-bar"></div>` directly under the `<body>` tag.
  - Add the `mdc-toolbar--statusbar` class to the toolbar element, next to the `mdc-toolbar` class.
  - Add the line `<div class="mdc-toolbar-fixed-adjust-more">` directly under the `<main>` tag.

#### 2. To correctly align the icons: 
  - Add the `align-icons` class to every `<a>` element, directly next to the `material-icons` class.
  - Add the `left-icon` class to the `<a>` class containing the menu icon.
  
#### 3. To fix the issue [#508](https://github.com/material-components/material-components-web/issues/508) (where a long title would jump to the next line, making it go out of the toolbar itself):
  - Add the `mdc-toolbar--flex-adjust` class to every section tag, next to every `mdc-toolbar__section` class.
  
> Demo files will be included in this repository, in the [demo](https://github.com/Touficbatache/mdc-web-custom/tree/master/demo) folder.
> You can also check what the page looked like [before](https://touficbatache.github.io/mdc-web-custom/demo/before.html) and [after](https://touficbatache.github.io/mdc-web-custom/demo/after.html) making the changes.
