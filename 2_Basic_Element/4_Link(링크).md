# Link(링크)

하이퍼 링크

+ 문법
    + `<a href = "링크주소">링크대변할 글</a>`

**href attribute은 연결할 페이지나 사이트 주고를 명시하는 속성입니다.**
**`<a>`는 텍스트나 단락, 이미지 등 다용한 HTML 요소에 사용할 수 있다.**

```html
<a href = "https://www.naver.com/"><h1>네이버</h1></a>
```


## `<a>`의 target 속성

링크로 연결된 문서를 어디에서 열지를 명시

```html
<h2><a href="https://www.naver.com/" target="_blank">blank</a></h2>
<h2><a href="https://www.naver.com/" target="_self">self</a></h2>
<h2><a href="https://www.naver.com/" target="_parent">parent</a></h2>
<h2><a href="https://www.naver.com/" target="_top">top</a></h2>
<h2><a href="Background(배경색).html" target="myframe">myframe</a></h2>

<iframe name="myframe" style="width:50%; height: 330px"></iframe>
```


![1](https://user-images.githubusercontent.com/38696775/153709133-a9cdf0e1-870f-44fd-b3c3-25e2a3785098.png)

(이미 방문해서 색깔이 방문해진 상태가 되었습니다.)

+ _blank : 새창이나 새 탭으로 연결된 문서 오픈
+ _self : 현재 frame(프레임, 창)에서 오픈 (기본 설정으로 되어 있음)    
+ _parent : 부모 frame에서 오픈
+ _top : 가장 상위 frame 에서 오픈
+ 프레임 이름 : 지정된 frame 에서 오픈


+ iframe : 웹 안에 새로운 웹 페이지를 만든다고 보면 된다.(이후 자세한 것은 iframe 에서 설명 할 것이다. )


## `<a>` state 링크 설정

CSS 로 설정을 해야한다.

링크 상태는 총 4가지다

+ link : 아직 한번도 방문하지 않은 상태 (텍스트에 밑줄과 파란색으로 초기 설정되어 있다.)
+ visited : 한번이라도 방문한 상태 (텍스트에 밑줄과 보라색으로 초기 설정되어 있다.)
+ hover : 링크 위에 마우스를 올려놓은 상태 
+ active : 링크를 마우스로 누르고 있는 상태 (텍스트에 밑줄과 빨간색으로 초기 설정되어 있다.)

```html

<style>
    a:link    { color: black; }
    a:visited { color: red; text-decoration: none }
    a:hover   { color: yellow; text-decoration: none }
    a:active  { color: green; text-decoration: none }
</style>

```

![2](https://user-images.githubusercontent.com/38696775/153709155-2d614d58-8c76-4f65-91f6-c0a1a47f31b7.png)

(이미 방문해서 색깔이 방문해진 상태가 되었습니다.)


## 페이지 책갈피
attribute 인 name을 이용하여 요소에 이름을 부여한 뒤

`<a>`의 href 로 불러와 간단한 책갈피를 만들 수 있다.

```html
<a href = "#bookmark"><p>bookmark로 이동</p></a>


<h2><a name = "bookmark"><p>bookmark</p></a>
```

참조 : http://www.tcpschool.com/html/html_basic_links
