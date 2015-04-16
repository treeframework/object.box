# Box

The Box object is simply boxes off content.

## Dependencies

The Box object depends on three other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.functions](https://github.com/treeframework/tools.functions)
* [trump.clearfix](https://github.com/treeframework/trump.clearfix)

If you install the Box object using Bower, you will get these dependencies at
the same time. If not using bower, please be sure to install and `@import` these
dependencies in the  relevant way.

## Installation

The recommended installation method is Bower, but you can install the Box module
via npm,  Git Submodule, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-box --save
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "bower_componenets/tree-box/object.box";
```

### Install using npm:

```sh
$ npm install tree-box --save
```

### Install as a Git Submodule:

```sh
$ git submodule add git@github.com:treeframework/object.box.git
```

Once installed, `@import` into your project in its Objects layer:

```scss
@import "object.box/object.box";
```

### Install via file download

The least recommended option for installation is to simply download
`_object.box.scss` into your project and `@import` it into your project in its
Objects layer.

## Usage

Basic usage of the Box object uses the required classes:

```html
<div class="o-box">
    Foo Bar Baz
</div>
```

## Options

Other, optional classes can supplement the required base classes:

* `.o-box--flush`: remove all padding from boxes.
* `.o-box--[tiny|small|large|huge]`: alter the padding on boxes.

For example:

```html
<div class="o-box  o-box--large">
    Foo Bar Baz
</div>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
