# Box

The Box object is simply boxes off content.

## Dependencies

The Box object depends on three other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.functions](https://github.com/treeframework/tools.functions)
* [trump.clearfix](https://github.com/treeframework/trump.clearfix)

If you install the `box` object using Bower or npm, you will get these 
dependencies at the same time. If not using Bower or npm, please be sure to 
install and `@import` these dependencies in the  relevant way.

## Installation

You can install the `box` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-box --save
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "bower_components/tree-box/object.box";
```

### Install using npm:

```sh
$ npm install tree-box --save
```

### Install via file download

The least recommended option for installation is to simply download
`_object.box.scss` into your project and `@import` it into your project in its
Objects layer.

## Usage

Basic usage of the Box object uses the required classes:

```html
<div class="o-box">...</div>
```

## Options

Other, optional classes can supplement the required base classes:

* `.o-box--flush`: remove all padding from boxes.
* `.o-box--[tiny|small|large|huge]`: alter the padding on boxes.

For example:

```html
<div class="o-box  o-box--large">...</div>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
