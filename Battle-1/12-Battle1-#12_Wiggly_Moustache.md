# [Target #12 - Wiggly Moustache](https://cssbattle.dev/play/12)

![]()

```HTML
<div id="left-end"></div>
<div id="left-side"></div>
<div id="center"></div>
<div id="right-side"></div>
<div id="right-end"></div>
<style>
  body{
    background-color:#F5D6B4;
    margin:0;
  }
  #left-end
  {
    position: absolute;
    width: 20px;
    height: 20px;
    background-color: #D86F45;
    top: 140px;
    left: 310px;
    border-radius: 100%;
  }
  #left-side {
    position: absolute;
    width: 60px;
    height: 30px;
    top: 150px;
    left:70px;
    border: 20px solid #D86F45;
    border-radius: 0 0 100px 100px;
    border-top:0
  }
  #center {
    position: absolute;
    width: 60px;
    height: 30px;
    top: 100px;
    left:150px;
    border: 20px solid #D86F45;
    border-radius: 100px 100px 0 0;
    border-bottom:0
  }
  #right-side {
    position: absolute;
    width: 60px;
    height: 30px;
    top: 150px;
    left:230px;
    border: 20px solid #D86F45;
    border-radius: 0 0 100px 100px;
    border-top:0
  }
  #right-end
  {
    position: absolute;
    width: 20px;
    height: 20px;
    background-color: #D86F45;
    top: 140px;
    left: 70px;
    border-radius: 100%;
  }
</style>
```