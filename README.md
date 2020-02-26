# WXNavigationBar
WeChat NavigationBar

![](Assets/navigationbar01.gif)

# Requirements

- iOS 12.0+
- Xcode 11.0+
- Swift 5.0+

# Installation

WXNavigationBar is available through CocoaPods. To install it, simply add the following line to your Podfile:

```
pod 'WXNavigationBar'
```

# Usage

See the demo.

```swift
import WXNavigationBar

let controller = ViewController()
let nav = WXNavigationController(rootViewController: controller)
```

### Configuration

In your AppDelegate

```swift

import WXNavigationBar

WXNavigationBar.NavBar.backImage = UIImage(named: "xxx")
WXNavigationBar.NavBar.isShadowImageHidden = false

```


Scenario 1
---

Push to solid colored navigation bar


Scenario 2
--

Push to transparent navigation bar


Scenario 3
--

Push to system navigation bar
