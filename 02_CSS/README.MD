# CSS (스타일 시트) 세부 내용

---------------------------------
## 1. 기본 선택자 
- 기본선택자 종류
  - 전체 선택자 (\*\) : HTML 페이지 내부의 태그를 모두 선택
  - 태그 선택자 (태그) :HTML 페이지 내부의 특정 태그를 모두 선택
  - 아이디 선택자 (#아이디) : 특정 id 속성이 있는 태그 선택,중복X 특정 태그 하나 선택
  - 클래스 선택자 (.클래스) : 특정 클래스가 있는 태그
<br>

<kbd>![기본 선택자 사진](https://user-images.githubusercontent.com/77951835/110293867-72f04080-8032-11eb-8257-b59b6dc86eca.JPG)<br></kbd>


[코드보기](https://github.com/guemin96/StudyHtml/blob/main/02_CSS/%EC%86%8D%EC%84%B1%20%EC%84%A0%ED%83%9D%EC%9E%90_test.html)

---------------------------------

## 2. 속성 선택자 
- 속성 선택자 형태
  - 선택자(속성) : 특정한 속성이 있는 태그 선택
  - 선택자(속성 = 값) : 특정한 속성 내부 값이 특정 값과 같은 태그 선택
  
<br>

<kbd>![속성선택자](https://github.com/guemin96/StudyHtml/blob/main/02_CSS/%EC%82%AC%EC%A7%84/2.%EC%86%8D%EC%84%B1%20%EC%84%A0%ED%83%9D%EC%9E%90.PNG)<br></kbd>


[코드보기](https://github.com/guemin96/StudyHtml/blob/main/02_CSS/%EC%86%8D%EC%84%B1%20%EC%84%A0%ED%83%9D%EC%9E%90_test.html)

---------------------------------

## 3. 상태선택자
- 상태 선택자
  - :checked : 체크 상태의 input 태그 선택
  - :focus : 포커스를 맞춘 input 태그 선택
  - :enabled : 사용 가능한 input 태그 선택
  - :disabled 사용 불가능한 input 태그 선택
<br>

<kbd>![상태선택자](https://github.com/guemin96/StudyHtml/blob/main/02_CSS/%EC%82%AC%EC%A7%84/%EC%83%81%ED%83%9C%20%EC%84%A0%ED%83%9D%EC%9E%90.PNG)<br></kbd>


[코드보기](https://github.com/guemin96/StudyHtml/blob/main/02_CSS/div_test.html)

---------------------------------

## 4. 구조선택자
- 구조 선택자
  - 홀수와 짝수 위치를 판별하고 스타일을 적용
<br>

<kbd>![구조선택자](https://github.com/guemin96/StudyHtml/blob/main/02_CSS/%EC%82%AC%EC%A7%84/7.PNG)<br></kbd>


[코드보기](https://github.com/guemin96/StudyHtml/blob/main/02_CSS/selector_struct_test.html)

---------------------------------

## 5. 박스 속성
- 박스 속성 종류
  - margin 속성 : 테두리와 다른 태그 사이의 테두리 바깥쪽 여백
  - border 속성 : 테두리
  - padding 속성 : 테두리와 글자 사이의 테두리 안쪽 여백, 배경색은 padding 영역까지만 적용
  - width 속성 : 글자를 감싸는 영역의 가로 크기
  - height 속성 : 글자를 감싸는 영역의 세로 크기
<br>

<kbd>![박스 속성](https://github.com/guemin96/StudyHtml/blob/main/02_CSS/%EC%82%AC%EC%A7%84/box.PNG)<br></kbd>


[코드보기](https://github.com/guemin96/StudyHtml/blob/main/02_CSS/box_test.html)

---------------------------------

## 5. 배경 속성
- 배경 속성 종류
  - background - image : 배경 이미지 삽입
  - background - size : 배경 이미지의 크기 지정
  - background - repeat : 배경 이미지의 반복 형태 지정
  - background - attachment : 배경 이미지의 부착 형태 지정
  - background - position : 배경 이미지의 위치 지정
  - background : 한 번에 모든 배경 속성 입력
<br>

<kbd>![배경 속성](https://github.com/guemin96/StudyHtml/blob/main/02_CSS/%EC%82%AC%EC%A7%84/8.PNG)<br></kbd>


[코드보기](https://github.com/guemin96/StudyHtml/blob/main/02_CSS/background_test.html)
