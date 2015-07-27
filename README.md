# swipingSideMenu
Touch enabled jQuery plugin that lets you create draggable (swipe) offscreen sidebar or side menu like on android apps.

[Live Demo](http://troll-winner.16mb.com/demo/swiping-side-menu)

###Features:
* Responsive
* Touch Events
* Fully Customizable
* CSS3 3d Transitions
* Bootsrtap 3 support

### 1.Getting Started
Load jQuery(1.8+) and include plugin files

```html
<!-- Basic stylesheet -->
<link rel="stylesheet" href="swipingSideMenu/swipingSideMenu.css">
 
<!-- Include js plugin -->
<script src="swipingSideMenu/jquery.swipingSideMenu.js"></script>
```
### 2.Set up your HTML
```html
<button type="button" data-component="swiping-side-menu-toggle">
  Toggle navigation
</button>
<button type="button" data-component="swiping-side-menu-open">
  Open navigation
</button>
<button type="button" data-component="swiping-side-menu-close">
  Close navigation
</button>

<div class="swiping-side-menu" data-component="swiping-side-menu">
  <div class="swiping-side-menu-content">
    <!-- navigation and other -->
  </div>
</div>
```

### 3.Call the plugin
With [data-component="swiping-side-menu"] selector plugin starts itself. Also you can call the plugin by:

```html
$('your-selector').swipingSideMenu();
```

### 4.Use with bootstrap
Include "bootstrap.swipingSideMenu.less" file in your bootstrap-based less-file and use standard variables.

### 5. Default options:
```javascript
{
  toggleElement: '[data-component="swiping-side-menu-toggle"]',     // selector to toggle menu
  closeElement: '[data-component="swiping-side-menu-close"]',       // selector to close menu
  openElement: '[data-component="swiping-side-menu-open"]',         // selector to open menu
  backdrop: '<div class="swiping-side-menu-backdrop" data-component="swiping-side-menu-close"></div>',  // backdrop html
  body: document.body,        // just body
  swipeThreshold: 5,          // threshold before start dragging (px)
  swipeToggleDuration: 200,   // max duration between touch start and touch end to fast open/close menu (ms)
  swipeToggleDistance: 50     // minimal distance between start and end points to fast open/close menu (px)
}
```
[Live Demo](http://troll-winner.16mb.com/demo/swiping-side-menu)

License
------------
The MIT License (MIT)
