# Ratio

The `ratio` object simply causes media embeds – such as videos, slideshows, or
even images to retain a specific aspect ratio.

## Dependencies

The `ratio` object depends on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the `ratio` object using Bower, you will get these dependencies at
the same time. If not using Bower, please be sure to install and `@import` these
dependencies in the relevant way.

## Installation

You can install `ratio` object via npm, Git Submodule, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-ratio --save
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "bower_components/tree-ratio/object.ratio";
```

### Install using npm:

```sh
$ npm install tree-ratio --save
```

### Install as a Git Submodule:

```sh
$ git submodule add git@github.com:treeframework/object.ratio.git
```

Once installed, `@import` into your project in its Object layer:

```scss
@import "trump.ratio/trump.ratio";
```

### Install via file download

The least recommended option dor installation is to simply download
`_object.ratio.scss` into your project and `@import` it into your project in its
Objects layer.

## Usage

Basic usage of the `ratio` object uses the required classes:

```html
<div class="ratio">
    <iframe class="ratio__item" src="..."></iframe>
</div>
```

## Options

Other, optional classes can supplement the required base classes:

* `.ratio--[3by1|2by1|16by9|4by3]`: alter aspect ratio.

For example:

```html
<figure class="ratio  ratio--4by3">
    <img class="ratio__item" src="path/to/image.jpg" alt="">
</figure>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.

* **[SUIT CSS link utilities](https://github.com/suitcss/utils-link/)** SUIT
CSS is a reliable and testable styling methodology for component-based UI
development.