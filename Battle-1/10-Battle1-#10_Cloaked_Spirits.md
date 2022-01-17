# [Target #10 - Cloaked Spirits](https://cssbattle.dev/play/10)

![](https://github.com/Naman-Saxena1/CSS-Battle.dev-Practice/blob/main/Targets/Battle-1-%2310_Cloaked_Spirits.PNG)

```HTML
<!--Method 1-->
<div id="main-container">
  <div id="upper-part">
    <div class="items" id="corner-div">
      <div class="circle" id="corner-circles"></div>
    </div>
    <div class="items" id="center-div">
      <div class="circle" id="center-circle"></div>
    </div>
    <div class="items" id="corner-div">
      <div class="circle" id="corner-circles"></div>
    </div>
  </div>
  <div id="lower-part">
    <div class="corner-platform"></div>
    <div id="center-platform"></div>
    <div class="corner-platform"></div>
  </div>
</div>
<style>
  body
  {
    background-color: #62306D;
    margin:0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  #main-container {
    width: 300px;
    height: 150px;
    position:absolute;
    bottom:0;
    display:flex;
    flex-direction:column;
  }
  #upper-part
  {
    width: 300px;
    height: 100px;
    display: flex;
  }
  .items{
    width: 100px;
    height: 100px;
  }
  #corner-div
  {
    display: flex;
    justify-content: center;
    align-items:center;
  }
  #center-div
  {
    display: flex;
    justify-content: center;
    align-items:center;
  }
  .circle
  {
    width: 60px;
    height: 60px;
    border-radius: 100%
  }
  #corner-circles
  {
    background-color: #E38F66;
    box-shadow: 0 0 0 20px #AA445F;
  }
  #center-circle
  {
    background-color: #AA445F;
    box-shadow: 0 0 0 20px #E38F66;
    margin-bottom: 200px;
  }
  #lower-part
  {
    width: 300px;
    height: 50px;
    background-color: #F7EC7D;
    display: flex;
    justify-content: center;
    align-items:center;
  }
  .corner-platform
  {
    z-index: -1;
    width: 100px;
    height: 100%;
    background-color:#F7EC7D;
    margin-top:-100px;
  }
  #center-platform
  {
    z-index: -1;
    width: 100px;
    height: 100%;
    background-color:#F7EC7D;
    margin-top:-100px;
    padding-bottom: 200px;
  }
</style>




<!--Method 2-->
<div id="main-container">
  <div id="circle-container">
    <div class="corner-circle"></div>
    <div class="center-circle"></div>
    <div class="corner-circle"></div>
  </div>
  <div id="platform">
    <div class="corner-platform"></div>
    <div class="center-platform"></div>
    <div class="corner-platform"></div>
  </div>
</div>
<style>
  body
  {
    background-color: #62306D;
    margin:0;
    display: flex;
    justify-content: center;
    align-items: flex-end;
  }
  #main-container {
    width: 300px;
    height: 150px;
  }
  #circle-container
  {
    width: 300px;
    height: 100px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
  }
  .corner-circle
  {
    display: absolute;
    width: 60px;
    height: 60px;
    background-color: #E38F66;
    border-radius: 100%;
    margin: 0 10px;
    box-shadow: 0 0 0 20px #AA445F;
  }
  .center-circle
  {
    width: 60px;
    height: 60px;
    background-color: #AA445F;
    border-radius: 100%;
    margin: -200px 20px 0 20px;
    box-shadow: 0 0 0 20px #E38F66;
  }
  #platform
  {
    width: 300px;
    height: 50px;
    display: flex;
  }
  .corner-platform
  {
    z-index: -1;
    width: 100px;
    height: 100px;
    background-color: #F7EC7D;
    margin: -50px 0;
  }
  .center-platform
  {
    z-index: -1;
    width: 100px;
    height: 200px;
    background-color: #F7EC7D;
    margin: -150px 0;
  }
</style>
```
