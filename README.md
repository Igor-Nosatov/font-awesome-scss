#fa-scss-plus
Font Awesome Scss Plus

##Install

####[Bower](http://bower.io)
```
$ bower install --save fa-scss-plus
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
CodePen · [http://codepen.io/dnomak/pen/EaWKmr](http://codepen.io/dnomak/pen/EaWKmr?editors=110)
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
}
```

#### 2. Size
CodePen · [http://codepen.io/dnomak/pen/ByWKYR](http://codepen.io/dnomak/pen/ByWKYR?editors=110)
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-size(2em);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
  @include fa-size(2em);
}
```

#### 3. Left
CodePen · [http://codepen.io/dnomak/pen/QwONgX](http://codepen.io/dnomak/pen/QwONgX?editors=110)
```scss
ul li:first-child a:after {
  @include fa;
  @include fa(github);
  @include fa-left(10px);
}
ul li:last-child a:after {
  @include fa;
  @include fa(twitter);
  @include fa-left(20px);
}
```

#### 4. Right
CodePen · [http://codepen.io/dnomak/pen/ZYaWJb](http://codepen.io/dnomak/pen/ZYaWJb?editors=110)
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-right(10px);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
  @include fa-right(20px);
}
```

####5. Align
CodePen · [http://codepen.io/dnomak/pen/RNpaMR](http://codepen.io/dnomak/pen/RNpaMR?editors=110)
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-size(2em);
  @include fa-align(top);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
  @include fa-size(2em);
  @include fa-align(bottom);
}
```

####6. Rotated
CodePen · [http://codepen.io/dnomak/pen/pveyLK](http://codepen.io/dnomak/pen/pveyLK?editors=110)
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-rotate(90deg);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
  @include fa-rotate(180deg);
}
```

####7. Flipped
CodePen · [http://codepen.io/dnomak/pen/JoWXBP](http://codepen.io/dnomak/pen/JoWXBP?editors=110)
```scss
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-flip(horizontal);
}
ul li:last-child a:before {
  @include fa;
  @include fa(twitter);
  @include fa-flip(vertical);
}
```

####8. Spin
CodePen · [http://codepen.io/dnomak/pen/QwpNBm](http://codepen.io/dnomak/pen/QwpNBm?editors=110)
```scss
@include fa-spin;
ul li:first-child a:before {
  @include fa;
  @include fa(github);
  @include fa-spin(1s);
}
ul li:last-child a:before{
  @include fa;
  @include fa(twitter);
  @include fa-spin(5s);
}
```
