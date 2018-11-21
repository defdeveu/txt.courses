# JavaScript specific

## The language specific module

### Secure coding in JS  <a id="secure-coding-in-js"></a>

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

* JS obfuscation
* Cryptography in JS

\[\*\] optional, delivered on demand

## Prerequisites

We assume that the developers attending the JS secdev course:

* are familiar with the JS language and with XOX
* understand the HTTP protocol and HTML
* are familiar with basic security features of an enterprise application \(authentication, authorization, the concept of a session\)
* have XOX and a suitable IDE installed on their laptop \(labs desktop\)

