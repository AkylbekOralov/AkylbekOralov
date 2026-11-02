## Akylbek Oralov

iOS Engineer | Swift, UIKit, SwiftUI

iOS engineer focused on scalable mobile architecture and performance optimization.
Experienced in working with modular codebases, improving build pipelines, and shipping production apps, including my own app [NuetShark](https://akylbekoralov.github.io/nuetshark-web/) on the App Store.

---

## Experience

### Junior Mobile Engineer (iOS), Snoonu

*Mar 2026 – Present*

* Mobile Platform team, 170+ merged PRs
* Cut Firebase build size by 25% (400MB → 300MB)
* Removed 6,000+ lines of dead code and ~30 outdated feature flags
* Removed duplicate config fetching on app launch
* Migrated all modules to String Catalogs (`.xcstrings`)
* Set up SwiftLint, Periphery and dependency checks in CI
* Built a Datadog iOS performance dashboard: crash-free rate, freezes, slow screens, startup, network and memory
* Integrated [DebugSwift](https://github.com/DebugSwift/DebugSwift) for in-app memory monitoring
* Migrated 4 modules to Swift 6 and moved shared singletons to FactoryKit DI
* Added iPhone Duo (foldable) support for bottom sheets
* Fixed a cross-account order data leak on logout

### iOS Engineer Intern, Snoonu

*Sep 2025 – Feb 2026*

* Mobile Platform team, 190+ merged PRs
* Migrated 36 modules to type-safe string and image resources using Tuist
* Implemented multi-currency support for expansion to Kuwait, Oman and Bahrain
* Developed reusable price formatting and date/time services for the Kuwait, Oman and Bahrain markets
* Added multi-timezone support and documented the shared formatting services for the team
* Unified icons across modules following the design system
* Fixed launch-blocking bugs for the Kuwait release, including address search and the country picker

### iOS Developer (Contract), Rabitabank

*May 2025 – Jun 2025*

Built features for Rabita Junior, Rabitabank's mobile banking app for children.

* Built a character-switching system that keeps the selected character in sync across every screen
* Added PIN change to the Settings module
* Turned backend error responses into clear, custom alerts for the user
* Localized the whole app, with the UI updating instantly on language change
* Fixed the statistics chart animation so it replays correctly when the month or year changes

---

## Projects

### [NuetShark](https://akylbekoralov.github.io/nuetshark-web/)

**NUET prep app for iPhone & iPad** · [Website](https://akylbekoralov.github.io/nuetshark-web/) · [App Store](https://apps.apple.com/kz/app/nuetshark/id6816238094)

Exam-style Mathematics and Critical Thinking tests for students applying to Nazarbayev University. Designed, built and shipped solo, from development to App Store submission, review and ongoing releases.

**App Store Connect (as of Nov 2026):** 220+ downloads · 1.2K+ impressions · 365 product page views

* Timed exams with a question tracker, auto-saved progress and resume mid-test
* Instant results with per-question timing, correct/incorrect filters and bookmarks
* Weekly streaks and progress stats; properly typeset math with LaTeX
* No ads, no advertising tracking, no third-party analytics

**Built with:** UIKit, SnapKit, VIPER, FactoryKit DI, modular Tuist workspace, Supabase backend, feature flags, light/dark themes

### [AirCheck](https://github.com/AkylbekOralov/AirCheck)

Air quality tracking app using Mapbox and AQI APIs

* Implemented map-based visualization with dynamic markers
* Built networking layer for real-time AQI updates
* Added location-based data fetching and caching
* Integrated WidgetKit for quick access to air quality data

### [ScoreMate](https://github.com/AkylbekOralov/ScoreMate)

Football tracking app built with SwiftUI and MVVM

* Designed state-driven UI architecture using MVVM
* Implemented match state management and score synchronization
* Integrated external API for live data updates
* Supported dark/light mode and dynamic UI updates

---

## Tech Stack

**Core**

* Swift (Swift 6), UIKit, SwiftUI, SnapKit
* Auto Layout, iPhone and iPad support (universal apps, adaptive layouts)

**Architecture**

* MVVM, VIPER, MVC, Clean Architecture, Modular Architecture
* Dependency Injection (FactoryKit)
* Kotlin Multiplatform (KMP) integration

**Concurrency & Networking**

* Swift Concurrency (async/await, actors, Sendable), Combine, GCD
* URLSession, Alamofire, REST

**Apple Frameworks**

* WidgetKit, MapKit, CoreLocation, String Catalogs (.xcstrings)

**Persistence**

* Core Data, SwiftData, UserDefaults, Keychain

**Backend & SDKs**

* Supabase, Firebase, Mapbox

**Analytics & Monitoring**

* Amplitude, Datadog, Adjust

**Testing**

* XCTest, Swift Testing

**Tooling**

* Tuist, Swift Package Manager, Xcode, Git
* App Store Connect, TestFlight, App Store publishing (signing, submission, review, releases)
* GitHub Actions, Fastlane, CI/CD, SwiftLint, Periphery, feature flags

---

## Links

* NuetShark: https://akylbekoralov.github.io/nuetshark-web/
* LinkedIn: https://www.linkedin.com/in/akylbek-oralov
* Email: [oralovv26@gmail.com](mailto:oralovv26@gmail.com)
