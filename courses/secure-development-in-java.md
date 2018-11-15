---
description: >-
  The below agenda represents a collection of topics and classes we deliver on a
  course, normally or optionally, in depth or in a short version depending on
  the needs of the client and the audience.
---

# Secure development in Java

{% hint style="warning" %}
Work in progress
{% endhint %}

## About

{% tabs %}
{% tab title="Properties" %}
**title**: Secure development in Java/JEE 

**audience**: senior/medior developers, lead devs, testers and security champions \(mostly comprehensible for juniors as well\) 

**duration**: 2 days \(12 hrs education time\) in the standard case options: DIY code and ASVS audit; assisted code-review lab; S-SDLC playbook 
{% endtab %}

{% tab title="Disclaimer" %}
This document describes a subject under discussion. The agenda of the training and the particulars of the planned delivery may change during further iterations of the discussion.
{% endtab %}

{% tab title="Revision" %}
R1811i %wip
{% endtab %}
{% endtabs %}

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

#### Secure coding in Java/JEE

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

## Trainers

### Péter Nyilasy 

Peter has been doing enterprise web application development for more than a decade now mainly for financial institutions. He has exceptional knowledge of and strong experiences with Java and JEE, and also with several javascript frameworks. In the recent years Péter turned to software security and does secure development consulting, ASVS-based application audits with secmachine.com and is a resident trainer with defdev.eu. Meanwhile he stays current with the software production internals working also as a freelance software engineer. Péter also teaches Java for developers. 

### Marek Zachara 

Marek Zachara graduated with MSc degree in Electrical and Electronic Engineering from University of Bristol, UK in 2000 and received his PhD in Computer Sciences in 2008 from AGH UST, Poland. He is assistant professor at AGH University of Science and Technology in Krakow. Since 2008 Marek have been working on security audits and development of tools and methods for security assessment. For over five years he has been involved in a number of research activities centered around software quality and security, with special focus on simulation and analysis of users behavior. 

### Glenn ten Cate 

As a coder, hacker, speaker, trainer and security researcher employed at ING Belgium Glenn has over 10 years experience in the field of security. One of the founders of defensive development \[defdev\] a security trainings series dedicated to helping you build and maintain secure software and also speaking at multiple other security conferences in the world. His goal is to create an open-source software development life cycle with the tools and knowledge gathered over the years.

