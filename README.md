# StealMy.css
CSS Utilities you can download--or just copy

## [Live Example](https://codepen.io/BrianRosamilia/pen/BRRvRJ)
## [Source](https://github.com/BrianRosamilia/StealMy.css/blob/master/smy.css)

```
.segment {
  position: relative;
  box-shadow: 0px 1px 2px 0 rgba(34, 36, 38, 0.15);
  margin: .1rem .1em;
  padding: .4rem;
  border: 1px solid rgb(240,240,240);
}

.segment.lite {
  box-shadow:none;
}

.flip-vertical {
  -moz-transform: scale(-1, 1);
  -webkit-transform: scale(-1, 1);
  -o-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}

.flip-horizontal {
  -moz-transform: scale(1, -1);
  -webkit-transform: scale(1, -1);
  -o-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}

.divider {
  margin: 1rem 0rem;
  line-height: 1;
  height: 0em;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  color: rgba(0, 0, 0, 0.85);
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
  border-top: 1.2px solid rgba(34, 36, 38, 0.15);
  border-bottom: 1.2px solid rgba(255, 255, 255, 0.1);
}

/* Must have relative positioned parent */
.emblem {
  font-weight:bold;
  position:absolute;
  left:1%;
  top:2%;
  padding-left:.3em;
  padding-right:.3em;
  padding-top:.3em;
}

.ellipsis {
  max-width: 100%; 
  overflow: hidden !important;
  text-overflow: ellipsis !important;
  white-space: nowrap !important;
  word-wrap: normal !important;
}

.indent {
  margin-left:1.3em;
}

.indent-under ~ * {
  margin-left:1.3em
}

.unselectable {
   -webkit-user-select: none;
   -khtml-user-select: none;
   -moz-user-select: -moz-none;
   -o-user-select: none;
   user-select: none;
}

.hidden {
  display:none;
}

.inline {
  display:inline-block;
}

.pointer {
  cursor:pointer;
}

.bold {
  font-weight:bold;
}
```

Note: segment and divider are simplified versions of classes in [Semantic UI](https://semantic-ui.com/).
