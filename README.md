# Designkit Dropdown

## Install

```bash
npm i designkit-dropdown
```

## Usage

### Basic Menu

```html
<div class="dropdown open">
  <button class="btn btn-default dropdown-toggle" type="button">
    Dropdown Button
  </button>
  <div class="dropdown-menu">
      <a class="dropdown-item" href="#">Action</a>
      <a class="dropdown-item" href="#">Another action</a>
      <a class="dropdown-item" href="#">Something else here</a>
  </div>
</div>
```

### Optional Drop up

```html
<div class="dropup open">
  <button class="btn btn-default dropdown-toggle" type="button">
    Dropup Button
  </button>
  <div class="dropdown-menu">
      <a class="dropdown-item" href="#">Action</a>
      <a class="dropdown-item" href="#">Another action</a>
      <a class="dropdown-item" href="#">Something else here</a>
  </div>
</div>
```

### Optional Dividers

```html
<div class="dropdown open">
  <button class="btn btn-default dropdown-toggle" type="button">
    Dropdown Button
  </button>
  <div class="dropdown-menu">
      <a class="dropdown-item" href="#">Action</a>
      <a class="dropdown-item" href="#">Another action</a>
      <a class="dropdown-item" href="#">Something else here</a>
      <div class="dropdown-divider"></div>
      <a class="dropdown-item" href="#">Settings</a>
  </div>
</div>
```

### Optional Headers

```html
<div class="dropdown open">
  <button class="btn btn-default dropdown-toggle" type="button">
    Dropdown Button
  </button>
  <div class="dropdown-menu">
      <a class="dropdown-item" href="#">Action</a>
      <a class="dropdown-item" href="#">Another action</a>
      <a class="dropdown-item" href="#">Something else here</a>
      <div class="dropdown-divider"></div>
      <h6 class="dropdown-header">Settings</h6>
      <a class="dropdown-item" href="#">Action</a>
      <a class="dropdown-item" href="#">Another action</a>
      <a class="dropdown-item" href="#">Something else here</a>
  </div>
</div>
```

### Optional Menu Title

```html
<div class="dropdown open">
  <button class="btn btn-default dropdown-toggle" type="button">
    Dropdown Button
  </button>
  <div class="dropdown-menu">
      <div class="dropdown-title">
        <h6>Optional Menu Title</h6>
      </div>
      <div class="dropdown-body">
        <a class="dropdown-item" href="#">Action</a>
        <a class="dropdown-item" href="#">Another action</a>
        <a class="dropdown-item" href="#">Something else here</a>
      </div>
  </div>
</div>
```

### Optional Scroll

```html
<div class="dropdown open">
  <button class="btn btn-default dropdown-toggle" type="button">
    Dropdown Button
  </button>
  <div class="dropdown-menu dropdown-menu-scrollable">
    <div class="dropdown-body">
      <h6 class="dropdown-header">Actions</h6>
      <a class="dropdown-item" href="#">Action</a>
      <a class="dropdown-item" href="#">Another action</a>
      <a class="dropdown-item" href="#">Something else here</a>
      <div class="dropdown-divider"></div>
      <h6 class="dropdown-header">Years</h6>
      <a class="dropdown-item"href="#">1998</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1996</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1994</a>
      <a class="dropdown-item"href="#">1998</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1996</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1994</a>
    </div>
  </div>
</div>
```

### Select Menu

```html
<div class="dropdown open">
  <button class="btn btn-default dropdown-toggle" type="button">
    Dropdown Button
  </button>
  <div class="dropdown-menu dropdown-menu-select">
    <a class="dropdown-item" href="#">Action</a>
    <a class="dropdown-item" href="#">Another action</a>
    <a class="dropdown-item" href="#">Something else here</a>
  </div>
</div>
```

### Multi-Select Menu

