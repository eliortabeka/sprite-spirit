# Sprite Spirit

SCSS Mixin that Brings Image Sprite to **life**

**Quick start using CDN:**
```
https://unpkg.com/sprite-spirit@1.0.0/scss/sprite-spirit.scss
```

**Using npm:**
```
npm install sprite-spirit
```

**Using bower:**
```
bower install sprite-spirit
```

### Usage
Include Sprite Spirit Mixin in your project and then use it like:
```html
@include spriteSpirit($name, $url, $vertical, $width, $height, $frameNum, $duration: .8, $iteration: 0, $reverse: nil);
```

* **$name** - String - Animation Name
* **$url** - String - Image Sprite Path
* **$vertical** - Boolean - Vertical Sprite?
* **$width** - Number - Image Sprite Width
* **$height** - Number - Image Sprite Height
* **$frameNum** - String - Animation Frames
* **$duration** - Number - Animation Duration - .6 is Default
* **$iteration** - Number - Animation Iteration - 0 is Infinity
* **$reverse** - Boolean - Reverse Animation

#### Demo of Usage
https://eliorshalev.github.io/sprite-spirit/


### Image Sprite to Animation Generator:
https://eliorshalev.github.io/sprite-spirit/


### Credit

Handcrafted with love by [Elior Shalev Tabeka](http://codepen.io/eliorshalev)
