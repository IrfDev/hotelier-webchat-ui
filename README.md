# Webchat UI

## Usage

Clone repository and use HTML files from root directory and .css files from dist. Please ignore PACKAGE.JSON

```bash
git clone https://github.com/IrfDev/hotelier-webchat-ui.git
```

## Class reference

```css
// This class represent a component or section
.category-card{
 min-width: 300px;
}

// This class __casing represent an element inside the component
.__icon {
 min-width: 300px;
}
```

```html
// The stagger animations on category card and 
// text card are in css, so please update --index 
// in javascript or PHP and I'll work
<div style="--index: 3;">
<div class="category-card"></div>
</div>
```
