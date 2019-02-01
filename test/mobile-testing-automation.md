# Mobile testing automation

## About the course

{% hint style="danger" %}
Work in progress
{% endhint %}

### Overview

XOX

### Properties

title: **Mobile testing automation**

audience: XOX

duration: 3-6hrs education time

developed by: Riccardo ten Cate

### Prerequisites

We assume that the developers attending the preps mobile secdev course:

* are familiar with with the mobile apps development process and technologies

### Related courses

* [Android security design and secure coding]()
* [iOS security design and secure coding](../code/ios.md)
* [Mobile security baseline](../lib/mobile-baseline.md)

## Agenda

#### Introduction + setup

* This part covers the Introduction to setting up security test automation in the CI/CD pipelines. Here we cover things as tool selection and how you set up a vulnerability management system. Here we also make sure all the participants get access to different platforms such as defect dojo, gitlab, kubernetes, and the intentionally vulnerable software used for the course.

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

