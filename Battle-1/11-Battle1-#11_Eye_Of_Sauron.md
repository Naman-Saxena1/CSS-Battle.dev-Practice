# [Target #11 - Eye Of Souran](https://cssbattle.dev/play/11)

![]()

```HTML
<div id="main-container">
  <div id="left-semicircle"></div>
  <div id="center-circle"></div>
  <div id="right-semicircle"></div>
</div>
<style>
  body{
    background-color: #191210;
    margin: 0;
    display: relative;
  }
  #main-container {
    width: 300px;
    height: 140px;
  }
  #left-semicircle
  {
    position: absolute;
    width: 60px;
    height: 30px;
    left: 50px;
    top: 150px;
    border: 20px solid #ECA03D;
    border-radius: 0 0 100px 100px;
    border-top:0;
  }
  #center-circle
  {
    position: absolute;
    width: 50px;
    height: 50px;
    background-color: #84271C;
    left: 175px;
    top: 125px;
    border-radius: 100%;
    box-shadow: 0 0 0 25px #191210, 0 0 0 45px #ECA03D;
  }
  #right-semicircle
  {
    position: absolute;
    width: 60px;
    height: 30px;
    bottom: 150px;
    left: 250px;
    border: 20px solid #ECA03D;
    border-radius: 100px 100px 0 0;
    border-bottom: 0;
  }
</style>
```
