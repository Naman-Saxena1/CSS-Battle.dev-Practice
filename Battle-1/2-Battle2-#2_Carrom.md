# [Target #2 - Carrom](https://cssbattle.dev/play/2)

![](https://github.com/Naman-Saxena1/CSS-Battle.dev-Practice/blob/main/Targets/Battle1-%232_Carrom.PNG)

```HTML
<div id="main-container">
	<div class="child-items">
      <div class="small-squares"></div>
      <div class="small-squares"></div>
  	</div>
	<div class="child-items">
      <div class="small-squares"></div>
      <div class="small-squares"></div>
  	</div>
</div>
<style>
  body
  {
    background-color: #62374e;
    display: flex;
  }
 #main-container {
    width: 300px;
    height: 200px;
   	margin : auto;
    background: #62374e;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  .child-items{
    background-color: #62374e;
    width:100%;
    height:50px;
    display: flex;
    justify-content: space-between;
  }
  .small-squares{
    width: 50px;
    height: 50px;
    gap:2rem;
    background-color: #fdc57b;
  }
</style>
```
