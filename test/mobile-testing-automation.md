# Mobile testing automation

## About the workshop

Mobile security test automation workshop focuses on how to set up security test automation in your CI/CD pipelines. But also how to create an agnostic pipeline approach that works over different CI tooling. **Build once, run everywhere!**

In the course we will in depth cover different security tooling for mobile software development. We cover static analysis tools and dynamic analysis tools, and in what stages of development to introduce these tools. By learning the tools that the hackers will run against your application, we will learn how to create more robust and hardened applications.

Now, security tooling can only cover the applications technical and misconfiguration vulnerabilities. In this course we will also be learning how to find and define the right security requirements by means of threat modeling and utilizing powerful standards of security controls like `MASVS`. This also helps us to prevent introducing vulnerabilities in the applications business logic.

After we learn how to set up a pipeline generating security metrics for your mobile applications. We now need a way to handle these metrics so that they can be easily worked with. Here we introduce the vulnerability management system. The VMT in short will help you with critical difficulties like delta reporting, false positive suppression, prioritise risk decisions and helps as a powerful reporting tool to your upper management.

### Properties

title: **Mobile testing automation**

**audience**: Android and iOS testers and developers, security engineers, security champions

**duration**: 3-6hrs education time

developed by: [Riccardo ten Cate](../trainers/riccardo-ten-cate.md)

### Prerequisites

Familiarity with with the mobile apps development process and technologies.

### Related courses

* [Android security design and secure coding](../code/android.md)
* [iOS security design and secure coding](../code/ios.md)
* [Mobile security baseline](../lib/mobile-baseline.md)
* [Security test automation in CI/CD pipelines](cicd.md)
* [Docker security](../ops/docker.md)

## Agenda

#### Introduction + setup

* This part covers the introduction to setting up security test automation in the CI/CD pipelines. Here we cover things as tool selection and how you set up a vulnerability management system. Here we also make sure all the participants get access to different platforms such as defect dojo, gitlab, kubernetes, and the intentionally vulnerable software used for the course.

#### Running your first pipeline

* After getting access to all the different platforms we go to Gitlab to start running our first security pipeline, and go through the different steps needed to get the metrics pushed to our defect dojo instance.

#### Building your own pipeline

* Use the blueprint provided in the previous deployment script to run additional tooling

#### Containerize security tools

* In the previous exercises we utilized docker images from the defdev registry, but how do we containerize our favorite tools ourselves?

#### Testing automation, Drozer

* How to use Drozer and building Drozer test scripts for automatic dynamic scanning of the application.

#### Testing automation, Calaba.sh

## Trainers

* [Riccardo ten Cate](../trainers/riccardo-ten-cate.md)

