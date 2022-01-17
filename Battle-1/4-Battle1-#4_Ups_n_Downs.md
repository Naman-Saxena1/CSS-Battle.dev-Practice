# [Target #4 - Ups n Downs](https://cssbattle.dev/play/4)

![](https://github.com/Naman-Saxena1/CSS-Battle.dev-Practice/blob/main/Targets/Battle1-%234_Ups_n_Downs.PNG)

```HTML
<div id="main-container">
  <div class="items invisible-items"></div>
  <div class="items upper-items"></div>
  <div class="items invisible-items"></div>
  <div class="items lower-items" ></div>
  <div class="items invisible-items"></div>
  <div class="items lower-items"></div>
</div>
<style>
  body{
    background-color: #62306D;
    margin : 0;
  }
  #main-container {
    position: absolute; /*Can also be `fixed`*/
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    margin: auto;
    width: 300px;
    height: 200px;
    background: #62306D;
    display: flex;
    flex-wrap: wrap;
  }
  .items
  {
    width: 100px;
    height: 50%;
    gap: 1rem;
    background-color: #F7EC7D;
  }
  .upper-items
  {
    border-radius: 50% 50% 0 0; 
  }
  .lower-items
  {
    border-radius: 0 0 50% 50%; 
  }
  .invisible-items
  {
    background-color: #62306D
  }
</style>
```