```html
<div class="dropdown open">
  <button class="btn btn-default dropdown-toggle" type="button">
    Dropdown Button
  </button>
  <div class="dropdown-menu dropdown-multi-select">
    <div class="dropdown-multi-select-item">
      <div class="dropdown-multi-select-checkbox"></div>
      <div>Amazon Web Services‎</div>
    </div>
    <div class="dropdown-multi-select-item">
      <div class="dropdown-multi-select-checkbox"></div>
      <div>Microsoft Azure</div>
    </div>
    <div class="dropdown-multi-select-item">
      <div class="dropdown-multi-select-checkbox"></div>
      <div>Google Cloud Platform 3845398-3487939</div>
    </div>
    <div class="dropdown-multi-select-item disabled">
      <div class="dropdown-multi-select-checkbox"></div>
      <div>Alibaba Cloud</div>
    </div>
  </div>
</div>
```

### Filter Menu

```html
<div class="dropdown open">
  <button class="btn btn-default dropdown-toggle" type="button">
    Dropdown Button
  </button>
  <div class="dropdown-menu dropdown-menu-filter">
    <div class="dropdown-filter">
      <input id="my_input" class="form-control" type="text" name="name" value="" placeholder="Filter">
    </div>
    <div class="dropdown-body">
      <a class="dropdown-item"href="#">1998</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1996</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1994</a>
      <a class="dropdown-item"href="#">1998</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1996</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1994</a>
      <a class="dropdown-item"href="#">1993</a>
      <a class="dropdown-item"href="#">1992</a>
    </div>
  </div>
</div>
```

### Multiple Menu Options

```html
<div class="dropdown open">
  <button class="btn btn-default dropdown-toggle" type="button">
    Dropdown Button
  </button>
  <div class="dropdown-menu dropdown-menu-select dropdown-menu-filter dropdown-menu-scrollable dropdown-menu-left">
    <div class="dropdown-title">
      <h6>Optional Menu Title</h6>
    </div>
    <div class="dropdown-filter">
      <input id="my_input" class="form-control" type="text" name="name" value="" placeholder="Filter">
    </div>
    <div class="dropdown-body">
      <h6 class="dropdown-header">Actions</h6>
      <a class="dropdown-item" href="#">Action</a>
      <a class="dropdown-item" href="#">Another action</a>
      <a class="dropdown-item" href="#">Something else here</a>
      <div class="dropdown-divider"></div>
      <h6 class="dropdown-header">Years</h6>
      <a class="dropdown-item"href="#">1998</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1996</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1994</a>
      <a class="dropdown-item"href="#">1998</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1996</a>
      <a class="dropdown-item"href="#">1997</a>
      <a class="dropdown-item"href="#">1994</a>
    </div>
  </div>
</div>
```

## The CSS

