# toasty

Vanilla, lightweight toast notifications without jQuery.

Inspired by:
- https://dev.to/arafat4693/how-to-create-a-toast-notification-in-javascript-261d
- https://github.com/CodeSeven/toastr

## Setup

Include the source files:
```html
<link rel="stylesheet" href="toasty.css" />
<script src="toasty.js"></script>
```

_optional:_ Include [Font Awesome](https://fontawesome.com/) for icons:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />
```

## Usage

Create a container for the toasts to appear in:
```html
<ul class="notifications"></ul>
```

Display toasts with default messages:
```js
toasty.info();      // "info"
toasty.success();   // "success"
toasty.warning();   // "warning"
toasty.error();     // "error"
```

Display toasts with messages:
```js
toasty.info("👋🏾 Hello");
toasty.success("😊 Yay!");
toasty.error("😨 Oh no!");
toasty.warning("😟 Careful...");
```
