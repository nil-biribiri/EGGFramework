# EGGFramework

[![CI Status](http://img.shields.io/travis/Suchon Dumnin/EGGFramework.svg?style=flat)](https://travis-ci.org/Suchon Dumnin/EGGFramework)
[![Version](https://img.shields.io/cocoapods/v/EGGFramework.svg?style=flat)](http://cocoapods.org/pods/EGGFramework)
[![License](https://img.shields.io/cocoapods/l/EGGFramework.svg?style=flat)](http://cocoapods.org/pods/EGGFramework)
[![Platform](https://img.shields.io/cocoapods/p/EGGFramework.svg?style=flat)](http://cocoapods.org/pods/EGGFramework)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

EGGFramework is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "EGGFramework"
```

## Usage
To run the example project, clone the repo, and run `pod install` from the Example directory first.

```ruby
import EGGFramework
```

**Validation Email**
```swift
let result = Validator.sharedInstance.isEmail("email@domain.com")
```

**Validation Mobile**
```swift
let result = Validator.sharedInstance.isMobile("0850099664")
```

**Validation Thai ID**
```swift
let result = Validator.sharedInstance.isThaiID("1040853260638")
```

## Author

Suchon Dumnin, mrdumnin@gmail.com

## License

EGGFramework is available under the MIT license. See the LICENSE file for more info.
