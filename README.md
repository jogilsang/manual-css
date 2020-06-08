# manual-CSS
for me


### HTML 기본
```html
<!DOCTYPE HTML>
<html>
<head>
    <title>HTML5 기본 구조</title>
    <meta charset="UTF-8" />
</head>
<body>
    <header></header>
    <nav></nav>
    <section></section>
    <aside></aside>
    <footer></footer>
</body>
</html>
```

### CSS 생성하는 법
```css
/* 2. 내부 스타일시트 */
<style type="text/css">
h1 {
   color : blue;
   text-align:center;
}
<style>

/* 3. 외부 스타일시트 */
<head>
    <link rel="stylesheet" href="/examples/media/expand_style.css">
    <link rel="stylesheet" type="text/css"
</head>

```

### CSS Syntax 
```CSS
   		h2 { text-decoration: overline; }
		h3 { text-decoration: line-through; }
		h4 { text-decoration: underline; }
		a { text-decoration: none; }

<h1>text-decoration 속성을 이용한 텍스트의 효과 설정</h1>
	<h2>텍스트에 윗줄을 만듭니다.</h2>
	<h3>텍스트를 통과하는 가운데 줄을 만듭니다.</h3>
	<h4>텍스트에 밑줄을 만듭니다.</h4>


```

### margin
```css
div.parent{
	height : 100px;
	margin-left : 100px;
}
div.child {
	background-color : #FFF8DC;
	margin-left : inherit;
}

div.desc {
	background-color : #FFF8DC;
	margin : 10px, 20px, 30px, 40px <!-- 위 10, 오른쪽 20, 아래 30, 왼쪽 40-->
	margin : 10px, 20px, 30px <!-- 위 10, 오른쪽 20, 아래 30, 왼쪽 20-->
	margin : 10px, 20px<!-- 위 10, 오른쪽 20, 아래 10, 왼쪽 20-->
	margin : 10px <!-- 위 10, 오른쪽 10, 아래 10, 왼쪽 10-->
	margin : auto <!-- 부모화면의 중앙-->
}

<div class="parent">
	<div class ="child"></div>
</div>

```

### outline
```css
<style>
    p { border: 1px solid black; }
    p.none { outline: 3px none teal; }
</style>
```


