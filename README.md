## ESOP Web Brand Standards Components

All styles are based on [Bootstrap 4.](https://getbootstrap.com)

A demo of the styles below can be found [here](https://tbiddy.github.io/esop-web-standards/).

Code snippets for quick integration are listed below. Please consult the brand standards PDF for additional details.

## Navbars [Bootstrap Navbar Page](http://getbootstrap.com/docs/4.0/components/navbar/)

### Blue Navbar (Default)
```html
<header>
  <nav class="navbar navbar-expand-lg navbar-dark fixed-top bg-blue">
    <a class="navbar-brand" href="#">
    <img src="public/brand/ESOP_WHITE.svg" width="60" height="60">
    <span style="color:#b6bf00">|</span> The ESOP Association
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarCollapse">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="btn btn-outline-light nav-btn ml-5" href="#">Join</a>
        </li>
        <li class="nav-item">
          <a class="btn btn-green nav-btn ml-2 mr-5" href="https://getbootstrap.com/docs/4.0/examples/sign-in/">Log In</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
      </ul>
      <form class="form-inline mt-2 mt-md-0">
        <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-yellow my-2 my-sm-0" type="submit">Search</button>
      </form>
    </div>
  </nav>
</header>
```

### White Navbar (Alternative)
```html
<header>
  <nav class="navbar navbar-expand-lg navbar-light fixed-top box-shadow" style="background-color:#fff">
    <a class="navbar-brand" href="#">
    <img src="public/brand/ESOP_logo.svg" width="60" height="60">
    | <span style="color:#0082bb">The ESOP Association</span>
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarCollapse">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="btn btn-outline-blue nav-btn ml-5" href="#">Join</a>
        </li>
        <li class="nav-item">
          <a class="btn btn-green nav-btn ml-2 mr-5" href="https://getbootstrap.com/docs/4.0/examples/sign-in/">Log In</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
      </ul>
      <form class="form-inline mt-2 mt-md-0">
        <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search" style="background-color:#f2f2f2">
        <button class="btn btn-outline-yellow my-2 my-sm-0" type="submit">Search</button>
      </form>
    </div>
  </nav>
</header>
```

## Text
To use the serif fonts (Freight Micro Pro):
* Use the `.serif` class for `<h1>` through `<h6>`.
* Use `.serif-text` for `<p>` text.
* Use `.serif-lead` to use the original Bootstrap `.lead` class for serif fonts.

## Buttons [Bootstrap Buttons Page](http://getbootstrap.com/docs/4.0/components/buttons/)

### Solid Buttons
```html
<button type="button" class="btn btn-blue">ESOP Blue</button>
<button type="button" class="btn btn-yellow">ESOP Yellow</button>
<button type="button" class="btn btn-purple">ESOP Purple</button>
<button type="button" class="btn btn-green">ESOP Green</button>
```
### Outline Buttons
```html
<button type="button" class="btn btn-outline-blue">ESOP Blue</button>
<button type="button" class="btn btn-outline-yellow">ESOP Yellow</button>
<button type="button" class="btn btn-outline-purple">ESOP Purple</button>
<button type="button" class="btn btn-outline-green">ESOP Green</button>
```


## Badges [Bootstrap Badges Page](http://getbootstrap.com/docs/4.0/components/badge/)

```html
<span class="badge badge-blue">Blue</span>
<span class="badge badge-yellow">Yellow</span>
<span class="badge badge-purple">Purple</span>
<span class="badge badge-green">Green</span>
```
