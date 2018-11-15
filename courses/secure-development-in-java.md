---
description: >-
  With the Secure development in Java/JEE course we deliver a complete set of
  knowledge and practicing. We can on the fly flex the course to meet the level
  and the experiences of the audience.
---

# Secure development in Java

{% hint style="warning" %}
Work in progress
{% endhint %}

## About the course

{% tabs %}
{% tab title="Properties" %}
**title**: Secure development in Java/JEE 

**audience**: senior/medior developers, lead devs, testers and security champions \(mostly comprehensible for juniors as well\) 

**duration**: 2 days \(12 hrs education time\) in the standard case options: DIY code and ASVS audit; assisted code-review lab; S-SDLC playbook 

**already delivered to**: Logmein, Siemens, AEGON
{% endtab %}

{% tab title="Disclaimer" %}
This document describes a subject under discussion. The agenda of the training and the particulars of the planned delivery may change during further iterations of the discussion.
{% endtab %}

{% tab title="Revision" %}
R1811i %wip
{% endtab %}
{% endtabs %}

### Agenda ingredients 

The below agenda represents a collection of topics and classes we deliver on a course, normally or optionally, in depth or in a short version depending on the needs of the client and the actual audience. The below agenda does not represent a lineup of the topics and classes. In a defdev course we interweave introductory lecturing with intro exercises and the advanced discussion of topics with practicing the subject matters by doing exercises, DIY tasks and challenges. 

For many of the topics in the below agenda we prepare demos, code fixing exercises, and DIY practices. Most of the hands-ons and other practical exercises are available as cloud instances developed and hosted by defdev.eu. 

A defdev course for developers consists of the following ingredients: 

* **Intros**: We make students experience the problems of hackable software right from the beginning. We touch some topics in introductory mode first, turn to some exercises then, and finally discuss the details based on hands-on experiences. Also there are topics that need to be discussed like S-SDLC which we introduce without details to developers. \[see block A\]; 
* **Secure coding**: The topics of secure implementation every developer is expected to have a good command of in order to produce quality code. We discuss and practice how to avoid vulnerabilities. \[see block B\]; 
* **Secure architecting**: The topics of secure design which should be well applied at the initial phase of software development. We discuss how to make choices regarding threats, crypto, access management, business logic, regarding object references and remote calls, communication configuration, tiers of protection, logging, etc. \[see block C\]; 
* **Framework/language specifics**: Every course has its specific subject, a language or a framework in the context of which the above topics are illustrated. Also every framework and language has its own weaknesses to learn how to avoid. \[see block D\]; 
* **Security testing and audit**: We assume that developers \(and other professionals involved in software production\) should be able to do basic security testing on their own. We teach basics of automated code analysis, and also ASVS review. \[see block E\]; 
* **Options**: The course can be extended with add-on modules, such as assisted code-review or S-SDLC playbook. \[see blocks K,L,M\];

### Course variants 

By default the duration of a course is 2 days, 12 hours education time in the standard case. 

But it also can take 3 days depending on the demands, the preferences regarding the coverage or the depth and also the options requested. An actual course can consist of the main blocks only \(A-E\), or it can be extended with extras, on-demand add-on blocks \(K-...\). 

The general content variants are: 

* **2 days, broad coverage**: We deliver all the topics in the agenda with reasonable amount of exercises. We go in-depth into a few topics the audience is interested the most. 
* **2 days, in-depth selected topics**: We assume the basic knowledge of the most of the topics, we go in-depth into discussion and practicing of a number of topics agreed beforehand or selected on-the-fly. 
* **3 days, both depth and scope**: We deliver all the topics in agenda in-depth and walking through all the exercises. 
* **3 days, assisted code-review**: A custom mixture of scope and depth in topics plus a day or a half of assisted code-review lab.

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

### E. Security testing and audit 

Practicing is part of many of the above blocks. We start off basic hacking challenges, but the real exercises are about fixing vulnerable codes, and tasks when attendees need to assess code and an application on their own. We mostly offer cloud based facilities to run the exercise environments, so no local installation is needed. Hands-ons with vulnerable apps For most of the courses there are intentionally vulnerable applications which we use to demonstrate and learn specific vulnerabilities and how to fix them. In some cases we use public "damn vulnerable" applications, in some cases we prepared our own applications to practice with. DIY sonarqube code checking We assume that developers should be capable of running basic automated tests against the security of their codes on their own. And also be able to tune the SCA tools to produce reasonable false positive and valuable findings ratio. Normally we teach how to use security plugins of Sonarqube. We provide sample codes to test. Though the best experience is achieved when developers run the security SCA against their own codes. See also the extra, on-demand block of 'Assisted code-review lab' below for practicing on your own codes. DIY ASVS self-audit OWASP ASVS is the current standard for assessing the security quality and design flaws of a \(web\) application, and it's the developers who know the answers to the ASVS audit questions. So we take developers to a short journey in assessing the security properties of their applications.

### Extras _\[optional\]_ 

Upon request we also deliver additional blocks: 

* K: In case of languages and frameworks our trainers are familiar with as auditors we can deliver an additional day to let developers apply the knowledge and skills learnt against their own codes. We call it the 'Assisted code-review lab'. 
* L-N: We also suggest one of the related add-on courses: S-SDLC playbook Hacking applications Security test automation in CI/CD pipelines

## Trainers

{% hint style="info" %}
Check out the trainers' bios in the Trainers section
{% endhint %}

* [Péter Nyilasy](../trainers/peter-nyilasy.md) 
* [Marek Zachara](../trainers/marek-zachara.md) 
* [Glenn ten Cate](../trainers/untitled.md) 



