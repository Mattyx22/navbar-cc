# Navbar-cc
Navbar-cc is a responsive navbar made using basic technologies like HTML and CSS.

## See an example
https://mattyx22.github.io/navbar-cc/index.html

## Features 
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

## Mobile-extra
You can also find a folder called "mobile-extra" which contains the same navbar but with usage a little bit of vanilla JavaScript to provide fully responsive navbar.



