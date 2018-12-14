## raw html

```html 
 <style>
    #box-container {
      height: 500px;

    }

    #box-1 {
      background-color: dodgerblue;
      width: 50%;
      height: 50%;

    }

    #box-2 {
      background-color: orangered;
      width: 50%;
      height: 50%;

    }
  </style>
  <div id="box-container">
    <div id="box-1"></div>
    <div id="box-2"></div>
  </div>
```

---

## DOM tree

```
- HTML
  |- HEAD
  |  |- STYLE
  |  |  |- #text: #box-container { height: 500px; } #box-1 { background-color: dodgerblue; width: 50%; height: 50%; } #box-2 { background-color: orangered; width: 50%; height: 50%; }
  |  |
  |  |- #text:
  |
  |- BODY
     |- DIV id="box-container"
        |- #text:
        |- DIV id="box-1"
        |- #text:
        |- DIV id="box-2"
        |- #text:
```

---

## rendered html

 <style>
    #box-container {
      height: 500px;

    }

    #box-1 {
      background-color: dodgerblue;
      width: 50%;
      height: 50%;

    }

    #box-2 {
      background-color: orangered;
      width: 50%;
      height: 50%;

    }
  </style>
  <div id="box-container">
    <div id="box-1"></div>
    <div id="box-2"></div>
  </div>

