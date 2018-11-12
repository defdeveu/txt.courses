# Secure development in Java

### Agenda

#### A. Intro to principles and practice of secdev

**Introduction to vulnerabilities**

* 'Into the middle of things' hands-on hacking
* Playing with untuned source code scanning
* Playing with identifying real threats and security requirements 

  **Intro to secure coding**

* OWASP ASVS topics, an introduction to the areas to protect
* How a properly designed infrastructure architecture should be built

  **Intro to practical secure development**

* Setting up the right security requirements
* Create and train security champions
* S-SDLC basics, secure development as integral part of SDLC
* Automatic tools and their values, non-automatic tools, pentests, peer code review, assisted code-review

#### B.    Code security

**Common server-side vulnerabilities and their defense**

* Injections: SQLi, XML injections, JSON, XPath, XSS, cookie injection,  open redirection, http header injection

  Path traversal, XXE, Buffer overflow, Zip bomb, Million laugh, RFI, Insecure file upload, Code execution

* Insecure direct object reference

  **Common client-side vulnerabilities and their defense**

* XSS \(types, impact, causes, defenses, other html injections, BeEF\)
* CSRF, Clickjacking, Same-origin policy, CORS
* Tabnabbing

  **Server-side defense**

* Input validation vs encoding

  **Some security features**

* Security logging, exception handling

#### C. Security design

**Security by design**

* Threat modelling
* Separation of duties, trust boundaries, security boundaries, defence in depth, principle of least privilege, minimising the attack surface, risk driven mitigation
* Business logic vulnerabilities

  **Cryptography**

* Cryptography basics
* TLS, ciphersuites
* HTTP certificate pinning 
* Perfect forward secrecy, certificate transparency

  **Http configuration**

* CSP, HSTS, Cookie settings, x-content-type-options

  **Access management**

* Authentication principles, session management, authorization
* RESTful authorization \(OAuth2, OpenID Connect\)
* JSON web tokens, JWT

  **Server-side defense**

* API security, design and implementation
* Web service security _\[optional\]_
* Attack surface

  **Other security features**

* Audit support \(separate audit logs, managing debug logs\)
* Intrusion detection, correct reactions
* Protecting the admin interface

#### D. Framework/language specifics

**Secure coding in Java/JEE**

* Java security manager
* Java language security \(is Java a secure language?\) 
* Java-specific issues 
  * Numeric overflow, automatic conversions
  * Serialization, JPQL
* SEI CERT Oracle Coding Standard for Java
* Cryptography in Java

  **JS frameworks \[optional\]**

* Angular JS/TS
* Polymer
* React

  **HTML5 \[optional\]**

* Local storage/session storage 
* Web messaging, web sockets

