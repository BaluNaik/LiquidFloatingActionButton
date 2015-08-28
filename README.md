# LiquidFloatingActionButton

[![CI Status](http://img.shields.io/travis/yoavlt/LiquidFloatingActionButton.svg?style=flat)](https://travis-ci.org/yoavlt/LiquidFloatingActionButton)
[![Version](https://img.shields.io/cocoapods/v/LiquidFloatingActionButton.svg?style=flat)](http://cocoapods.org/pods/LiquidFloatingActionButton)
[![License](https://img.shields.io/cocoapods/l/LiquidFloatingActionButton.svg?style=flat)](http://cocoapods.org/pods/LiquidFloatingActionButton)
[![Platform](https://img.shields.io/cocoapods/p/LiquidFloatingActionButton.svg?style=flat)](http://cocoapods.org/pods/LiquidFloatingActionButton)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)]
(https://github.com/Carthage/Carthage)

LiquidFloatingActionButton is floating action button component of [material design](https://www.google.com/design/spec/material-design/introduction.html) in liquid state, inspired by [Material In a Liquid State](http://www.materialup.com/posts/material-in-a-liquid-state).

## Features
- [x] liquid animation
- [x] easily custoizable
- [x] Objective-C complatible

## Usage

You just need implement `LiquidFloatingActionButtonDataSource` and `LiquidFloatingActionButtonDelegate` similar to well-known UIKit design.

### LiquidFloatingActionButtonDataSource
* func numberOfCells(liquidFloatingActionButton: LiquidFloatingActionButton) -> Int
* func cellForIndex(index: Int) -> LiquidFloatingCell

### LiquidFloatingActionButtonDelegate
* optional func liquidFloatingActionButton(liquidFloatingActionButton: LiquidFloatingActionButton, didSelectItemAtIndex index: Int)

## Installation

LiquidFloatingActionButton is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "LiquidFloatingActionButton"
```
or, if you use [Carthage](https://github.com/Carthage/Carthage), add the following line to your `Carthage` file.

```
github "yoavlt/LiquidLoader"
```

## License

LiquidFloatingActionButton is available under the MIT license. See the LICENSE file for more info.
