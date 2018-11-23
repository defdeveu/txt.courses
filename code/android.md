---
description: XOX headline
---

# Android

## About the course

{% hint style="danger" %}
Work in progress
{% endhint %}

### Overview

XOX

### Properties

title: **Android security design and secure coding**

audience: XOX

duration: 1 XL day \(7hrs education time\)

developed by: Zsombor Kovács

### Prerequisites

We assume that the developers attending the Android secdev course:

* are familiar with with the mobile apps development process and technologies
* have a suitable IDE installed on their laptop \(labs desktop\)
  * Android Studio installed and configured
  * Genymotion emulator installed and configured

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

