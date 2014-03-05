# YACTS
**Yet Another CSS 3 Spinner &ndash; as if there wouldn't be enough of them.**

[![Spinner Preview (as a GIF)](README.md.res/spinner-preview.gif)](index.html)

From [mindrevolution](http://www.mindrevolution.com). Maintained by [Marc Stöcker](https://twitter.com/esn303).


## Looking for a lightweight CSS-only indicator?

My co-workers sometimes hit me up with the question for a "simple spinner, CSS only possibly". To safe me some time, I created this tiny repo, so I can just refer them to it. Job done, time saved. 


Click [here for a working demo page](index.html).




## Just a few lines for a nice effect!

### HTML
```html
<div class="spinner"></div>
```

### CSS (excerpt)

```css
.spinner {
  border: 10px double rgba(255, 204, 0, 0.2);
  border-top: 10px double rgba(255, 204, 0, 0.8);
  border-radius: 100%;

  -webkit-animation: rotation 0.7s infinite linear;
  -moz-animation: rotation 0.7s infinite linear;
  -o-animation: rotation 0.7s infinite linear;
  animation: rotation 0.7s infinite linear;
}

@keyframes rotation {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(359deg);
  }
}
/* see './css/yacts.css' for complete CSS */
```

### As you like: LESS, CSS, minified CSS
It's all in the [/css/ directory](css/), though there isn't any use of LESS yet. Probably a good starting point for extending it with i.e. color variables?



## Licence

YACTS is released under the MIT license:
[opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)



## Contributing

This project is open for collaboration. **Fork. Push. Innovate.**
