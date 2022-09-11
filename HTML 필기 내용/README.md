# 필기

<a href="https://developer.mozilla.org/ko/docs/Web/HTML">MDN HTML</a>

<a href="https://validator.w3.org/">태그 검사기</a>

<a href="https://developer.mozilla.org/ko/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure">Document and website structure</a>

```
<!--Doctype은 html이다라고 정의한 것-->
<!DOCTYPE html>
<html lang="en">
  <!--사용자에게 보여지는 정보가 없고 meta 데이터만 있다-->
  <head>
    
  </head>
  <!--유저한테 보여지는 것-->
  <body>
   
  </body>
</html>
```

## head안에 들어가는 것
```
<meta charset="UTF-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Document</title>
```

## body 안에 들어가는 것
```
[BOX]

<header>
<footer>
<nav>
<aside>
<main>
<section>
<article>: 여러가지 아이템들을 그룹화해서 재사용 가능한 요소들이 모아져 있는 것
<div>
<span>
<form>

[ITEM]

<a>
<button>
<input>
<label>
<img>
<video>
<audio>
<map>
<canvas>
<table>
<h1 ~ 6>
<ol>
<ul>
<li>
```

## Block vs Inline
>Block
>
>>한줄에 한칸을 전부다 쓴다

>Inline
>
>>텍스트박스만 공간을 차지하고 옆에 남은 공간이 있으면 다른 텍스트 박스가 들어올 수 있다

## Tap & Element
```
<p> My cat is very grumpy </p>
    ↗️
    content
 ⬆️                         ⬆️
opening tap               closing tag

태그 하나를 Element라고 부른다
```

## Attribute
```
<p class="editor-note"> My cat is very grumpy </p>
        ⬆️
    Attribute
```

## ol vs ul
```
<ol>
자동으로 숫자, 로마기호 등 순서가 있는 리스트로 작성된다

<ul>
기호가 들어가는 리스트지만 순서가 없는 리스트로 작성된다
```
