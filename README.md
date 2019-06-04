# Navbar-cc
Navbar-cc is a responsive navbar made using basic technologies like HTML and CSS with a little of vanilla JavaScript.

## See an example
https://mattyx22.github.io/responsive-navbar/index.html

## Features
- fully responsive (looks nice on mobile and desktop) 
- colors of navbar can be different for both options
- fast (takes only ~6 KB)

## Usage
• Adding a button:
```html
<li class="nav-btn">
   <a href="#">Home</a>
</li>
```

• Adding a button on right side (just add nav-btn-r class):
```html
<li class="nav-btn nav-btn-r">
   <a href="#">Contact</a>
</li>
```

• Adding a dropdown:
```html
<div class="nav-dropdown">
   <ul class="nav-dropdown-ul">
      <li class="nav-dropdown-link">
         <a href="#">Option 1</a>
      </li>
      <li class="nav-dropdown-link">
         <a href="#">Option 2</a>
      </li>
   </ul>
</div>
```

• Adding a dropdown on right:
```html
<li class="nav-btn nav-btn-dropdown nav-btn-r" onclick="dropdown()">
            <a class="nav-a-href">Dropdown</a>
  ...
```



