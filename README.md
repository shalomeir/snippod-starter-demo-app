# **Snippod-Starter-Demo-App**

[![Join the chat at https://gitter.im/shalomeir/snippod-boilerplate](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/shalomeir/snippod-boilerplate?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Overview

A [**Snippod-Starter-Demo-App**](https://github.com/shalomeir/snippod-starter-demo-app) is a 'Full Stack Single Page Application' for the starter who want to be a web application developer.
We'd like to build this starter kit based on full stack single page web application architecture.
Snippod's architecture used a this kind of technology, **React + Flux (Redux) + django REST framewrok + RDBMS**.
[This stack](https://drive.google.com/file/d/0B9ltVFRI_UMiSkhkenBGTEdmTUU/view?usp=sharing) is presented by diagram too.

You can check out the hosted version [**DEMO**](http://snippod-demo-front.ap-northeast-2.elasticbeanstalk.com/) at [http://snippod-demo-front.ap-northeast-2.elasticbeanstalk.com/](http://snippod-demo-front.ap-northeast-2.elasticbeanstalk.com/).

![Alt Stack Diagram](https://raw.githubusercontent.com/shalomeir/snippod-starter-demo-app/master/SnippodStarterDemoAppArchitecture.png "Stack Diagram")

## Base Repository, Module

A frontside [**Snippod-Starter-Demo-App-Front**](https://github.com/shalomeir/snippod-starter-demo-app-front) is built with [React](http://facebook.github.io/react/) and [Redux](https://github.com/gaearon/redux).  
Also a serverside [**Snippod-Starter-Demo-App-Server**](https://github.com/shalomeir/snippod-starter-demo-app-server) is built with [django REST framework](http://www.django-rest-framework.org/).

* [React](http://facebook.github.io/react/)
* [Redux](https://github.com/gaearon/redux)
* [Django](https://www.djangoproject.com/) and [Djnago REST Framework](http://www.django-rest-framework.org/)
* [Node.js](https://nodejs.org/en/)

More information is located in each side of repositories.

## Getting Started
Preliminaries :
* npm v2.15.5 or higher
* Node v4.4.6 - We highly recommend [Node Version Manager (NVM)](https://github.com/creationix/nvm)
* Python 3.4
* virtualenv (optional)

You have to git clone this repository and update all GIT submodules.
```
git clone https://github.com/shalomeir/snippod-starter-demo-app
git submodule update --init
```

Further step is located in a each **submodules**.

* [**Snippod-Starter-Demo-App-Front**](https://github.com/shalomeir/snippod-starter-demo-app-front)
* [**Snippod-Starter-Demo-App-Server**](https://github.com/shalomeir/snippod-starter-demo-app-server)

If you want to follow step by step, go to a [**codelab branch**](https://github.com/shalomeir/snippod-starter-demo-app-front/tree/codelab) of front repository.

## Demo

A demonstration of this app can be seen [here](http://snippod-demo-front.ap-northeast-2.elasticbeanstalk.com/).

[![Alt App Demo](https://raw.githubusercontent.com/shalomeir/snippod-starter-demo-app-front/master/SnippodStarterDemoApp_Capture_En_160717.png "App Demo")](http://snippod-demo-front.ap-northeast-2.elasticbeanstalk.com/)


## Contributing

Contributions, questions and comments are all welcome and encouraged.

## License
[MIT License](http://opensource.org/licenses/MIT).

Copyright 2016, [Snippod Inc.](http://www.snippod.com/)