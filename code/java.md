---
description: >-
  'Secure development in Java/JEE' course template. Using the "Webapp
  development with security in mind" template and the 'Secure coding in
  Java/JEE' language specific module.
---

# Java

## About the course

### Overview

The two-day java security workshop covers the fundamentals of secure coding in a web-related environment. We can on the fly flex the course to meet the level and the experiences of the audience.

During the course, developers learn how to find vulnerabilities, how to identify them within the source code, how to avoid, and how to mitigate them. We believe that developers understand security concepts at best when it is presented in their own programming language, therefore in this course, every example \(except HTML and js specifics\) are demonstrated via Java code. 

Doing exercises is the most fun and most effective way of learning security concepts, and so during the workshop, the attendees will identify and fix security vulnerabilities in [Javulna](https://github.com/defdeveu/javulna), a deliberately vulnerable Java application, developed by us \(available on Github\). 

The course covers the following topics: 

* Secure-coding principles 
* Injections \(SQL, XML, LDAP, path-traversal, etc...\) 
* Other server-side vulnerabilities \(XXE, CSRF, Billion laughs, RFI\) 
* Java-specific \(overflows, type-safety, serialization, Java Security Manager, Java-coding best-practices by SEI CERT\) 
* Client-side vulnerabilities \(XSS, HTML injection, Clickjacking, Tabnabbing\) 
* Http security-related headers
* Security of the most fundamental authentication and authorization schemes. 

Based on their previous knowledge and interest attendees can further choose from the following topics: 

* Security of OAuth and OpenId
* Cryptography basics
* Cryptography of the web \(TLS, certificate pinning\)
* HTML5 security 
* Security of some JS frameworks.

Auditing of the attendees' own source-code, identifying security best-practises of their specific technologies can be part of the two-days workshop, or extended to an additional day \(see Related courses below\).

### Properties

title: **Secure development in Java/JEE**

**audience**: senior/medior developers, lead devs, testers and security champions \(mostly comprehensible for juniors as well\)

**duration**: 2 days \(12 hrs education time\) in the standard case, 3 days if combined with additional modules \(see the related courses below\)

Java specific parts are developed by: [Péter Nyilasy](../trainers/peter-nyilasy.md)  

### Prerequisites

We assume that the developers attending the Java secdev course:

* are familiar with the Java language and with JEE
* understand the HTTP protocol, HTML and Javascript
* are familiar with basic security features of an enterprise application \(authentication, authorization, the concept of a session\)
* have Java \(JDK\) and a suitable IDE installed on their laptop \(labs desktop\)

### Related courses

* DIY code and ASVS audit
* [Assisted code-review lab](../ctrl/codereview-lab.md)
* [S-SDLC playbook](../ctrl/ssdlc-playbook.md)

## Agenda

### A. Intro to principles and practice of secdev

#### Introduction to vulnerabilities

* 'Into the middle of things' hands-on hacking
* Playing with untuned source code scanning
* Playing with identifying real threats and security requirements 

#### Intro to secure coding

* OWASP ASVS topics, an introduction to the areas to protect
* How a properly designed infrastructure architecture should be built

#### Intro to practical secure development

* Setting up the right security requirements
* Create and train security champions
* S-SDLC basics, secure development as integral part of SDLC
* Automatic tools and their values, non-automatic tools, pentests, peer code review, assisted code-review

### B.    Code security

#### Common server-side vulnerabilities and their defense

* Injections: SQLi, XML injections, JSON, XPath, XSS, cookie injection, open redirection, http header injection

  Path traversal, XXE, Buffer overflow, Zip bomb, Million laugh, RFI, Insecure file upload, Code execution

* Insecure direct object reference

#### Common client-side vulnerabilities and their defense

* XSS \(types, impact, causes, defenses, other html injections, BeEF\)
* CSRF, Clickjacking, Same-origin policy, CORS
* Tabnabbing

#### Server-side defense

* Input validation vs encoding

#### Some security features

* Security logging, exception handling

### C. Security design

#### Security by design

* Threat modelling
* Separation of duties, trust boundaries, security boundaries, defence in depth, principle of least privilege, minimising the attack surface, risk driven mitigation
* Business logic vulnerabilities

#### Cryptography

* Cryptography basics
* TLS, ciphersuites
* HTTP certificate pinning 
* Perfect forward secrecy, certificate transparency

#### Http configuration

* CSP, HSTS, Cookie settings, x-content-type-options

#### Access management

* Authentication principles, session management, authorization
* RESTful authorization \(OAuth2, OpenID Connect\)
* JSON web tokens, JWT

#### Server-side defense

* API security, design and implementation
* Web service security _\[optional\]_
* Attack surface

#### Other security features

* Audit support \(separate audit logs, managing debug logs\)
* Intrusion detection, correct reactions
* Protecting the admin interface

### D. Framework/language specifics

#### Secure coding in Java/JEE     <a id="secure-coding-in-java-jee"></a>

{% hint style="info" %}
Developed by Péter Nyilasy
{% endhint %}

* Java security manager
* Java language security \(is Java a secure language?\)
* Java-specific issues
  * Numeric overflow, automatic conversions
  * Serialization, JPQL
* SEI CERT Oracle Coding Standard for Java
* Cryptography in Java

#### JS frameworks _\[optional\]_

* Angular JS/TS
* Polymer
* React

#### HTML5 _\[optional\]_

* Local storage/session storage 
* Web messaging, web sockets

### E. Security testing and audit \[optional\]

Practicing is part of many of the above blocks. We start off basic hacking challenges, but the real exercises are about fixing vulnerable codes, and tasks when attendees need to assess code and an application on their own. We mostly offer cloud based facilities to run the exercise environments, so no local installation is needed.

#### Hands-ons with vulnerable apps

* For most of the courses there are intentionally vulnerable applications which we use to demonstrate and learn specific vulnerabilities and how to fix them.
* In some cases we use public "damn vulnerable" applications, in some cases we prepared our own applications to practice with. 

#### DIY sonarqube code checking

* We assume that developers should be capable of running basic automated tests against the security of their codes on their own. And also be able to tune the SCA tools to produce reasonable false positive and valuable findings ratio. 
* Normally we teach how to use security plugins of Sonarqube. 
* We provide sample codes to test. Though the best experience is achieved when developers run the security SCA against their own codes. 
* See also the extra, on-demand block of 'Assisted code-review lab' below for practicing on your own codes. 

#### DIY ASVS self-audit

* OWASP ASVS is the current standard for assessing the security quality and design flaws of a \(web\) application, and it's the developers who know the answers to the ASVS audit questions. So we take developers to a short journey in assessing the security properties of their applications.

## Trainers

{% hint style="info" %}
Check out the trainers' bios in the Trainers section
{% endhint %}

Lead trainers:

* [Péter Nyilasy](../trainers/peter-nyilasy.md) 
* [Glenn ten Cate](../trainers/glenn-ten-cate.md) 

Co-trainer:

* [Marek Zachara](../trainers/marek-zachara.md) 

## Disclaimer

This document describes a subject under discussion. The agenda of the training and the particulars of the planned delivery may change during further iterations of the discussion.

