# List(리스트)

HTML의 리스트란 여러 요소들을 일렬로 나열한 목록이나 명단을 의미한다.

+ HTML 의 리스트는 총 3가지로 표현한다.
    1. 순서가 없는 리스트(unordered list)
    2. 순서가 있는 리스트(ordered list)
    3. 정의 리스트(definition list)


## unordered list(순서가 없는 리스트)

순서가 없는 리스트는 `<ul>` 태그를 쓰며, 안에 `<li>`태그로 표시한다.
`<li>`는 기본 마커인 검은색 작은 원이다.

```html
<ul>
    <li>작은원1</li>
    <li>작은원2</li>
    <li>작은원3</li>
</ul>
```

![1](https://user-images.githubusercontent.com/38696775/153859980-cb8a5c02-7eb2-4502-b29b-92fd72da1c3b.png)


CSS 인 list-style-type 속성을 사용하면 마커를 다른 모양으로 바꿀 수 있다.
```html
<ul style="list-style-type:circle">
    <li>빈원1</li>
    <li>빈원2</li>
    <li>빈원3</li>
</ul>

<ul style="list-style-type: square">
    <li>사각형1</li>
    <li>사각형2</li>
    <li>사각형3</li>
</ul>
```
![2](https://user-images.githubusercontent.com/38696775/153860000-1afa4a6a-5178-4337-adc7-779c463afb93.png)
![3](https://user-images.githubusercontent.com/38696775/153860008-ec9d66a3-3f05-4667-b5f1-0cb9844bed7b.png)



## Ordered List(순서가 있는 리스트)

순서가 있는 리슽트는 `<ol>`로 시작하여 `<li>`을 붙이면 된다.

```html
<ol>
    <li>순서1</li>
    <li>순서2</li>
    <li>순서3</li>
</ol>
```

![4](https://user-images.githubusercontent.com/38696775/153860029-dc4f2a1c-b49b-4a3c-8211-edce53930cac.png)


`<ol style="list-style-type: upper-alpha">` 형식으로 쓰게 되면 마커를 변경시킬 수 있다.
+ upper-alpha : 영문 대문자
+ lower-alpha : 영문 소문자
+ upper-roman : 로마 숫자 대문자
+ lower-roman : 로마 숫자 소문자


## Description List(정의 리스트)

`<dl>` 태그로 시작하여 `<dt>`에는 용어 이름 `<dd>` 용어 정의가 들어간다.

```html
<dl>
    <dt>정의리스트1</dt>
    <dd>- 용어를 정의하는 리스트1</dd>
    <dt>정의리스트2</dt>
    <dd>- 용어를 정의하는 리스트2</dd>
</dl>
```

![5](https://user-images.githubusercontent.com/38696775/153860042-7ef2af6d-c171-4a5b-bd81-8f4101fc8e88.png)



참조 : http://www.tcpschool.com/html/html_basic_lists
