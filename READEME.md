## CSS3 animation

-- [transform](http://www.w3cplus.com/content/css3-transform)

  * 旋转`rotate`

  compass
    ```css
    .rotate {
      @include transform(rotate(45deg));
    }
    ```

  css
  ```css
  .rotate {
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -webkit-transform: rotate(45deg);
    transform: rotate(45deg);
  }
  ```

---

  * 移动`translate` translate(x,y)  translateX(x) translateY(y)

  compass
  ```css
  .skew {
    @include transform(translate(100px, 20px));
  }
  ```
  css
  ```css
  .skew {
    -moz-transform: translate(100px, 20px);
    -ms-transform: translate(100px, 20px);
    -webkit-transform: translate(100px, 20px);
    transform: translate(100px, 20px);
  }
  ```

---

  * 缩放`scale` scale(x,y) scaleX(x) scaleY(y)

  compass
  ```css
  .scale {
    @include transform(scale(2, 1.5));
  }
  ```
  css
  ```css
  .scale {
    -moz-transform: scale(2, 1.5);
    -ms-transform: scale(2, 1.5);
    -webkit-transform: scale(2, 1.5);
    transform: scale(2, 1.5);
  }
  ```

---

  * 扭曲`skew` translate(x,y)  translateX(x) translateY(y)

  compass
  ```css
  .skew {
    @include transform(skew(30deg, 10deg));
  }
  ```
  css
  ```css
  .skew {
    -moz-transform: skew(30deg, 10deg);
    -ms-transform: skew(30deg, 10deg);
    -webkit-transform: skew(30deg, 10deg);
    transform: skew(30deg, 10deg);
  } 
  ```

---

  * 矩阵变形`matrix`

  compass
  ```css
  .skew {
    @include transform(skew(30deg, 10deg));
  }
  ```
  css
  ```css
  .skew {
    -moz-transform: skew(30deg, 10deg);
    -ms-transform: skew(30deg, 10deg);
    -webkit-transform: skew(30deg, 10deg);
    transform: skew(30deg, 10deg);
  } 
  ```


-- [transition](http://www.w3cplus.com/content/css3-transition)

-- [animation](http://www.w3cplus.com/content/css3-animation)