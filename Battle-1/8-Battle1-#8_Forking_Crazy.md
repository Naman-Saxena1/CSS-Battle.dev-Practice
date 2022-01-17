# [Target #8 - Forking Crazy](https://cssbattle.dev/play/8)

![](https://github.com/Naman-Saxena1/CSS-Battle.dev-Practice/blob/main/Targets/Battle1-%238_Forking_Crazy.PNG)

```HTML
<!--Method 1-->
<div id="main-container">
  <div id="fork-front">
    <div class="tines"></div>
    <div class="tines"></div>
    <div class="tines"></div>
    <div class="tines"></div>
    <div class="tines"></div>
    <div class="tines"></div>
    <div class="tines"></div>
  </div>
  <div id="fork-root">
  </div>
  <div id="fork-handle">
  </div>
</div>
<style>
  body{
    background-color: #6592CF;
    margin:0;
    display: flex;
    justify-content: center;
  }
  #main-container {
    margin-top: 50px;
    width: 140px;
    height: 250px;
    background: #6592CF;
    display: flex;
    flex-direction:column;
  }
  #fork-front
  {
    z-index:2;
    width: 100%;
    height:110px;
    background: rgba(0, 0, 0, 0);
    opacity:;
    display: flex;
  }
  .tines:nth-child(odd)
  {
    width: 20px;
    background-color:#060F55;
    border-radius: 2rem 2rem 0 0;
  }
  .tines:nth-child(even)
  {
    width: 20px;
    background-color:#6592CF;
    border-radius: 0 0 1rem 1rem;
  }
  #fork-root
  {
    z-index:1;
    width: 100%;
    height:100px;
    margin-top: -10px;
    background-color:#060F55;
    border-radius: 0 0 5rem 5rem;
  }
  #fork-handle
  {
    width: 15%;
    height: 52px;
    margin: auto;
    margin-top: -2px;
    background-color:#060F55;
  }
</style>




<!--Method 2-->
<div id="main-container">
  <div id="fork-front">
    <div id="upper-front">
      <div class="tines"></div>
      <div class="tines"></div>
      <div class="tines"></div>
      <div class="tines"></div>
      <div class="tines"></div>
      <div class="tines"></div>
      <div class="tines"></div>
    </div>
    <div id="lower-front"></div>
  </div>
  <div id="fork-root"></div>
  <div id="fork-handle"></div>
</div>
<style>
  body{
    background-color: #6592CF;
    margin:0;
    display: flex;
    justify-content: center;
  }
  #main-container
  {
    position:absolute;
    width:140px;
    height:250px;
    bottom:0;
    background-color:#6592CF;
    display:flex;
    flex-direction:column;
  }
  #fork-front
  {
    width: 140px;
    height: 110px;
    background-color: #6592CF;
    display: flex;
    flex-direction:column;
  }
  #upper-front
  {
    z-index:2;
    width: 100%;
    height: 50%;
    background-color: #6592CF;
    display: flex;
  }
  .tines
  {
    width: 20px;
    height: 100%;
    background-color:white;
  }
  .tines:nth-child(odd)
  {
    background-color: #060F55;
    border-radius: 11px 10px 0 0;
  }
  .tines:nth-child(even)
  {
    padding-top: 55px;
    background-color: #6592CF;
    border-radius: 0 0 15px 15px;
  }
  #lower-front
  {
    z-index:1
    width: 100%;
    height: 50%;
    background-color: #060F55;
  }
  #fork-root
  {
    width: 140px;
    height: 90px;
    background-color: #060F55;
    border-radius: 0 0 80px 80px;
  }
  #fork-handle
  {
    width: 21px;
    height: 51px;
    margin:auto;
    margin-top:-1px;
    background-color: #060F55;
  }
</style>

```
