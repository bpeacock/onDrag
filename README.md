New Library
===========

Usage
-----

Installation `npm install ondrag`

```javascript
drag('#myEl', {
    tag:   "myDrag",
    helper: "clone",
    start: function() {
        
    },
    move: function() {
        
    },
    stop: function() {

    },
    constrain: element //or selector, or function
});

drag.drop('#dropTarget', {
    tag: "myDrag",
    hover: function() {

    },
    hoverClass: 'myHoverClass',
    drop: function() {

    }
});
```

Development
-----------

To Build: `grunt build`

To Develop: `grunt watch`

To Test: `npm test`
