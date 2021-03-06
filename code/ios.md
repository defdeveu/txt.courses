# iOS

## About the workshop

Our iOS workshop aims to provide an insight into every aspect of secure mobile application development. In order to cover everything a developer needs to commit and publish secure code through the App Store, the agenda is built from the ground up and has been designed to provide practical exercises throughout the entire training.

After a short introduction, we take a look at the overall Apple/iOS philosophy, the OS security features and their implications on the daily life of a developer. We take a look at typical issues in iOS applications \(many of those result in immediate rejection from App Store upload\), how problematic challenges can be tackled and how typical pitfalls can be avoided. Throughout the course, a plethora of in-house demo applications are provided to highlight issues.

The '[Mobile security baseline](../lib/mobile-baseline.md)' module can be taken as general preps to this course. While the '[Mobile testing automation](../test/mobile-testing-automation.md)' module greatly extends the coverage of the practical field. 

The training has been tested and used successfully with several mobile heavy developer companies.

### Properties

title: **iOS security design and secure coding**

**audience**: iOS developers, architects and testers, security engineers, security champions

**duration**: 1 XL day \(7hrs education time\), or 2 days combined with the '[Mobile security baseline](../lib/mobile-baseline.md)' module

developed by: [Zsombor Kovács](../trainers/zsombor-kovacs.md)

### Prerequisites

We assume that the developers attending the iOS secdev course:

* Are familiar with with the mobile apps development process and technologies;
* Have a suitable IDE installed on their MacBook
  * with Xcode and the latest SDK installed,
  * and a valid developer profile \(a free limited 7-day developer licence is sufficient\);
* Ideally bring an iOS device.

### Related courses

* [Mobile security baseline](../lib/mobile-baseline.md)
* [Mobile testing automation](../test/mobile-testing-automation.md)
* [Android security design and secure coding](android.md)

## Agenda

**Intro**

* 'Into the middle of things' demo: "Bugs and flaws in your app help bad guys"
* Security mechanisms in iOS
* Application signing in iOS

**Application design in iOS**

* Common design patterns
* Architecture of an iOS app
* Secure API design
* Designing a reasonable communication flow

**Secure data storage**

* iOS storage encryption
* Protection classes, storage formats and their security implications
* Data storage and backups \(iTunes, iCloud, 3rd party applications\)
* Logging
* Hands-on: \(in\)secure storage in applications

**Network security**

* App Transport Security
* Certificate pinning
* Hands-on: certificate pinning implementation and potential bypass methods

**Inter-process communication**

* Custom protocol handlers
* Hands-on: attacking and securing an insecure custom protocol handler

#### Secure crypto implementation

* Crypto implementation in iOS. CCCrypt and wrappers
* Designing a secure crypto engine, what to do and what to avoid. The dangers of home grown ciphers 
* Hands-on: insecure crypto examples, the extraction of a hard wired encryption key

#### Environmental interaction in iOS

* The iOS environment philosophy, the evolution of the 'iOS cage'
* Expected and unexpected environmental intervetions throughout the application lifecycle
* Hands-on: screen masking, side channel data leakage, WebView issues 

#### Secure implementation in

* Swift
* Objective C 
* Non-native/hybrid app development: Flutter, React, etc.

**Tampering detection**

* Jailbreaking, implications of running on a jailbroken device
* Dynamic hooking and method swizzling
* Hands-on: bypassing jailbreak detection in several ways

## Trainers

* Lead trainer:
  * [Zsombor Kovács](../trainers/zsombor-kovacs.md)
* Co-trainer:
  * ​[Glenn ten Cate](https://c.defdev.eu/trainers/glenn-ten-cate)

