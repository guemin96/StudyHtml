# HTML 기본 학습

## 웹 페이지 기본 구조와 작성방법
태그, 요소, 속성에 의미 이해 및 HTML, CSS JS 작성방법 따라하기

## HTML5 기본 태그

### 제목 태그
```
<!Doctype html>
<html>
    <head>
        <title>HTML5+CSS Text</title>

    </head>
    <body>
        <h1>제목 글자 태그1</h1>
        <h2>제목 글자 태그2</h2>
        <h3>제목 글자 태그3</h3>
        <h4>제목 글자 태그4</h4>
        <h5>제목 글자 태그5</h5>
        <h6>제목 글자 태그6</h6>
    </body>

</html>

```
### 이미지, 음악 태그
```
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Page Title</title>
</head>
<body>
    <img src="media/image.jpg" 
    alt="우리의 추억"
    width="300">
    <br>
    <audio src="media/Kalimba.mp3" controls="controls"></audio>

</body>
</html> 

```

### 테이블 태그
```
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Page Title</title>
</head>
<body>
    <table border="1">
        <thead>
            <tr>
                <th></th>
                <th>월</th>
                <th>화</th>
                <th>수</th>
                <th>목</th>
                <th>금</th>

            </tr>

        </thead>
        <tbody>
            <tr>
                <td>1교시</td>
                <td>영어</td>
                <td>국어</td>
                <td>과학</td>
                <td rowspan="3">미술</td>
                <td>기술</td>


            </tr>
            <tr>
                <td>2교시</td>
                <td>국어</td>
                <td>도덕</td>
                <td>체육</td>
                <!-- <td>수학</td> -->
                <td>사회</td>

            </tr>
            <tr>
                <td>3교시</td>
                <td>국사</td>
                <td>수학</td>
                <td>사회</td>
                <!-- <td>영어</td> -->
                <td>음악</td>

            </tr>

        </tbody>
    </table>
</body>
</html>
```


## HTML5 입력 태그
[이전](https://github.com/guemin96/StudyHtml/tree/main/01_HTML)
