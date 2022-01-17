# [Target #7 - Leafy Trail](https://cssbattle.dev/play/7)

![](https://github.com/Naman-Saxena1/CSS-Battle.dev-Practice/blob/main/Targets/Battle1-%237Leafy_Trail.PNG)

```HTML
<div id="main-container">
  <div id="left-div"></div>
  <div id="center-div"></div>
  <div id="right-div"></div>
</div>
<style>
  body{
    background-color: #0B2429;
    margin: 0;
    display: flex;
  }
  #main-container {
    margin: auto;
    width: 250px;
    height: 150px;
    background: #0B2429;
    display: flex;
  }
  #left-div
  {
    z-index: 1;
    width: 100%;
    height: 100%;
    background-color: #1A4341;
    border-radius: 100px 0 ;
  }
  #center-div
  {
    z-index: 2;
    margin-left: -40%;
    width: 100%;
    height: 100%;
    background-color: #998235;
    border-radius: 100px 0 ;
  }
  #right-div
  {
    flex-grow : 1;
    z-index: 3;
    margin-left: -40%;
    width: 100%;
    height: 100%;
    background-color: #F3AC3C;
    border-radius: 100px 0 ;
  }
</style>

```
