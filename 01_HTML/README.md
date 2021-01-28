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

### 텍스트, 파일 ,체크박스, 라디오버튼, 보이지 않는 양식, 버튼, 선택스크롤 코드
```
<form>
        <!-- 사용자가 입력하는 양식 -->
        <input type="text" name="userid" value="guemin96"><br>
        <input type="password" name="password" value="12345"><br>
        <input type="file" name="attach_file" ><br>
        <input type="checkbox" name="chk_hobby_swim" value="수영">수영<br>
        <input type="checkbox" name="chk_hobby_maraton" value="마라톤">마라톤<br>
        <input type="radio" name="rdo_gender" value="M">남자
        <input type="radio" name="rdo_gender" value="F">여자
        <input type="radio" name="rdo_gender" value="G">중성<br>
        
        
        <input type="datetime" name="dt_today" value="2021-01-28"><br>

        <!-- 보이지 않는 양식 -->
        <input type="hidden" name="hdn_temp_val" value="2323232323"><br>


        <!-- 버튼 -->
        <input type="button" name="btn_normal" value="click"><br>
        <input type="reset" name="btn_reset" value="reset"><br>
        <input type="submit" name="btn_reset" value="제출"><br>
        
        <!-- 기타 -->
        <input type="image" name="" src="http://placehold.it/400x250"><br>
        
        <!-- 선택컨트롤(콤보박스/드랍다운) -->
        <select>
            <option>김밥</option>
            <option>떡볶이</option>
            <option>오뎅</option>
            <option>순대</option>
            <option>튀김</option>
        </select>


    </form>


```
### div 태그와 span 태그(공간분할 태그!)
<!-- div는 세로로 span은 가로로>
```
<body>
    <div>div태그 - 블록형식</div>
    <div>div태그 - 블록형식</div>
    <div>div태그 - 블록형식</div>
    <div>div태그 - 블록형식</div>
    <div>div태그 - 블록형식</div>

    <span>span태그 - 인라인형식</span>
    <span>span태그 - 인라인형식</span>
    <span>span태그 - 인라인형식</span>
    <span>span태그 - 인라인형식</span>
    <span>span태그 - 인라인형식</span>
    <span>span태그 - 인라인형식</span>
</body>

```

### 시멘틱 태그
<!-- header,nav,aside, section,article,footer>

```
<header>
        <h1>공간분할 테스트</h1>
    </header>
    <nav>
        <ul>
            <li>
                <a href ="#">메뉴1</a></li>
                <a href ="#">메뉴2</a></li>
                <a href ="#">메뉴3</a></li>
                <a href ="#">메뉴4</a></li>
                <a href ="#">메뉴5</a></li>
            </li>
        </ul>
    </nav>
    <section>
        <article></article>
        <h2>Lorem ipsum dolor sit amet </h2>
        <p>consectetur adipisicing elit. Similique sed ea inventore at placeat necessitatibus ut temporibus! Cum non voluptate facilis, qui id modi culpa quibusdam, quasi doloribus earum atque?</p>

        <article></article>
        <h2>Lorem ipsum dolor sit amet </h2>
        <p>consectetur adipisicing elit. Similique sed ea inventore at placeat necessitatibus ut temporibus! Cum non voluptate facilis, qui id modi culpa quibusdam, quasi doloribus earum atque?</p>

        <article></article>
        <h2>Lorem ipsum dolor sit amet </h2>
        <p>consectetur adipisicing elit. Similique sed ea inventore at placeat necessitatibus ut temporibus! Cum non voluptate facilis, qui id modi culpa quibusdam, quasi doloribus earum atque?</p>

    </section>
    <footer>
        <address>부산 해운대구 좌동 삼성아파트</address>
    </footer>
```



[이전](https://github.com/guemin96/StudyHtml/tree/main/01_HTML)
