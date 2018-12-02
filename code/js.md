# JavaScript



## About the course

### Overview

The one-day javascript security training will cover the fundamentals of secure coding in javascript. We will teach the most important web vulnerabilities related to javascript from the perspective of the developer. They will learn how to find vulnerabilities during testing, how to recognize them within the source-code, how to avoid, and how to mitigate them. We will cover the security-related specialties of javascript, emphasizing some common pitfalls. We will reach an in-depth understanding of XSS, covering all types and flavors, focusing not only on the theory, but practicing on intentionally vulnerable applications and analyzing their source-code. We will raise awareness of several other js vulnerabilities, CSRF, OSRF, clickjacking, tabnapping as well as some HTML5 related security problems. We will enlighten the significance of CSP and other security-related Http headers. Depending on the needs of the audience we can also present a brief security-evaluation of some popular js technologies \(Angular, React\). 

On the two-days training we do more exercises, thereby deepening the understanding and the awareness of several topics. We can analyze specific technologies \(Angular, React\) in a more detailed manner. We also learn about some tools used by hackers and penetration testers. If time and the structure of the audience allows it, we can even finish the course by analyzing the some of the audience’s own source code, trying to find vulnerabilities and putting into practice what we learned during the course.

### Properties

title: **Secure development in Javascript**

revision: R1811i %wip

audience: senior/medior developers, lead devs, testers and security champions \(mostly comprehensible for juniors as well\)

duration: 2 days \(12 hrs education time\) in the standard case; 1 XL day \(7 hrs\)

options: DIY code and ASVS audit; [assisted code-review lab](../ctrl/codereview-lab.md); [S-SDLC playbook](../ctrl/ssdlc-playbook.md)

developed by: Péter Nyilasy, Glenn ten Cate, Marek Zachara

### Agenda structure

{% hint style="info" %}
The below agenda represents a collection of topics and classes we deliver on a course, normally or optionally, in depth or in a short version depending on the needs of the client and the actual audience. The below agenda does not represent a lineup of the topics and classes.
{% endhint %}

For many of the topics in the below agenda we prepare demos, code fixing exercises, and DIY practices. Most of the hands-ons and other practical exercises are available as cloud instances developed and hosted by defdev.eu.

A defdev course for developers consists of the following ingredients:

* [Intros](../delivery/agenda-structure.md#intros) \[see block A\]; 
* [Secure coding](../delivery/agenda-structure.md#secure-coding) \[see block B\]; 
* [Secure architecting](../delivery/agenda-structure.md#secure-architecting) \[see block C\]; 
* [Framework/language specifics](../delivery/agenda-structure.md#framework-language-specifics) \[see [block D](webapps-all.md)\]; 
* [Security testing and audit](../delivery/agenda-structure.md#security-testing-and-audit) \[see [block E](../ctrl/codereview-lab.md)\]; 
* [Options](../delivery/agenda-structure.md#options)

### Days and kits

By default the duration of a course is 2 days, 12 hours education time in the standard case. But it also can take 3 days depending on the demands, the preferences regarding the coverage or the depth and also the options requested. The general content variants are:

* [2 days, broad coverage](../delivery/kits.md#2-days-broad-coverage)
* [2 days, in-depth selected topics](../delivery/kits.md#2-days-in-depth-selected-topics) 
* [3 days, both depth and scope ](../delivery/kits.md#3-days-both-depth-and-scope)
* [3 days, assisted code-review](../delivery/kits.md#3-days-assisted-code-review)

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
* Access management in a RESTful environment \(to JWT or not to JWT\)
* OAuth2, OpenID Connect

#### Server-side defense

* API security, design and implementation
* Web service security _\[optional\]_
* Attack surface

#### Other security features

* Audit support \(separate audit logs, managing debug logs\)
* Intrusion detection, correct reactions
* Protecting the admin interface

### D. Secure coding in JS

{% hint style="info" %}
Developed by Péter Nyilasy
{% endhint %}

#### Is JS a secure language? 

* Automatic conversions
* Type safety
* Variable scopes
* Eval, setTimeout, etc,,,

#### Js injections

* XSS
  * Types \(reflective, stored, dom-based, non dom-based\) 
  * Dangerous js functions \(Vanilla and jQuery\)
  * How to defend 
  * BeEF demo \[\*\]
* Other html injections
* Open redirection
* Client side sqli \[\*\]
* Cookie injection

#### Other JS \(or JS related\) vulnerabilities 

* The same origin policy, CSRF, CORS
* OSRF
* Clickjacking
* Tabnapping

#### HTML5 security

* Web storage \[\*\]
* WebSockets \[\*\]
* Web Messaging \[\*\]
* Webworkers \[\*\]
* Iframe sandboxing
* CSP and other security headers

#### Technology specific security 

* ReactJS security \[\*\]
* Angular security \[\*\]

#### Other topics 

* JS obfuscation \[\*\]
* Cryptography in JS \[\*\]

\[\*\] optional, delivered on demand

## Trainers

In delivering the course one or two of the following trainers are involved as lead trainer or co-trainer:

{% hint style="info" %}
When it comes to the actual proposal we define who is supposed to do the delivery and in what formation or schedule.
{% endhint %}

* [Glenn ten Cate](../trainers/glenn-ten-cate.md)
* [Péter Nyilasy](../trainers/peter-nyilasy.md) 
* [Marek Zachara](../trainers/marek-zachara.md) 
* [Riccardo ten Cate](../trainers/riccardo-ten-cate.md)

