# bulma-fab-button

A Bulma's extension for FABs (Floating Action Buttons).

## Quick install

``` bash
# NPM
npm i bulma-fab-button

# Yarn
yarn add bulma-fab-button
```

## Import

You can import the .css or .sass file into your project after importing Bulma:

``` scss
@import '../node_modules/bulma-fab-button/src/bulma-fab-button.sass';
```

## Usage

Basic usage:

``` html
<a href="#" class="button is-floating is-primary">
  <i class="fas fa-shopping-cart"></i>
</a>
```

You can use colors like any other Bulma component:

``` html
<a href="#" class="button is-floating is-primary">
  <i class="fas fa-shopping-cart"></i>
</a>

<a href="#" class="button is-floating is-dark">
  <i class="fas fa-shopping-cart"></i>
</a>

<a href="#" class="button is-floating is-success">
  <i class="fas fa-shopping-cart"></i>
</a>

<a href="#" class="button is-floating is-info">
  <i class="fas fa-shopping-cart"></i>
</a>

<a href="#" class="button is-floating is-danger">
  <i class="fas fa-shopping-cart"></i>
</a>

<a href="#" class="button is-floating is-light">
  <i class="fas fa-shopping-cart"></i>
</a>
```

Also size modifiers (`.is-large`, `.is-small`):

``` html
<a href="#" class="button is-floating is-small">
  <i class="fas fa-shopping-cart"></i>
</a>

<a href="#" class="button is-floating is-large">
  <i class="fas fa-shopping-cart"></i>
</a>
```

And position modifiers (`.is-left`, `.is-centered`, `.is-right`):

``` html
<a href="#" class="button is-floating is-left">
  <i class="fas fa-shopping-cart"></i>
</a>

<a href="#" class="button is-floating is-centered">
  <i class="fas fa-shopping-cart"></i>
</a>

<a href="#" class="button is-floating is-right">
  <i class="fas fa-shopping-cart"></i>
</a>
```

## Customize

> For options available, take a look at the `_initial-variables.sass` file.

``` scss
// Customize
$fab-circle-size: 4rem; // default: 3.75rem
$fab-h-space: 1rem; // default: 1.25rem
$fab-v-space: 1rem; // default: 1.25rem

// Then import
@import '../node_modules/bulma-fab-button/src/bulma-fab-button.sass'
```

## Copyright and license

Code copyright 2020 José Olórtegui. Code released under [the MIT license](https://github.com/olrtg/bulma-fab-button/blob/master/LICENSE).
