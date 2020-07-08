# Efeitos Shadow 
<div align=center>
  <img src="shadow.png" alt="shadow" width="400px">
</div>

## HTML
```html
<body>
  <div></div>
</body>
</html>
```

## CSS
```css
body{
  display: flex;
  justify-content:center;
  align-items: center;
  min-height: 100vh;
  background: #fff;
}
div {
  position: relative;
  width: 40px; 
  height: 40px; 
  background: transparente;
  box-shadow: 0 0 0 40px rgba(0,191,255, 1),
    0 0 0 80px rgba(0,191,255, 0.5),
    0 0 0 120px rgba(0,191,255, 0.3),
    0 0 0 160px rgba(0,191,255, 0.3),
    0 0 0 200px rgba(0,191,255, 0.3),
    0 0 0 240px rgba(0,191,255, 0.3),
    0 0 0 280px rgba(0,191,255, 0.2);
  border-radius: 0% 50% 50% 50%;
  transform: rotate(45deg);
}
```