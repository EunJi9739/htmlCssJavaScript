* 웹 페이지란?
    - 일종의 문서 파일
    - 웹 페이지를 작성하는 도구의 이름 → HTML
    - 웹 페이지들이 모여서 만들어진 덩어리 → 웹 사이트

* 개발자란?
    - 컴퓨터를 활용해 소프트웨어를 제작하는 사람

* 웹 개발자
    - HTTP 통신 등을 활용하는 웹 사이트나 관련된 소프트웨어 또는 시스템을 구축하는 소프트웨어 엔지니어
    - 프론트엔드 개발자
        - 사용자가 직접적으로 눈으로 보며 사용하는 웹페이지를 개발
        - 정보를 아름답게 배치
        - 사용자가 조금 더 쾌적하게 사이트를 사용할 수 있도록 기능을 개선
        - 편의성 + 디자인 영역
    - 백엔드 개발자
        - 데이터 저장
        - 프론트엔드의 원활한 작동을 도와주기 위한 서버를 개발하는 엔지니어

* 마크업 언어
    - 문서에 마크업을 추가하기 위해 사용하는 도구

* 프로그래밍 언어
    - 프로그래밍 → 명령을 설계하는 행위
    - 컴퓨터에 명령을 내리기 위해 사용하는 언어

* 프레임 워크
    - 복잡한 문제를 해결하는 데 사용할 수 있도록 누군가가 만들어둔 소프트웨어


* HTML
    - HyperText Mark-up Language
    - 종이책의 한계를 초월한 다양한 기능을 선보이기 위해 사용하는 마크업 언어

***
* \<html\>
    - html 코드임을 표현
* \<head\>
    - 웹 페이지 헤드 부분임을 표현
* \<body\>
    - 문서의 본문임을 표현
* \<title\>
    - 사이트 제목을 표현
* \<meta\>
    - 메타 데이터 표현
    - 웹 사이트에 대한 정보를 알려주지만 브라우저 화면에 표시X
        ```
        <head>
            <meta name="description" conetn="sample"/>
        </head>
        ```
* \<div\>
    - 콘텐츠를 담는 그릇
    - 줄 바꿈 O
* \<a\>
    - 하이퍼링크
        ```
        <a href="url">콘텐츠</a>
* \<script\>
    - 자바스크립트 삽입
* \<link\>
    - 외부 파일을 HTML 문서와 연결
        ```
        <link rel="style.css" type="text/css"/>
        ```
* \<img\>
    - 문서에 이미지 삽입
        ```
        <img src="이미지 경로"/>
        ```
        
***
* \<span\>
    - 콘텐츠를 담는 그릇
    - 줄바꿈 X
* \<p\>
    - 문단(단락) 표현
    - 줄바꿈 O
* \<li\>와 \<ul\>
    - 목록(리스트) 표현을 위해 사용
* \<style\>
    - CSS 코드 삽입
* \<br\>
    - 줄 바꿈

***
* \<h1\>
    - 가장 큰 제목
* \<h2\>
    - 두 번째로 큰 제목
* \<input\>
    - 화면에 입력창 삽입
    - value : 도움말
    - type
        - number, password, tel, search, email, url, button, summit, file, color, checkbox, radio, range, date, month, week, time, datetime-local ...
            ```
            <input type="file" accept="image/*"/>
            <input type="file" accept="audio/*"/>
            <input type="file" accept="video/*"/>
            <input type="file" accept=".jpg, .png, .pdf"/>
            ```
            ```
            <input type="radio" name="radio1" checked/>한식
            <input type="radio" name="radio1"/>중식
            <input type="radio" name="radio1"/>양식
            <input type="radio" name="radio1"/>일식
            ```
            ```
            <input type="range" min="0" max="1000" step="10" value="10"/>
            ```
                
* \<form\>
    - 정보를 모아 한번에 전송
* \<h3\>
    - 세 번째로 큰 제목
* \<iframe\>
    - 다른 콘텐츠를 현재 문서에 삽입
* \<nav\>
    - 하이퍼링크를 모아 두는 영역 표시
* \<strong\>
    - 글자 굵게
* \<footer\>
    - 웹 사이트 푸터 작성
* \<header\>
    - 웹 사이트 헤더 작성
* \<button\>
    - 화면에 버튼 삽입

***

* Class
    - 남들과는 구분되지만
    - 여러 번 등장할 수 있는 정보
* Id
    - 디자인을 적용하기는 해야 하는데
    - 태그를 선택자로 사용하자니 너무 범위가 넓어 의도치 않은 곳에도 디자인이 적용될 것 같고
    - 문서를 통틀어 딱 한 번 등장하는 정보이므로 클래스와는 차별점을 두고 싶을 때

* CSS 우선 순위
    - ID > Class > 태그
    - HTML 태그 내부의 style 속성 > HTML 코드 내부의 \<style\> 태그 > 외부 CSS 파일 

* 공간의 단위
    - %
        - 부모 대비 비율
    - auto
        - 브라우저가 자동으로 계산
    - vw, vh
        - 브라우저 창의 해상도를 기준으로 삼음

```
선택자{
    color : rgb(0, 0, 0);
    color : rgba(0, 0, 0, 0);
    color : #FFFFFF;

    font-style : italic;
    font-weight : 100;
    font-variant : small-caps;
    font-size : 15px;
    font-famaily : 폰트 이름;
    text-align : center;
    text-decoration : underline;

}
```
***
* typeof
* 데이터 타입
    - Number
    - String
    - Boolean
    - underfined

* 주로 쓰이는 String 메서드
    - length
    - startWith
    - endWith
    - indexOf
    - repeat
    - replace
    - split
    - toUpperCase
    - toLowerCase

* 타입캐스팅
    - String
    - Number
    - Boolean

* 인덱싱
    ``` 
    > "abcde"[2]
    "c"
    ```
* 슬라이싱
    ```
    > "abcdefgh".slice(3,5)
    de
    ```

* 변수
    - let
    - const

* 비교 연산자
    - ===
    - !==
    - <
    - \>
    - \>=
    - <=

* 배열
    ```
    > let a = [1, 2, 3, 4]
    > a
    (4) [1, 2, 3, 4]
    ```
* 객체 만들기
    ```
    > let id = {
        name : "은지",
        age : 27,
        books : "업무 자동화",
        job : "Engineer"
    }
    ```
* 이벤트 리스너
    ```
    요소.addEventListner(이벤트, 
        function(e){
            실행할 내용
        }
    )
    ```

* 자주 쓰이는 이벤트들
    |이벤트명|인라인 호출 시|발생 시점|
    |-------|-------------|----------|
    |keydown|onKeydown|키가 눌렸을 때|
    |click|onClick|요소가 클릭되었을 때|
    |doubleclick|onDoubleclick|요소가 더블 클릭되었을 때|
    |mouseover|onMouseover|요소 위에 마우스 포인터가 올라왔을 때|
    |mouseleave|onMouseleave|요소로부터 마우스 포인터가 벗어났을 때|
    |change|onChange|요소의 값이 변경될 때|
    |input|onInput|사용자가 요소에 값을 입력할 때|
    |submit|onSubmit|form 요소의 제출 버튼이 클릭되었을 때|
    |reset|onReset|form 요소의 리셋 버튼이 클릭되었을 때|
