<details>
<summary>Code Source  – <strong>600 (100% match) {2027}</strong></summary>

```html
<div class="face"></div>
<div class="left_ear"></div>
<div class="right_ear"></div>
<div class="left_eye"></div>
<div class="left_pupil"></div>
<div class="right_eye"></div>
<div class="right_pupil"></div>
<div class="nose"></div>

<style>
  body {
    margin: 0;
    position: relative;
    background: #ed6a9d;
  }

  .face {
    position: absolute;
    top: 90px;
    left: 110px;
    width: 180px;
    height: 150px;
    border-radius: 80%;
    background: #050044;
    z-index: 1;
  }

  .left_ear {
    position: absolute;
    top: 60px;
    left: 105px;
    width: 0;
    height: 0;
    border-left: 30px solid transparent;
    border-right: 30px solid transparent;
    border-bottom: 60px solid #050044;
    rotate: -30deg;
    z-index: -2;
  }

  .right_ear {
    position: absolute;
    top: 60px;
    left: 235px;
    width: 0;
    height: 0;
    border-left: 30px solid transparent;
    border-right: 30px solid transparent;
    border-bottom: 60px solid #050044;
    rotate: 30deg;
    z-index: -3;
  }

  .left_eye {
    position: absolute;
    top: 130px;
    left: 145px;
    width: 40px;
    height: 40px;
    background: #ffc100;
    border-radius: 50% 0;
    rotate: 45deg;
    z-index: 2;
  }

  .right_eye {
    position: absolute;
    top: 130px;
    left: 215px;
    width: 40px;
    height: 40px;
    background: #ffc100;
    border-radius: 50% 0;
    rotate: 45deg;
    z-index: 3;
  }

  .left_pupil {
    position: absolute;
    top: 135px;
    left: 160px;
    width: 10px;
    height: 30px;
    border-radius: 80%;
    background: #050044;
    z-index: 4;
  }

  .right_pupil {
    position: absolute;
    top: 135px;
    left: 230px;
    width: 10px;
    height: 30px;
    border-radius: 80%;
    background: #050044;
    z-index: 5;
  }

  .nose {
    position: absolute;
    top: 185px;
    left: 185px;
    width: 0;
    height: 0;
    border-left: 15px solid transparent;
    border-right: 15px solid transparent;
    border-bottom: 15px solid #ed6a9d;
    rotate: 180deg;
    z-index: 6;
  }
</style>
```

</details>
