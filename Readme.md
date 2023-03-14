# Palm pay website

## Issues 

### Section

Fixed the css for <section> element

### Navbar toggler

I prevent navbar toggler from wrapping on extra small screens

```html


<div class="d-flex flex-nowrap w-100 justify-content-between">
    <a href="#" class="navbar-brand">
        <img src="./logos/palmpay_logo.png" class="logo" alt="">
    </a>

    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navmenu">
        <span class="navbar-toggler-icon"></span>
    </button>
</div>

```

[link](https://stackoverflow.com/questions/58584147/keep-brand-and-toggler-on-same-row-when-screen-very-small-bootstrap-4)