# WEP-PROGECT

## YOLO옵서예
* Team project for Web Programming
* 2040 세대들 즉 젊은 층을 타겟으로 설정하여 제주도의 각 구역별 먹거리, 놀거리, 볼거리에 관한 정보를 소개해주는 클라이언트 사이트
* Open App : https://yolo-obseoye.herokuapp.com/


### 관광지 데이터 선정의 기준?
* 타겟을 2040으로 설정한 만큼 젊은 층의 사용자가 많은 인스타그램 해시태그 수 많은 순으로 선정
* 타겟 사이트인 VISIT 제주 사이트에서 리뷰 수 높은 순으로 선정


## YOLO옵서예 메인 화면
<img width = "700" src = "https://user-images.githubusercontent.com/67010327/103907308-75264380-5144-11eb-9e7c-7e3745fa5a8b.png">
<img width = "700" src = "https://user-images.githubusercontent.com/67010327/103850056-ab82a500-50e9-11eb-886f-2546656778ba.png">


## YOLO옵서예 2번째 페이지
<img width = "700" src = "https://user-images.githubusercontent.com/67010327/103907320-78b9ca80-5144-11eb-8a2f-c113a30e1e55.png">


## YOLO옵서예 3번째 페이지
<img width = "700" src = "https://user-images.githubusercontent.com/67010327/103907326-7bb4bb00-5144-11eb-9231-f77e8c09a145.png">


## YOLO옵서예 4번째 페이지
<img width = "700" src = "https://user-images.githubusercontent.com/67010327/103907337-7ce5e800-5144-11eb-921f-ffe1995403a7.png">

## Tech
Yolo Obseoye uses a number of open source projects to work properly:

* HTML5 - Markup web pages
* CSS - how HTML elements are to be displayed on screen
* Javascript - change elements of HTML and CSS dinamically
* node.js - execute server on localhost
* jQuery - Javascript library to much easier to deal with HTML and CSS elements
* Heroku - platform as a service enables to operate application


## Installation
Yolo Obseoye requires Node.js v6+ to run.

Install the dependencies and devDependencies and start the server.

$ cd YOLO-obseoye
$ npm install -d
$ node app.js

## Development
Open your favorite Terminal and run these commands.

$ node app.js

By default, the default will be configured by port 3000, so change this within the app.js if necessary. When ready, simply modify the app.js to operate other port.

const port = process.env.PORT || ${port};

Verify the deployment by navigating to your server address in your preferred browser.

127.0.0.1:port

## Heroku
This web site use Heroku to deployment application. If you wanna deploy your application, follow below steps.

To deploy your application on Heroku, you need to download and install the Heroku CLI.

First, Login to Heroku

$ heroku login

Second, Create a new Git repository

$ cd YOLO-obseoye
$ git init
$ heroku git:remote -a Yolo-obseoye

Third, Deploy your application

git add .
git commit -am "commit message"
git push heroku master
