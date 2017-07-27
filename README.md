
<p align="center">
  <a href="www.cobi.bike"><img width="90px" height="90px" src="https://cdn.cobi.bike/devkit/resources/images/devkit-logo.svg">
  </a>

  <h3 align="center">COBI UI Components</h3>

  <p align="center">
    Sleek, intuitive, and scalable UI Components for faster and easier COBI webApp development.
    <br> <br>
    <a href="www.cobi.bike"><strong>Explore COBI DevKit website &raquo;</strong></a>
    <br>
    <br>
  </p>
</p>

<br>

## Description

These UI Components will let you to create Sleek, Intuitive and Scalable WebApp's. Build complex settings page, description view's for your WebApp's. Just grab one example and use it in your project! Read the instructions below how to start and create your own WebApp and run it on COBI!

### Getting Started

All you have to do is just include cobi-style.css and cobi-style.js files to your project!

#### CSS:
``` html
<link href="https://cdn.cobi.bike/devkit/css/cobi-style.css" rel="stylesheet">
```
#### JS:
``` html
 <script src="https://cdn.cobi.bike/devkit/js/cobi-style.js"></script>
```


## UI Components

Series of examples that tell you how you can use COBI UI Components:


### Typography

Use headings and paragraphs to title and describe sections of your app.
``` html
<h1>COBI Style framework!</h1>
<h2>COBI Style framework!</h2>
<h3>COBI Style framework!</h3>
<h4>COBI Style framework!</h4>
<h5>COBI Style framework!</h5>
<h6>COBI Style framework!</h6>
```

Wrap elements with .content-padded class to give the content space around the screen.

``` html
<div class="content-padded">
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
</div>
```

When you want to center headline or paragraphs in your view just add `class="text-center"`


### Buttons

Say what the step will be

Regular button style
``` html
<button class="btn">Button text</button>
```
Disabled state
``` html
<button class="btn disabled">Button text</button>
```
Button with icon. You can find full list of icons <a>here</a>
``` html
<button class="btn">Button text<span class="icon icon-right-nav"></span></button>
```
Button with COBI surf blue color
``` html
<button class="btn blue">Button text</button>
```
Button with COBI tarmac color
``` html
<button class="btn tarmac">Button text</button>
```


### Forms

Say what the step will be

``` html
<form class="input-group">
  <div class="input-row">
    <label>Full name</label>
       <input type="date" placeholder="21.02.2017">
  </div>
  <div class="input-row">
    <label>Example</label>
    <input type="email" placeholder="cobistyle@gmail.com">
  </div>
  <div class="input-row">
    <label>Username</label>
    <input type="text" placeholder="cobistyle">
  </div>
</form>
```

### Inputs

Say what the step will be

``` html
<ul class="table-view">
  <li class="table-view-cell">
    <a class="navigate-right" href="settings.html" data-transition="slide-in">Load new page with push</a>
  </li>
  <li class="table-view-cell table-view-cell">
    <a class="navigate-right">Item 2</a>
  </li>
  <li class="table-view-cell">COBI toggle<label class="toggle"><input type="checkbox"><div class="slider round"></div></label></li>
  <li class="table-view-cell">
    <a>Item 1</a>
  </li>
  <li class="table-view-cell table-view-cell">
    <a>Item 2</a>
  </li>
  <li class="table-view-cell">COBI toggle
    <label class="toggle">
    <input type="checkbox" checked>
      <div class="slider round"></div>
    </label>
  </li>
  <li class="table-view-divider">Divider</li>
  <li class="table-view-cell">
    <a class="navigate-right">Item 1</a>
  </li>
  <li class="table-view-divider">Divider</li>
</ul>
```
### Modals

Modals are designed to be fire only from links, use `<a href="#myModalexample" class="btn blue">Open modal</a>` to fire div with `id="myModalexample"`

``` html
<!-- Content of your page -->
<div class="content-padded">
  <a href="#myModalexample" class="btn blue">Open modal</a>
</div>

<!-- Modal Content -->
<div id="myModalexample" class="modal">
  <header class="bar bar-nav">
    <a class="icon icon-close pull-right" href="#myModalexample"></a>
    <h1 class="title">Modal</h1>
  </header>

  <div class="content">
    <p class="content-padded">The contents of my modal go here. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut.</p>
  </div>
</div>
```

### Toggle

Say what the step will be

``` html
<label class="toggle"><input type="checkbox"><div class="slider round"></div></label>
```
