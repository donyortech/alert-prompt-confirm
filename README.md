# alert-prompt-confirm

### DOWNLOAD & INSTALL

```
npm install sweetalert2
```
```html
<script src="//cdn.jsdelivr.net/npm/sweetalert2@11"></script>
```

###  files:
```html
<script src="sweetalert2.all.min.js"></script>
```
```html
script src="sweetalert2.min.js"></script>
<link rel="stylesheet" href="sweetalert2.min.css">
```

## example:
```html
<button class="btn" type="button" id="click">Click me</button>
```
```js
$("#click").on("click", function () {
  Swal.fire({
  title: 'Error!',
  text: 'Do you want to continue',
  icon: 'error',
  confirmButtonText: 'Cool'
  })
});
