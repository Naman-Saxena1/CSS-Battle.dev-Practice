# [Target #6 - Missing Slice](https://cssbattle.dev/play/6)

![](https://github.com/Naman-Saxena1/CSS-Battle.dev-Practice/blob/main/Targets/Battle1-%236_Missing_Slice.PNG)

```HTML
<div id="main-container">
  <div class="items"></div>
  <div class="items"></div>
  <div class="items"></div>
  <div class="items"></div>
</div>
<style>
  body{
    margin:0;
    background-color: #E3516E;
  }
  #main-container {
    width: 200px;
    height: 200px;
    position: absolute;
    top: 0 ;
    right:0;
    left:0;
    bottom:0;
    margin:auto;
    background: #E3516E;
    display: flex;
    flex-wrap: wrap;
  }
  .items:nth-child(1){
    width: 50%;
    height: 50%;
    background-color:#51B5A9;
    border-radius: 100% 0 0 0;
  }
  .items:nth-child(2){
    width: 50%;
    height: 50%;
    background-color:#FADE8B;
    border-radius: 0 100% 0 0;
  }
  .items:nth-child(3){
    width: 50%;
    height: 50%;
    background-color:#F7F3D7;
    border-radius: 0 0 0 100%;
  }
</style>

```
