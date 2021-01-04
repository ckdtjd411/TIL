# HTML 기초

## 1. HTML 이해하기

### 1.1 HTML(Hyper Text Markup Language)

* 웹 페이지를 만드는 언어

* Hyper Text - 웹 페이지의 특정 부분과 연결할 수 있는 기능을 가진 텍스트(링크)

* Markup Language - 정보를 구조적, 계층적으로 표현 가능



### 1.2 문법

#### 태그(TAG)

* 무언가를 표시하기 위한 꼬리표, 이름표 

* <,> 기호로 표현하며 <,> 기호 사이에 태그 이름

* 시작 태그와 종료 태그로 이루어지며 종료 태그는 태그 이름 앞에 '/' 기호

  `<h1>hello, HTML</h1>`

  

#### 요소(Element)

* 내용을 포함한 태그 전체



#### 속성

* 태그에 추가로 정보를 제공하거나 태그의 동작이나 표현을 제어할 수 있는 설정값

* 이름, 값으로 구성

* 시작 태그에서 태그 이름 뒤에 공백으로 구분 후 속성 이름="속성값"으로 표현

* 여러 속성을 선언할 때는 공백으로 구분해서 사용



#### 빈 태그

* 내용이 없는 태그

* 브라우저가 직접 화면에 내용을 그려줘야 하는 경우 사용 (replacement 태그)

  `<br> <img src=""> <input type="">`



#### 공백 무시

* 두 칸 이상의 공백을 모두 무시



#### 주석

* 화면에 노출되지 않고 메모의 목적으로 사용
* `<!-- 내용 -->`



### 1.3 문서의 기본 구조

```markup
<!DOCTYPE html>
<html lang="ko">
    <head>
        <meta charset="UTF-8">
        <title>HTML</title>
    </head>
    <body>
        <h1>Hello, HTML</h1>
    </body>
</html>
```

#### 문서 타입 정의

* 문서 타입 정의는 DTD(doctype)라고 부름
* 어떤 버전으로 작성되었는지 브라우저에 알려주는 선언문
* 문서 내 최상단에 선언



#### `<html>` 요소

* 문서 타입 선언 후 `<html>` , 자식으로는 `<head>, <body>`
* html 태그의 lang 속성은 문서가 어느 언어로 작성되었는지를 의미
* head 태그에 위치하는 태그들은 브라우저 화면에 표시되지 않음
  * 문서의 기본 정보 설정이나 외부 스타일 시트 파일 및 js 파일을 연결하는 등의 역할
* meta 태그의 charset 속성은 문자의 인코딩 방식을 지정
* body 태그에는 실제 브라우저 화면에 나타나는 내용





## 2. HTML 태그

### 2.1 HTML 태그

\[HTML 태그]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element

#### 제목 태그

* 제목(heading) 태그는 문서 내에 제목을 표현할 때 사용하는 태그
* 제목의 레벨에 따라서 `<h1>~<h6>`까지 사용



#### 단락 태그

* paragraph를 줄여서 `<p>`로 사용
* p를 사용해서 단락으로 구분하면 자연스럽게 개행이 됨
* `<p>` 내부에서 임의로 개행을 하려면 개행 태그 `<br>` 사용 (linebreak)



#### 텍스트 표현 태그

\[Inline text semantics] : https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Inline_text_semantics



