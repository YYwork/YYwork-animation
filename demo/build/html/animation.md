<style type="text/css">
  .tansform {
    position: relative;
  }

  .demo {
    border: 1px solid #ddd;
    background-color: #fff;
    text-align: center;
  }

  .square {
    display: inline-block;
    vertical-align: middle;
    *vertical-align: auto;
    *zoom: 1;
    *display: inline;
    width: 100px;
    height: 100px;
    background-color: #37a508;
    border: 1px solid #555;
  }

  .demo-vertical {
    position: absolute;
    display: inline-block;
    vertical-align: middle;
    *vertical-align: auto;
    *zoom: 1;
    *display: inline;
    width: 100px;
    height: 100%;
    border: 1px solid #ddd;
    left: 50%;
    margin-left: -50px;
  }

  .rotate {
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -webkit-transform: rotate(45deg);
    transform: rotate(45deg);
  }

  .translate {
    -moz-transform: translate(100px, 20px);
    -ms-transform: translate(100px, 20px);
    -webkit-transform: translate(100px, 20px);
    transform: translate(100px, 20px);
  }

  .translate-x {
    -moz-transform: translateX(100px);
    -ms-transform: translateX(100px);
    -webkit-transform: translateX(100px);
    transform: translateX(100px);
  }

  .translate-y {
    -moz-transform: translateY(20px);
    -ms-transform: translateY(20px);
    -webkit-transform: translateY(20px);
    transform: translateY(20px);
  }

  .scale {
    -moz-transform: scale(2, 1.5);
    -ms-transform: scale(2, 1.5);
    -webkit-transform: scale(2, 1.5);
    transform: scale(2, 1.5);
  }

  .scale-x {
    -moz-transform: scaleX(2);
    -ms-transform: scaleX(2);
    -webkit-transform: scaleX(2);
    transform: scaleX(2);
  }

  .scale-y {
    -moz-transform: scaleY(1.5);
    -ms-transform: scaleY(1.5);
    -webkit-transform: scaleY(1.5);
    transform: scaleY(1.5);
  }

  .skew {
    -moz-transform: skew(30deg, 10deg);
    -ms-transform: skew(30deg, 10deg);
    -webkit-transform: skew(30deg, 10deg);
    transform: skew(30deg, 10deg);
  }

  .skew-x {
    -moz-transform: skewX(30deg);
    -ms-transform: skewX(30deg);
    -webkit-transform: skewX(30deg);
    transform: skewX(30deg);
  }

  .skew-y {
    -moz-transform: skewY(10deg);
    -ms-transform: skewY(10deg);
    -webkit-transform: skewY(10deg);
    transform: skewY(10deg);
  }

</style>
<h2>tansform</h2>
<div class="tansform">
  <h1>基本位置对照</h1>
  <div class="demo-vertical"></div>
  <div class="demo">
    <div class="square">text</div>
  </div>
  <h2>旋转 rotate</h2>
  <div class="demo">
    <div class="square rotate">text</div>
  </div>
  <h2>扭曲 translate</h2>
  <div class="demo">
    <div class="square translate">text</div>
  </div>
  <h3>扭曲 translateX</h3>
  <div class="demo">
    <div class="square translate-x">text</div>
  </div>
  <h3>扭曲 translateY</h3>
  <div class="demo">
    <div class="square translate-y">text</div>
  </div>
  <h2>缩放 scale</h2>
  <div class="demo">
    <div class="square scale">text</div>
  </div>
  <h3>缩放 scaleX</h3>
  <div class="demo">
    <div class="square scale-x">text</div>
  </div>
  <h3>缩放 scaleY</h3>
  <div class="demo">
    <div class="square scale-y">text</div>
  </div>
  <h2>扭曲 scale</h2>
  <div class="demo">
    <div class="square skew">text</div>
  </div>
  <h3>扭曲 scaleX</h3>
  <div class="demo">
    <div class="square skew-x">text</div>
  </div>
  <h3>扭曲 scaleY</h3>
  <div class="demo">
    <div class="square skew-y">text</div>
  </div>
</div>