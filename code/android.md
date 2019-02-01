---
description: XOX headline
---

# Android

## About the course

### Overview

Our Android training aims to provide an insight into every aspect of secure mobile application development. In order to cover everything a developer needs to commit and publish secure code through the Play Store, the agenda is built from the ground up and has been designed to provide practical exercises throughout the entire training, with a heavy focus on how Android as a development platform offers security features to developers.

After a short introduction, we take a look at the overall Google/Android philosophy, the OS security features and their implications on the daily life of a developer. We take a look at typical issues in Android applications with some now-infamous bugs and exploits from the past, how problematic challenges can be tackled and how typical pitfalls can be avoided. Throughout the course, a plethora of in-house demo applications are provided to highlight issues.

The '[Mobile security baseline](../lib/mobile-baseline.md)' module can be taken as general preps to this course. While the '[Mobile testing automation](../test/mobile-testing-automation.md)' module greatly extends the coverage of the practical field. 

The course has been tested and used successfully with several mobile heavy developer companies.

### Properties

title: **Android security design and secure coding**

**audience**: Android developers, architects and testers, security engineers, security champions

**duration**: 1 XL day \(7hrs education time\), or 2 days combined with the '[Mobile security baseline](../lib/mobile-baseline.md)' module

developed by: [Zsombor Kovács](../trainers/zsombor-kovacs.md)

### Prerequisites

We assume that the developers attending the Android secdev course:

* are familiar with with the mobile apps development process and technologies
* have a suitable IDE installed on their laptop \(labs desktop\)
  * Android Studio installed and configured
  * Genymotion emulator installed and configured

### Related courses

* [Mobile security baseline](../lib/mobile-baseline.md)
* [Mobile testing automation](../test/mobile-testing-automation.md)
* [iOS security design and secure coding](ios.md)

## Agenda

#### Intro

* 'Into the middle of things' demo: "Bugs and flaws in your app help bad guys"
* Security mechanisms in Android

#### Application Design

* Common design patterns
* Architecture of and Android app
* Secure API design
* Designing a reasonable communication flow
* Hands-on: the manifest.xml

#### Secure data storage

* Storage locations, which one to use?
* Different formats \(sqlite, xml, prefs file etc.\) and security implications
* Threats to stored data \(backups, data leak etc.\)
* Logging
* Hands-on: Exploiting weak data storage methods

#### Network security

* Designing and implementing a secure communication flow
* Hands-on: SSL cert pinning implementation and bypass

#### Inter-process communication

* Securing activities
* Securing content providers
* Securing broadcast listeners
* Hands-on: typical IPC issues

#### Secure crypto implementation

* Libraries
* Hands-on: extraction of hard coded crypto material

#### Secure implementation in

* Java
* Kotlin 
* Non-native/hybrid app development: Flutter, React, etc.

#### Tampering detection

* Rooting, implications of running on a rooted device
* Hands-on: dynamic hooking exercise 
* Hands-on: bypassing root detection in several ways

## Trainers

* Lead trainer:
  * [Zsombor Kovács](../trainers/zsombor-kovacs.md)
* Co-trainer:
  * ​[Glenn ten Cate](https://c.defdev.eu/trainers/glenn-ten-cate)

