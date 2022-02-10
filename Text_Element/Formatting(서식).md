# Formating(서식)
HTML 텍스트에 다양한 효과를 주는 여러 tag(태그)를 제공

## `<b>` , `<strong>`
+ **`<b>` (bold text):** 굵게
+ **`<strong>` :** 굵게 + 중요하다는 뜻 

둘 다 굵게 나타내는 효과를 가지고 있으며 겉보기에도 같아 보인다.

```html
<p><b>굵게</b><br>
<strong>굵고 중요하다</strong></p>
```

## `<i>` , `<em>`
+ **`<i>` (italic text) :** 텍스트 글꼴이 italic 체(기울기)로 바뀌는 것이다.
+ **`<em>` (emphasized text) :** 텍스트 글꼴이 italic 체(기울기)로 바뀜 + 중요하다는 뜻

둘 다 곁보기에 똑같이 italic체(기울기)로 보인다.

```html
<p><i>기울기</i><br>
<em>기울기 중요</em></p>
```


## `<mark>`
하이라이팅(highlighting)효과를 준다(그냥 텍스트 배경에 색이 입혀진다.)
```html
<p><mark>하이라이팅</mark></p>
```

## `<del>`
delete 로 텍스트 중앙에 가로선으로 그어지며 취소선을 만든다.
```html
<p><del>취소선</del></p>
```

## `<ins>`
insert로 텍스트가 삽입한 느낌을 주는 텍스트 밑줄 긋기
```html
<p><ins>밑줄</ins></p>
```

## `<sup>` , `<sub>`
superscript, subscript 로 수학공식에서 제곱과 변수 번호 표현할 때 쓰인다.
```html
<p>X<sup>2</sup> + Y<sup>2</sup><sub>0</sub> = Z<sub>0</sub>
```