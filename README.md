# swipingSideMenu
Draggable adaptive sidebar

<a href="http://troll-winner.16mb.com/demo/swiping-side-menu/" target="_blank">Live Demo</a>

Default options:
===============
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
