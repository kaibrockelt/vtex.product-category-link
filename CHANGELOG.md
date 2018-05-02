# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

* Add the Product Image component which is responsible to display a main image and a list of thumbnail images of a Product.

### Changed

* Use the _Link_ Component from _render_ module.
* Use _Price_, _ProductName_ and _DiscountBadge_ from [npm-storecomponents](https://github.com/vtex-apps/npm-storecomponents).

### Fixed

* Fix components style that was overwritten by the _Link_ Component.

## [0.2.1] - 2018-04-27

### Fixed

* Fix summary style on mobile screens with the shelf component

## [0.2.0] - 2018-04-26

### Added

* Add the component dynamic schema props to hide the `showButtonOnHover` property if `hideBuyButton` is activated.

### Fixed

* Does not show list price when it is equal to selling price
* Always shows the buy button on mobile if `showButtonOnHover` is activated (smartphones and tablets)
* Add default schema props to the _Product Summary_

## [0.1.0] - 2018-04-24

### Added

* **Component** Create the VTEX Store Component _Product Summary_