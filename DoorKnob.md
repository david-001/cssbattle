<details>
<summary>Code Source  – <strong>600 {1259}</strong></summary>
<!-- have to be followed by an empty line! -->

```html
<div class="outercircle"></div>
<div class="innercircle"></div>
<div class="smile"></div>
<div class="leftsmallcircle"></div>
<div class="rightsmallcircle"></div>

<style>
  body {
    background-color: #191919
  }
  .outercircle {
    position: absolute;
    left: calc(50% - 80px);
    top: calc(50% - 80px);
    width: 160px;
    height: 160px;
    border-radius:50%;
    background: #824B20;
  }
  .innercircle{
    position: absolute;
    left: calc(50% - 50px);
    top: calc(50% - 50px);
    width: 100px;
    height: 100px;
    background: #E08027;
    border-radius:50%;
  }
  .smile{
    position: absolute;
    left: calc(50% - 60px);
    top: calc(50% - 60px);
    width: 80px;
    height: 80px;
    border-radius:50%;
    border: 20px solid #FFF58F;
    border-top-color: transparent;
    border-left-color: transparent;
    rotate: 45deg;
    # background: radial-gradient(circle at 40px, red, yellow);
  }
  .leftsmallcircle{
    position: absolute;
    left: 140px;
    top: 140px;
    width: 20px;
    height: 20px;
    border-radius:50%;
    background: #FFF58F
  }
  .rightsmallcircle{
    position: absolute;
    left: 240px;
    top: 140px;
    width: 20px;
    height: 20px;
    border-radius:50%;
    background: #FFF58F
  }
</style>
```

</details>
