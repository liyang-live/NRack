NDock  [![Build Status](https://travis-ci.org/kerryjiang/NDock.svg?branch=master)](https://travis-ci.org/kerryjiang/NDock)
=====

**NDock** is a server application container, which can be used for your back end services' hosting and management.

**Features**:

* Automatic service hosting: host your many backend applications, needn't create service for each application;
* External application hosting: host external executable application, no matter whether it is developed using .NET;
* Multiple application isolation: support isolate your multiple applications using AppDomain and process;
* Watch dog: start application after it stops unexpected;
* Automatic recycle management: restart application automatically after it satisify some conditions;
* App Garden: run one application in multiple instances.