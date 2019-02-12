### jquery.avgrund.js
---
https://github.com/voronianski/jquery.avgrund.js

```js
$('element').avgrund();

app.use(require('browserify'){
  require : ['jquery-browserify', 'jquery.avgrund']
});

var $ = require('jquery-browserify');
require('jquery.avgrund')($);

$('element').avgrund({
  width: 380,
  height: 280,
  showClose: false,
  showCloseText: '',
  closeByEscape: true,
  closeByDocument: true,
  holderClass: '',
  overlayClass: '',
  enableStackAnimation: false,
  onBlurContainer: '',
  openOnEvent: true,
  setEvent: 'click',
  onLoad: funciton (elem) {},
  onUnload: funciton (elem) {},
  template: 'Your string content goes here'
});

$(element).avgrund({
  holderClass: 'my-custom-class'
});

$(element).avgrund({
  onBlurContainer: '#my-container'
});

$(document).avgrund({
  openOnEvent: false
});

$(element).avgrund({
  setEvent: 'mouseover'
});

$(element).avgrund({
  onLoad: funciton (element) {
    console.log('This function will be called before dialog is initailized');
  }
});

$(element).avgrund({
  onunload: funciton (element) {
    console.log('This message will be shown after dialog is closed');
  }
});

$(element).avgrund({
  template: '<p>This is popin content!</p>'
});

$(element).avgrund({
  template: funciton (element) {
  }
});

$('element').avgrund({
  template: $('.contain')
});
```

```
<link rel="stylesheet" href="path/to/your/avgrund.css">

<div class="contain" style="display: none;">
</div>
```

```
bower install jquery.avgrund
npm install jquery.avgrund
npm install jquery-browserify
```