```css
/*
//
// Designkit-Dropdown
// --------------------------------------------------
*/
.dropdown,
.dropup {
  position: relative;
}

.dropdown-toggle::after {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  content: '';
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}

.dropdown-toggle:focus {
  outline: 0;
}

.dropup .dropdown-toggle::after {
  border-top: 0;
  border-bottom: 4px solid;
}

.dropup .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}

.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  display: block;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  font-size: 13px;
  color: #0A83F6;
  text-align: left;
  list-style: none;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid rgba(209, 214, 220, 0.99);
  border-bottom-color: rgba(200, 206, 213, 0.99);
  border-radius: .25rem;
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  opacity: 0;
  -webkit-transform-origin: top;
  transform-origin: top;
  -webkit-transform: scale(1, 0);
  transform: scale(1, 0);
  transition: -webkit-transform 0.2s cubic-bezier(0.175, 0.885, 0.21, 1.175);
  transition: transform 0.2s cubic-bezier(0.175, 0.885, 0.21, 1.175);
  transition: transform 0.2s cubic-bezier(0.175, 0.885, 0.21, 1.175), -webkit-transform 0.2s cubic-bezier(0.175, 0.885, 0.21, 1.175);
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.dropdown-menu > * {
  opacity: 0;
  transition: opacity .4s ease;
}

.dropup .dropdown-menu {
  -webkit-transform-origin: bottom;
  transform-origin: bottom;
}

.dropdown-divider {
  height: 1px;
  margin: .5rem 0;
  overflow: hidden;
  background-color: #e2e5e9;
}

.dropdown-item {
  display: block;
  width: 100%;
  padding: 3px 20px;
  clear: both;
  font-weight: 400;
  color: #0A83F6;
  text-align: inherit;
  text-decoration: none;
  white-space: nowrap;
  background: 0 0;
  border: 0;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.dropdown-item.active {
  font-weight: bold;
  color: #0769c6;
  background-color: transparent;
}

.dropdown-item.disabled {
  cursor: not-allowed;
  background-color: transparent;
  opacity: .6;
}

.dropdown-item:focus, .dropdown-item:hover {
  color: #0769c6;
  text-decoration: none;
  background-color: #f1f1f1;
}

.dropdown-multi-select .dropdown-multi-select-item {
  position: relative;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  padding: 10px 20px;
  clear: both;
  font-weight: 400;
  line-height: 1;
  color: #0A83F6;
  text-align: inherit;
  text-decoration: none;
  white-space: nowrap;
  cursor: pointer;
  background: 0 0;
  -webkit-box-flex: 1;
      -ms-flex: 1 1 auto;
          flex: 1 1 auto;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.dropdown-multi-select .dropdown-multi-select-item:not(:last-child) {
  border-bottom: 1px solid #e2e5e9;
}

.dropdown-multi-select .dropdown-multi-select-item.disabled {
  cursor: not-allowed;
  background-color: transparent;
  opacity: .6;
}

.dropdown-multi-select .dropdown-multi-select-item:not(.disabled).active {
  font-weight: bold;
  color: #0769c6;
  background-color: transparent;
}

.dropdown-multi-select .dropdown-multi-select-item:not(.disabled).active .dropdown-multi-select-checkbox:after {
  border-color: #80C11A;
}

.dropdown-multi-select .dropdown-multi-select-item:not(.disabled).active .dropdown-multi-select-checkbox:before {
  position: absolute;
  top: 4px;
  left: 4px;
  z-index: 1;
  width: 7px;
  height: 6px;
  content: '';
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='7' height='6' viewBox='0 0 7 6'%3E%3Cpath fill='%2380C11A' d='M2.6 6c.3 0 .5-.1.7-.3l3.4-4.3c.1-.2.2-.4.2-.5 0-.3-.1-.5-.3-.7C6.4.1 6.2 0 6 0c-.3 0-.5.1-.7.3L2.5 3.9l-1-1c-.2-.2-.4-.3-.6-.3s-.4.1-.6.3c-.2.1-.3.3-.3.5s.1.5.3.6L2 5.7c.1.2.3.3.6.3z'/%3E%3C/svg%3E");
}

.dropdown-multi-select .dropdown-multi-select-item:not(.disabled).active:focus .dropdown-multi-select-checkbox:after, .dropdown-multi-select .dropdown-multi-select-item:not(.disabled).active:hover .dropdown-multi-select-checkbox:after {
  border-color: #80C11A;
}

.dropdown-multi-select .dropdown-multi-select-item:not(.disabled):focus, .dropdown-multi-select .dropdown-multi-select-item:not(.disabled):hover {
  color: #0769c6;
  text-decoration: none;
  background-color: #f1f1f1;
}

.dropdown-multi-select .dropdown-multi-select-item:not(.disabled):focus .dropdown-multi-select-checkbox:after, .dropdown-multi-select .dropdown-multi-select-item:not(.disabled):hover .dropdown-multi-select-checkbox:after {
  border-color: #7b8895;
}

.dropdown-multi-select .dropdown-multi-select-checkbox {
  position: relative;
  width: 14px;
  height: 14px;
  margin-right: 8px;
}

.dropdown-multi-select .dropdown-multi-select-checkbox:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 14px;
  height: 14px;
  content: "";
  background: #fff;
  border: 2px solid #A2AFBA;
  border-radius: 2px;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}

.open > .dropdown-menu,
.open > .dropdown-menu.dropdown-menu-center {
  display: block;
  opacity: 1;
  -webkit-transform: scale(1, 1);
  transform: scale(1, 1);
}

.open > .dropdown-menu > *,
.open > .dropdown-menu.dropdown-menu-center > * {
  opacity: 1;
}

.open > a {
  outline: 0;
}

.dropdown-title {
  padding: 5px 10px 11px;
  margin: 0 0 3px 0;
  border-bottom: 1px solid #e2e5e9;
  box-shadow: inset 0 -2px 0 #F4F5F7;
}

.dropdown-title h6 {
  padding: 0;
  margin: 0;
  font-family: "Helvetica Neue", "Helvetica", "Roboto", "Arial", sans-serif;
  font-size: 13px;
  font-weight: bold;
  color: #57626C;
}

.dropdown-header {
  display: block;
  padding: 3px 20px;
  margin: 0 0 3px 0;
  font-family: "Helvetica Neue", "Helvetica", "Roboto", "Arial", sans-serif;
  font-size: 12px;
  color: #76899A;
  white-space: nowrap;
}

.dropdown-menu.dropdown-menu-right {
  right: 0;
  left: auto;
}

.dropdown-menu.dropdown-menu-left {
  right: auto;
  left: 0;
}

.dropdown-menu.dropdown-menu-select .dropdown-item {
  position: relative;
  padding-left: 25px;
}

.dropdown-menu.dropdown-menu-select .dropdown-item.active {
  background-color: transparent;
}

.dropdown-menu.dropdown-menu-select .dropdown-item:before {
  position: absolute;
  top: 6px;
  left: 8px;
  z-index: 1;
  width: 12px;
  height: 12px;
  content: '';
  background-color: transparent;
  background-image: none;
  background-repeat: no-repeat;
  background-position: 0 1px;
  background-size: 11px;
}

.dropdown-menu.dropdown-menu-select .dropdown-item:hover:before {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 10 10'%3E%3Cpath fill='%230769c6' fill-rule='evenodd' d='M9.942%201.1L8.622.056C8.58.02%208.527%200%208.472%200c-.055%200-.11.022-.15.06L3.52%206.23S1.63%204.413%201.58%204.36c-.053-.052-.123-.14-.23-.14-.105%200-.153.074-.208.13L.096%205.45c-.02.02-.03.033-.048.05-.03.04-.047.087-.048.136%200%20.054.02.097.048.138l.068.062s3.35%203.217%203.403%203.272c.056.056.122.125.22.125.097%200%20.176-.103.222-.15l5.988-7.69c.03-.042.048-.09.05-.14%200-.058-.02-.112-.056-.155'/%3E%3C/svg%3E");
}

.dropdown-menu.dropdown-menu-select .dropdown-item.active:before, .dropdown-menu.dropdown-menu-select .dropdown-item.active:hover:before {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 10 10'%3E%3Cpath fill='%230769c6' fill-rule='evenodd' d='M9.942%201.1L8.622.056C8.58.02%208.527%200%208.472%200c-.055%200-.11.022-.15.06L3.52%206.23S1.63%204.413%201.58%204.36c-.053-.052-.123-.14-.23-.14-.105%200-.153.074-.208.13L.096%205.45c-.02.02-.03.033-.048.05-.03.04-.047.087-.048.136%200%20.054.02.097.048.138l.068.062s3.35%203.217%203.403%203.272c.056.056.122.125.22.125.097%200%20.176-.103.222-.15l5.988-7.69c.03-.042.048-.09.05-.14%200-.058-.02-.112-.056-.155'/%3E%3C/svg%3E");
}

.dropdown-menu.dropdown-menu-select .dropdown-item.disabled.active:before {
  color: #ccc;
}

.dropdown-menu.dropdown-menu-select .dropdown-item.disable-select:before {
  display: none;
}

.dropdown-menu.dropdown-menu-center {
  -webkit-transform-origin: top center;
  transform-origin: top center;
  -webkit-transform: scale(0);
  transform: scale(0);
  transition: all 300ms cubic-bezier(0.3, 0, 0, 1.3);
}

.dropdown-menu.dropdown-menu-scrollable .dropdown-body {
  height: auto;
  max-height: 200px;
  padding: 5px 0 0 0;
  margin: 0 0 -5px 0;
  overflow-x: hidden;
  overflow-y: auto;
}

.dropdown-menu.dropdown-menu-filter .dropdown-filter {
  position: relative;
  padding: 5px 10px 8px 10px;
  border-bottom: 1px solid #e2e5e9;
}

.dropdown-menu.dropdown-menu-filter .dropdown-filter input[type="text"] {
  width: 250px;
}
```

## Author

Jason Melgoza

## License

MIT
