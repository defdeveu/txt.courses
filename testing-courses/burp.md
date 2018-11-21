---
description: >-
  The purpose of the training is to provide testers and developers an overview
  how the Burp suite can be used for web testing work.
---

# Burp for developers

## About the course

### Overview

The purpose of the training is to provide testers and developers an overview how the Burp suite can be used for web testing work. Even though Burp is primarily designed for penetration testers, its sophisticated capabilities can come handy for everyone whose job is to perform general bug hunting in web applications.

By the end of the training, participants will have a general understanding of how web applications work under the hood, how to use Burp for troubleshooting errors and how to utilize Burp's tool set for re-creation of error conditions by manual HTTP traffic manipulation.

### Properties

title: **Burp suite for testers and developers**

audience: application testers \(non-pentesters\), developers

duration: 2 days \(12hrs education time\)

developed by: Zsombor Kovács

### Prerequisites

#### Technical prerequisites

Each participant needs a working computer with Burp installed. Ideally, a licensed Pro version is accessible for participants, but most of the training agenda can be completed also with the Community version.

#### Knowledge related prerequisites

Participants need a general understanding of how computer networks work, and they should be familiar and comfortable with reading and understanding HTML and simple JavaScript code.

## Agenda

### Chapter 1. Understanding Burp

1. Computer networking in general 
   * The HTTP protocol. Requests and responses. Stateful and stateless protocol philosophy and built-in hacks in HTTP.
2. Browsers and web applications 
   * Executable code vs. static code. Basic browser features \(cookies, caching etc.\) and potential pitfalls.
3. Web proxies
   * Different types, features. SSL related issues. Advantages, disadvantages of proxy implementations.
4. Burp at a glance
   * Overall philosophy of the GUI. Sending requests internally between tools. Basic use of the GUI for static HTTP traffic inspection.
5. Burp and networking 
   * SSL, certificates, the PortswiggerCA. Importing and exporting certificates. Potential pitfalls with the oh-so-many different SSL certificate formats. Downstream and upstream proxies.
6. The Target tab 
   * The significance of scope settings. Exclusion lists and the proper scope selection process.
7. The Spider tab 
   * Operation, caveats and results. Throttling and performance issues.
8. The Repeater
   * Operation, use of this versatile tool in several scenarios.
9. The Sequencer 
   * Setup, parametrization and use. Result interpretation.
10. The Intruder 
    * Interaction with repeater. The payload position template. Different types of payloads. Attack types \(sniper, pitchfork etc.\) and usage. Payload selection and pre-send processing. Throttling and result interpretation.
11. The Decoder 
    * Different encodings and external tools to enhance the efficiency of the process.
12. The Extender
    * Basic concepts, the Burp API. Writing extensions for various tasks in Python.

### Chapter 2. Mastering Burp

In this chapter, lifelike challenges will be presented to participants as small web applications modelling real-life scenarios, which can be overcome by using and fine-tuning several tools in conjunctions within Burp.

## Schedule

**Day 1.** Chapter 1

**Day 2.** Chapter 2

## Trainers

* [Zsombor Kovács](../trainers/zsombor-kovacs.md)

