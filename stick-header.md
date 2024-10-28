### Add this script to add class to the nav menu

```javascript
const navbar = document.getElementById("navbar");

var sticky = 100;

window.addEventListener("scroll", function () {
  if (window.pageYOffset >= sticky) {
    navbar.classList.add("sticky");
  } else {
    navbar.classList.remove("sticky");
  }
});
```
