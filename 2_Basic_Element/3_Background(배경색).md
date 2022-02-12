# Background(배경색)

HTML로 배경색을 바꾸는 방법 2가지

1. 다른 색으로 변경
2. 이미지로 변경

## 다른 색으로 변경

HTML5부터는 CSS로 배경색을 바꾸기에 이를 통해 바꿔보겠다.

```html
<style>
    body { background-color: lime; }
    h1 { background-color: rgb(255,0,0); }
    p { background-color: #0000FF; }
</style>123
```

![1](https://user-images.githubusercontent.com/38696775/153706728-cdb74b15-0eac-4c52-8244-937096257a04.png)


body 태그는 배경색이 lime으로 나오도록 한다.
h1 의 배경색은 빨간색으로 설정
p 의 배경색은 파란색으로 설정.

## 이미지로 변경

`<태그이름 background="이미지주소">`

배경이미지를 사용하면 웹 로딩 시간이 길어짐으로 작은 사이즈의 이미지를 패턴으로 만들어 배경이미지 반복 설정을 한다.


참조 : http://www.tcpschool.com/html/html_basic_backgrounds
