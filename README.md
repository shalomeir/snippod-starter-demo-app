# **Snippod-Starter-Quickstart-React**

[![Join the chat at https://gitter.im/shalomeir/snippod-boilerplate](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/shalomeir/snippod-boilerplate?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## 개요

본 [**Snippod-Starter-Quickstart-React**](https://github.com/KoreaHTML5/snippod-starter-quickstart-react) 저장소는 풀스택 SPA(Full Stack Single Page Application) 데모 코드로 [React](http://facebook.github.io/react/)와 [Django](https://www.djangoproject.com/)로 이루어져 있습니다.
보다 자세한 내용은 [웹Frameworks.kr](http://webframeworks.kr/)의 tutorial 포스트인 ['React with Redux 와 Django를 이용한 SPA 개발'](http://webframeworks.kr/tutorials/react/react-django-full-stack-spa/)을 참고하세요.

호스팅 되고 있는 [**데모**](http://snippod-demo-front.ap-northeast-2.elasticbeanstalk.com/) url은 [http://snippod-demo-front.ap-northeast-2.elasticbeanstalk.com/](http://snippod-demo-front.ap-northeast-2.elasticbeanstalk.com/)입니다.

![스택 다이어그램](https://raw.githubusercontent.com/shalomeir/snippod-starter-demo-app/master/SnippodStarterDemoAppArchitecture.png "Stack Diagram")

## 기본 구성

실제 저장소는 [React](http://facebook.github.io/react/)와 [Redux](https://github.com/gaearon/redux)로 이루어진 프론트엔드용 웹어플리케이션과 [Django](https://www.djangoproject.com/)를 이용한 서버 프로그램으로 나뉘며 이는 각각 별도의 서브모듈 저장소를 통해 제공되고 있습니다.

* [**Snippod-Starter-Demo-App-Front**](https://github.com/shalomeir/snippod-starter-demo-app-front)
* [**Snippod-Starter-Demo-App-Server**](https://github.com/shalomeir/snippod-starter-demo-app-server)


## 시작하기
사전준비 :
* npm v2.15.5 or higher
* Node v4.4.6 - [Node Version Manager (NVM)](https://github.com/creationix/nvm)을 추천합니다.
* Python 3.4
* virtualenv (optional)

저장소를 'git clone' 으로 받은 후 추가로 '서브모듈 update'를 통해 서브모듈들을 받아야 합니다.
```
git clone https://github.com/shalomeir/snippod-starter-demo-app
git submodule update --init
```

보다 세부적인 스텝은 개별 저장소인 **서브모듈**에서 확인해주세요.
그리고 가장 기초적인 코드 부터 단계별로 따라가고 싶으신 분들은 프론트엔드 저장소인 [Snippod-Starter-Demo-App-Front](https://github.com/shalomeir/snippod-starter-demo-app-front)의 [**codelab branch**](https://github.com/shalomeir/snippod-starter-demo-app-front/tree/codelab)를 참고하세요.


## 데모

A 데모는 [여기](http://snippod-demo-front.ap-northeast-2.elasticbeanstalk.com/)에서 볼 수 있습니다.

[![Alt 앱 데모](https://raw.githubusercontent.com/shalomeir/snippod-starter-demo-app-front/master/SnippodStarterDemoApp_Capture_En_160717.png "App Demo")](http://snippod-demo-front.ap-northeast-2.elasticbeanstalk.com/)


## 참고

본 저장소는 스타트업 [**Snippod**](https://www.snippod.com/)에서 공유, 관리하고 있는 [Snippod-Starter-Demo-App](https://github.com/shalomeir/snippod-starter-demo-app)저장소를 통해 업데이트 되고 있습니다.

## 라이센스
[MIT License](http://opensource.org/licenses/MIT).
