# things-view-open-behavior

## View를 Open해주는 Behavior.

 view를 기본 다이얼로그로 오픈하는 함수와 FullScreen 다이얼로그로 오픈하는 함수가 있다.

***
view를 full screen 다이얼로그로 오픈요청  `@event things-open-full-screen-view`
***
view를 기본 다이얼로그로 오픈요청 `@event things-open-popup-view`
***
다이얼로그 닫기 요청 @event things-close-popup-view

*****
</br></br>


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-view-open-behavior/`, where `things-view-open-behavior` is the name of the directory containing it.