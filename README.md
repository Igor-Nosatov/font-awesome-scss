#fa-sass-plus
Font Awesome Sass Plus

##Install

####[Bower](http://bower.io)
```
$ bower install --save fa-sass-plus
```

##Using

####Html
```html
<ul>
  <li><a href="#">Github</a></li>
  <li><a href="#">Twitter</a></li>
</ul>
```

####1. Icon
CodePen · http://codepen.io/dnomak/pen/EaWKmr
```sass
ul li:first-child a:before
  +fa
  +fa(github)
ul li:last-child a:before
  +fa
  +fa(twitter)
```

#### 2. Size
CodePen · http://codepen.io/dnomak/pen/ByWKYR
```sass
ul li:first-child a:before
  +fa
  +fa(github)
  +fa-size(2em)
ul li:last-child a:before
  +fa
  +fa(twitter)
  +fa-size(2em)
```

#### 3. Left
CodePen · http://codepen.io/dnomak/pen/QwONgX
```sass
ul li:first-child a:after
  +fa
  +fa(github)
  +fa-left(10px)
ul li:last-child a:after
  +fa
  +fa(twitter)
  +fa-left(20px)
```

#### 4. Right
CodePen · http://codepen.io/dnomak/pen/ZYaWJb
```sass
ul li:first-child a:before
  +fa
  +fa(github)
  +fa-right(10px)
ul li:last-child a:before
  +fa
  +fa(twitter)
  +fa-right(20px)
```

####5. Align
CodePen · http://codepen.io/dnomak/pen/RNpaMR
```sass
ul li:first-child a:before
  +fa
  +fa(github)
  +fa-align(top)
ul li:last-child a:before
  +fa
  +fa(twitter)
  +fa-align(bottom)
```

####6. Rotated
CodePen · http://codepen.io/dnomak/pen/pveyLK
```sass
ul li:first-child a:before
  +fa
  +fa(github)
  +fa-rotate(90deg)
ul li:last-child a:before
  +fa
  +fa(twitter)
  +fa-rotate(180deg)
```

####7. Flipped
CodePen · http://codepen.io/dnomak/pen/JoWXBP
```sass
ul li:first-child a:before
  +fa
  +fa(github)
  +fa-flip(horizontal)
ul li:last-child a:before
  +fa
  +fa(twitter)
  +fa-flip(vertical)
```

####8. Spin
CodePen · http://codepen.io/dnomak/pen/QwpNBm
```sass
ul li:first-child a:before
  +fa
  +fa(github)
  +fa-spin(1s)
ul li:last-child a:before
  +fa
  +fa(twitter)
  +fa-spin(5s)
```
