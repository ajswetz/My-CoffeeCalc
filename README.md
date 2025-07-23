# My CoffeeCalc

<!-- App Icon -->
<img src="assets/CoffeeCalcIcon-500x500.png" alt="My CoffeeCalc App Icon" width="120" height="120" />

<!-- App Store Badge -->
<a href="https://apps.apple.com/us/app/my-coffeecalc/id6747992533?itscg=30200&itsct=apps_box_badge&mttnsubad=6747992533" style="display: inline-block;">
    <img src="https://toolbox.marketingtools.apple.com/api/v2/badges/download-on-the-app-store/black/en-us?releaseDate=1753056000" alt="Download on the App Store" style="width: 145px; height: 48px; vertical-align: middle; object-fit: contain;" />
</a>
    

# iOS App Development Overview

## Problem Statement
Coffee brewing newcomers struggle with understanding coffee-to-water ratios and translating abstract ratios into precise brewing measurements. This app solves both challenges by providing curated, community-accepted brewing ratios with smart defaults, and a streamlined calculator that converts ratios into exact coffee and water amounts. Educational articles help users understand the science behind optimal brewing ratios.

## Technical Architecture

The My CoffeeCalc iOS application is built entirely in **Swift**, leveraging Apple's modern **SwiftUI** framework for declarative UI development. The app demonstrates proficiency with contemporary iOS development patterns and Apple's latest tools and frameworks.

### Key Technologies & Frameworks

- **SwiftUI** - Primary UI framework utilizing declarative syntax
- **Swift Markdown UI** - Third-party package integration for rendering Markdown content in iOS-optimized format ([gonzalezreal/swift-markdown-ui](https://github.com/gonzalezreal/swift-markdown-ui))
- **WidgetKit** - watchOS complications implementation
- **TestFlight** - Beta distribution and testing platform

## Multi-Platform Implementation

The project showcases cross-platform development skills with three distinct targets:
- **iOS App** - Primary mobile application
- **watchOS App** - Companion Apple Watch application
- **watchOS Complication** - Watch Face complication using WidgetKit

## Swift & SwiftUI Features Implemented

The codebase demonstrates advanced Swift and SwiftUI concepts including:

**Core Swift Patterns:**
- Structs, enums, and classes for proper data modeling
- Extensions for code organization and reusability
- JSONDecoder() for structured data parsing

**SwiftUI State Management:**
- `@Observable` for modern data observation
- `@State` and `@FocusState` for local view state
- `@Environment` for dependency injection
- `@AppStorage` for persistent user preferences

**Advanced UI Components:**
- `NavigationSplitView` for adaptive navigation
- `TabView` for organized content structure
- `@ViewBuilder` for flexible view composition
- Custom animations and sheet presentations

## Development Workflow & CI/CD

**Continuous Integration:**
- **Xcode Cloud** integration with GitHub repository
- Automated build and test processes
- Streamlined deployment pipeline

**Quality Assurance:**
- **TestFlight** distribution for both internal dev testing and external beta user feedback
- Multi-stage testing process ensuring quality releases

## Architecture Highlights

The application demonstrates modern iOS development best practices through clean separation of concerns, efficient state management, and thoughtful integration of both first-party and third-party frameworks. The multi-platform approach showcases understanding of Apple's ecosystem and the ability to create cohesive experiences across devices.
