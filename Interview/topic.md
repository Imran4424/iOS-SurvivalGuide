# iOS Senior / Lead Engineer Interview Preparation Roadmap

> Use the checkboxes to track progress. Topics marked ⭐ deserve extra focus based on your experience (Combine and async/await at 6 months each).

---

## Part 1: Core Technical

### 1. Swift Language
- [ ] Value vs reference types, copy-on-write
- [ ] Optionals and unwrapping patterns
- [ ] Properties, initialization, enums
- [ ] Closures, capture lists, escaping vs non-escaping
- [ ] ARC and memory management
- [ ] Protocols and protocol-oriented programming
- [ ] Generics, `some` vs `any`, type erasure
- [ ] Error handling, typed throws
- [ ] Collections and strings
- [ ] Access control and modules
- [ ] Method dispatch and performance
- [ ] Property wrappers, result builders, macros, key paths
- [ ] Noncopyable types and ownership (`consume`, `borrowing`, `consuming`)

### 2. UIKit
- [ ] View controller lifecycle
- [ ] Auto Layout (constraints, priorities, intrinsic content size)
- [ ] UITableView / UICollectionView (diffable data sources, compositional layout)
- [ ] Responder chain and event handling
- [ ] Custom views and drawing
- [ ] Navigation patterns and coordinators
- [ ] UIKit ↔ SwiftUI interop (`UIHostingController`, `UIViewRepresentable`)

### 3. SwiftUI
- [ ] View identity, lifetime, and dependencies
- [ ] State management (`@State`, `@Binding`, `@Environment`, `@Bindable`)
- [ ] Observation framework (`@Observable`) vs `ObservableObject`
- [ ] View update performance
- [ ] Layout system and custom `Layout`
- [ ] Navigation (`NavigationStack`, `NavigationSplitView`, programmatic navigation)
- [ ] Animations and transitions
- [ ] Custom view modifiers and preference keys

### 4. SwiftData
- [ ] `@Model`, attributes, relationships
- [ ] `ModelContainer` and `ModelContext`
- [ ] `@Query`, `#Predicate`, `FetchDescriptor`
- [ ] Schema versioning and migrations
- [ ] Background work with `ModelActor`
- [ ] SwiftData vs Core Data trade-offs

### 5. Combine ⭐
- [ ] Publishers, subscribers, subscriptions
- [ ] Operators (map, flatMap, combineLatest, merge, debounce, etc.)
- [ ] Subjects (`PassthroughSubject`, `CurrentValueSubject`)
- [ ] Schedulers and threading
- [ ] Backpressure and demand
- [ ] Memory management with `AnyCancellable`
- [ ] Combine vs async/await

### 6. Async/Await ⭐
- [ ] Async functions and suspension points
- [ ] `async let` and task groups
- [ ] Cancellation
- [ ] Continuations (bridging callback APIs)
- [ ] Error propagation in async code

### 7. Swift Concurrency (Deep Dive) ⭐
- [ ] Actors and actor isolation
- [ ] `@MainActor` and global actors
- [ ] `Sendable` and data-race safety
- [ ] Actor reentrancy
- [ ] `Task`, `Task.detached`, task priorities, task-local values
- [ ] `AsyncSequence` and `AsyncStream`
- [ ] Swift 6 language mode and strict concurrency migration
- [ ] Approachable concurrency settings (default main-actor isolation)

---

## Part 2: Senior & Lead Level

### 8. App Architecture
- [ ] MVC, MVVM, VIPER, Clean Architecture, TCA
- [ ] Coordinators / routers
- [ ] Dependency injection
- [ ] Modularization with Swift Package Manager

### 9. Mobile System Design
- [ ] Designing a feed, chat, or offline-first app
- [ ] Caching strategies
- [ ] Pagination and sync
- [ ] Image loading pipeline
- [ ] API contract design

### 10. Performance & Debugging
- [ ] Instruments (Time Profiler, Allocations, Leaks, Hangs)
- [ ] Retain cycles and memory graph debugger
- [ ] App launch time optimization
- [ ] Scroll and rendering performance
- [ ] Battery and network efficiency

### 11. Testing
- [ ] Unit testing with XCTest and Swift Testing
- [ ] UI testing
- [ ] Mocks, stubs, protocols for testability
- [ ] Snapshot testing
- [ ] Testing async and concurrent code

### 12. Networking & Security
- [ ] URLSession, Codable
- [ ] Error handling and retry strategies
- [ ] Keychain and data protection
- [ ] Certificate pinning
- [ ] OAuth and token refresh flows

### 13. Problem Solving / DSA (in Swift)
- [ ] Arrays and strings
- [ ] Hash maps and sets
- [ ] Linked lists, stacks, queues
- [ ] Trees and graphs
- [ ] Recursion and dynamic programming
- [ ] Sorting and searching
- [ ] Big-O analysis

### 14. iOS Platform Knowledge
- [ ] App lifecycle and scenes
- [ ] Background tasks
- [ ] Push notifications
- [ ] Deep links and universal links
- [ ] Accessibility
- [ ] Localization
- [ ] App Store submission and review

### 15. CI/CD & Tooling
- [ ] Build settings, schemes, configurations
- [ ] Fastlane, Xcode Cloud
- [ ] Code signing and provisioning
- [ ] Feature flags and phased rollouts

### 16. Leadership & Behavioral
- [ ] Mentoring and growing engineers
- [ ] Code review culture
- [ ] Technical decision-making and RFCs
- [ ] Handling disagreements
- [ ] Estimation and planning
- [ ] STAR-format stories from past projects