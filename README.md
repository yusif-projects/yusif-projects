<div align="center">

```
    ┌───────────────────────────────────────────────────────────────────┐
    │                                                                   │
    │    ┌──────────────────────────────────────────────────────────┐   │
    │    │  ◉                                                       │   │
    │    │                                                          │   │
    │    │                    YUSIF ALIYEV                          │   │
    │    │              iOS Software Architect                      │   │
    │    │                   Baku  🇦🇿                               │   │
    │    │                                                          │   │
    │    │          ┌────────────────────────────┐                  │   │
    │    │          │      VIEW PROFILE ▶        │                  │   │
    │    │          └────────────────────────────┘                  │   │
    │    │                                                          │   │
    │    └──────────────────────────────────────────────────────────┘   │
    │                              ───                                  │
    └───────────────────────────────────────────────────────────────────┘
```

<br>

![Swift](https://img.shields.io/badge/Swift-5.9-F05138?style=flat-square&logo=swift&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-17+-000000?style=flat-square&logo=apple&logoColor=white)
![UIKit](https://img.shields.io/badge/UIKit-Expert-007AFF?style=flat-square&logo=apple&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-15-147EFB?style=flat-square&logo=xcode&logoColor=white)

</div>

<br>

## 📲 `AppDelegate.swift`

```swift
import UIKit

@main
final class YusifAliyev: UIResponder, UIApplicationDelegate {
    
    let location = CLLocationCoordinate2D(latitude: 40.4093, longitude: 49.8671) // Baku 🏔️
    let experience: TimeInterval = .years(5)
    let preferredFramework: UIFramework = .UIKit  // and proud of it
    
    func application(_ application: UIApplication, 
                     didFinishLaunchingWithOptions launchOptions: [UIApplication.LaunchOptionsKey: Any]?) -> Bool {
        
        setupArchitecture(.clean)
        configurePatterns([.mvvm, .coordinator, .repository])
        startCoding()
        
        return true
    }
    
    var currentRole: String {
        """
        Leading mobile development for a popular app in Azerbaijan
        """
    }
}
```

<br>

## 🛠️ `Podfile`

```ruby
platform :ios, '17.0'
use_frameworks!

target 'YusifSkillset' do
  
  # Core
  pod 'Swift',           '~> 5.9'      # ████████████████ mastered
  pod 'Objective-C',     '~> 2.0'      # ████████████░░░░ proficient
  
  # UI Frameworks
  pod 'UIKit',           '~> latest'   # ████████████████ daily driver
  pod 'SwiftUI',         '~> 5.0'      # ████░░░░░░░░░░░░ when needed
  
  # Architecture
  pod 'CleanArchitecture'
  pod 'MVVM-C'
  pod 'Coordinator'
  
  # Tools
  pod 'Instruments'                     # memory leaks fear me
  pod 'Fastlane'                        # automate all the things
  pod 'XCTest'                          # because shipping bugs is not a feature
  
end
```

<br>

## 📁 `Info.plist`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<plist version="1.0">
<dict>
    <key>CFBundleName</key>
    <string>Pet Projects</string>
    
    <key>CFBundleDescription</key>
    <string>Experiments, weekend hacks, and UI playgrounds</string>
    
    <key>NSHumanReadableWarning</key>
    <string>⚠️ Built for fun, not for production. Proceed with curiosity.</string>
    
    <key>UIRequiredDeviceCapabilities</key>
    <array>
        <string>creativity</string>
        <string>caffeine-tolerance</string>
        <string>late-night-debugging</string>
    </array>
    
    <key>LSApplicationQueriesSchemes</key>
    <array>
        <string>learning</string>
        <string>experimenting</string>
        <string>breaking-things-to-understand-them</string>
    </array>
</dict>
</plist>
```

<br>

## 🚀 `AppStore.connect`

<div align="center">

<a href="https://apps.apple.com/az/app/id1602500636">
<img src="https://img.shields.io/badge/Download_on_the-App_Store-000000?style=for-the-badge&logo=app-store&logoColor=white" alt="App Store" height="50"/>
</a>

<br>
<sub>🇦🇿 Popular app in Azerbaijan · Leading the iOS development</sub>

</div>

<br>

## 💭 `// MARK: - Philosophy`

```swift
/// Why UIKit over SwiftUI?
///
/// Some say it's old school.
/// I say it's battle-tested, pixel-perfect, and
/// gives me the control I need.
///
/// SwiftUI is the future. UIKit is the present that works.
/// I speak both, but UIKit is my native tongue.
```

<br>

---

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│   Build Succeeded                                         ✓     │
│   ─────────────────────────────────────────────────────────     │
│   No issues · Ready to explore                                  │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

<br>

<sub>*Crafted with `UIView` and way too much ☕ in Baku*</sub>

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com)

</div>
