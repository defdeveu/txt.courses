---
description: Spring-flavoured
---

# Security champions boot

### The training story

During the training we will explore what are the activities across the complete SDLC to build secure code, and recognize unsecure code using two different Java applications \(Javula, Webgoat\). Using different security tools \(used by security engineers\) we will exploit the vulnerabilities, create a fix based on the ASVS v4, MASVS \(for mobile\) and SKF recommendations, and validate their effectiveness using previous exploits. The first day will focus on understanding the security standards \(using ASVS and SKF\), how to do threat modelling and how to apply the security principles. After that, using security tools, we will start exploiting web application vulnerabilities using the WebGoat Java app. Each attendee will exploit, fix and retest the vulnerabilities. The second day introduces some of the Spring boot security features \(like the Java Security Manager\) and explores well known issues that affected the Spring Boot. The second part keeps the focus on another batch of backend vulnerabilities and briefly touches how to detect them through source code review processes for mobile and web. Finally an exciting and fun security quiz will take place in the last 30 mins where the winner will be awarded with a defdeveu gadget.

### Takeaway skills

* know threat modeling \(STRIDE methodology\);
* know the  vulnerabilities and their standard treatment in a standard framework \(ASVS, mASVS\);
* get the first hands-on experience with finding those vulnerabilities in damn-vulnerable codes \(Java apps and a Kotlin "mobile banking" app\);
* learn using vulnerability management in production \(SKF\);
* be introduced to the secdev testing tools \(SAST, DAST and dependency checker tools\);
* be introduced to the secure pipeline \(Gitlab runners and automated security testing\);
* be introduced to the S/SDLC approaches \(not a methodology, but some basic principles of making it a persistent practice in the software design, manufacturing, testing and supporting flows\).

### Properties

title: **Security champions boot**

**audience**: security champions, application testers, developers

**duration**: 2 days \(12hrs education time\)

developed by: [Davide Cioccia](../trainers/davide-cioccia.md)

## Draft agenda

#### Day 1

* S/SDLC -- SKF and secure CI/CD pipelines
* ASVS
* MASVS
* Secure coding principles
* Burp introduction, web / mobile
* Threat modelling \(STRIDE\)
* XSS and Security headers \(Webgoat\)
* CSRF and CORS \(Webgoat\)
* IDOR \(Webgoat\)

#### Day 2

* Java Security Manager \(quick\)
* Spring/SB well known vulnerabilities \(quick\)
* SQL Injection \(Javulna\)
* XXE, XML Bomb \(Javulna\)
* Insecure File upload/download \(Javulna\)
* Secure code review Javulna \(Java\) and Vulnabank \(Kotlin/Android\) using SKF and ASVS
* Security quiz

## Trainers

* [Davide Cioccia](../trainers/davide-cioccia.md)

