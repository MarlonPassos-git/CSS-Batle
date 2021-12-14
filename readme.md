dd




## **#1 - Simply Square**
<img src="imagens/1.png">
 
### Code 
    
```html
    <div></div>
    <style>
    body {
        background-color: #5d3a3a;
        margin: 0;
    }
    div {
        width: 50%;
        height: 200px;
        background: #b5e0ba;
    }
    </style>

```

## **#2 - Simply Square**
<img src="imagens/2.png">
 
### Code 
```html
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body {
    background-color: #62374e;
    margin: 0;
    padding: 50px;
    display: grid;
    grid-template:
      "a  b" 
      "c  d"
    ;
    gap: 100px 200px
  }
  div {
    height: 50px;
    width: 50px;
    background-color: #fdc57b;
  }
</style>
```

## **#3 - Push Button**
<img src="imagens/3.png">

 
### **Code**

```html
<div class="circulo"></div>
<div class="quadrado"></div>
<style>
    body {
        background-color: #6592CF;
        display: grid;
        place-items: center;
        gap: 100px 200px;
    }
    
    div {
        grid-column: -1 \ 1;
        grid-row: -1 / 1;
    }
    .circulo {
        height: 50px;
        width: 50px;
        background-color: #EEB850;
        border-radius: 50%;
        border: 50px solid #243D83;
        outline: 50px solid #6592CF;
    }
    .quadrado {
        width: 300px;
        height:150px;
        background-color: #243D83;
        z-index: -1;
    }
</style>
```
