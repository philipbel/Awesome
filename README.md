# Awesome

[![Version](https://img.shields.io/cocoapods/v/FASwift.svg?style=flat)](http://cocoapods.org/pods/FASwift)
[![License](https://img.shields.io/cocoapods/l/FASwift.svg?style=flat)](http://cocoapods.org/pods/FASwift)
[![Platform](https://img.shields.io/cocoapods/p/FASwift.svg?style=flat)](http://cocoapods.org/pods/FASwift)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Installation

Awesome is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'Awesome'
```

for Cocoapods just do:

```ruby
github "manGoweb/Awesome"
```

## Usage

All icons are available through autogenerated enums like this:

```swift
let image = Awesome.solid.handScissors.asImage(size: 40.0)
// or
let image = Awesome.brand.apple.asImage(size: CGSize(width: 40, height: 40), color: .red, backgroundColor: .blue)
// or
let attributedText = Awesome.regular.terminal.asAttributedText(fontSize: 17, color: .red, backgroundColor: .blue)
```

## Author

Ondrej Rafaj , development@mangoweb.cz

## License

Awesome is available under the MIT license. See the LICENSE file for more info. All fonts are property of Font Awesome!
