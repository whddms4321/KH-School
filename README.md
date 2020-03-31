# HTML
  - 화면구면
  

1. web Version

  - web 1.0
    - 정적인 검색 서비스 (초기)
    - 동적인 검색 서비스 제공(현재 가장 많이 사용)   동적인 검색 및 사용자의 참여,공유, 개방  

  - web 2.0  
    - 지능형 웹서비스
    - 사용자의 패턴을 분석하여 개인별 맞춤 정보 검색 서비스 제공 1>2로 넘어가는중..

2. HTML(Hyper Text Markup Language)
  - 웹에서 정보를 표현할 목적으로 만든 마크업 언어
  
3. HTML5 의 특징
  1. 구조적 설계 지원(시멘틱 태그)
    시멘틱 이름만 보고도 역할을 짐작할 수 있는것
  2. 그래픽 및 멀티미디어 기능 강화
  3. CSS3/JAVAScript 지원
  4. 다양한 API 제공
  5. 모바일 웹 지원 / 장치 접근 가능(배터리정보,카메라,GPS 등)
  6. 인터넷이 연결되지 않은 상태에서도 어블리케이션 동작

4. HTML의 구성 요소
  - <p align = 'center'> HTML/CSS </p>  
  시작태그 속성     속성값    내부문자  종료태그    
    
  |구성요소|설명
  |:----:|:----:|
  |태그|<와>로 묶인 명령어 시작태크와 종료태그가 한쌍으로 이용|
  |요소|시작태그와 종료태그로 이루어진 모든 명령어 하나의 html문서는 요소들의 집합|
  |속성|요
  
5. HTML 주의사항
  1. 태그는 대소문자를 구분하지 않음(소문자 권장)
  2. 시작태그로 시작하면 반드시 종료태그로 종료
    - 종료태그가 없는 일부 태그를 제외하고는 반드시 종료해야함
  3. 파일 확장자는 반드시 html, htm으로 설정
  4. 문자의 공백은 한 개만 인식
    - 공백을 추가로 하기위해선 특수기호를 사용 (&nbsp;)등
    

**HEAD**    

```  
<table> : 테이블 표를 생성함
<tr> : 테이블의 한 행을 삽입해줌
<td> : 테이블의 내용..
<th> : 열의 제목을 표시하는 테그
<caption> 
<border> 태그의 속성으로 표의 테두리 두께를 조절
<rowspan> 과 <colspan> 테그의 속성으로 지정한 행만큼 병합하거나 열을 병합
</table> : 테이블을 닫음
```  

  




**영역 테그**

|속성|설명|
|:---|:----:|
|width/height|페이지 크기 설정|



__블록요소__

- 한줄 전채를 차지하는 요소로 한 줄에 여러 요소가 올 수 없음
- 기본적으로 가로폭 전체의 넓이를 가지는 직사각형 형태의 요소
- 자동으로 줄이 개행되며, 크기조절이 가능
- 블록요소는 모든 인라인 요소를 포함할 수 있고 다른 블록요소도 포함이 됨
- 제목테그(h1~h6), 목록태그, 테이블태그 .. 등


__인라인요소__

- 내부의 컨텐츠가 끝나는 지점까지를 넓이로 가지게 되며, 한줄에 여러 요소가 올수 있음
- 자동으로 줄이 개행되지 않으며, 한줄에 여러 요소가 오기에 크기조절 불가
- 반드시 블록요소 안에 포함되어 있음



- 글자 형식 테그.. 등등
```
<div> </div>  
block 형식의 공간을 분할(수직으로 공간 분할)  
```
```
<span></span>  
  - inline 형식의 공간을 분할(수평으로 공간 분할)
```  
  
__시멘틱 태그__

- 페이지 구조를 특정 기능에 맞는 태그를 사용하여 구분
- 페이지 구조를 쉽게 파악하고 좀 더 정확한 정보를 검색 할 수 있게됨

  1. <header> </header>  
    - 특정부분의 머리말로 쓰임  
  2. <nav>
  
  3. <article> </article>  
    - 웹 페이지의 내용이 들어가는 영역
    - 이 태그 영역은 다른곳으로 배포하거나 재사용 가능
    


__멀티미디어 태그__

|이미지확장자|설명|
|:-----:|:----:|
|GIF|파일 크기가 작아 작은 아이콘이나 블릿 기호에 많이 사용 투명한 배경이나 움직이는 이미지를 만들수 있음|
|JPG/JPEG|사진을 위해 개발,저장을 반복하다보면 화질이 떨어질수 있다.|
|PNG|네트워크용으로 개발되어 최근 많이 이용|   
  
  - **최근 벡터 이미지인 SVG확장자의 활용빈도도 높아지고 있다.**  
  
 - http://maschek.hu/imagemap/imgmap/ 수업용 사이트
 
 
 <audio> </audio>  
 
 <video></video>
  - 웹 브라우저에서
  
  
**하이퍼링크 태그**  

<a></a>
  - 
  
**폼 태그**  
  
<form></form>  
  - 사용자가 력한 data를 보내는 방식과 처리할 프로그램을 정하는 태그  
  
|속성|설명|
|:--|:---|
|method|get:url창에 데이터를 보내는 방식,   
|name|<form>태그의 고유이름지정(<form>을 구분하기위함)|
|action|데이터를 처리할 프로그램(페이지)지정|

<input>  

  - 사용자로부터 데이터를 입력받기 위한 태그  
  - form 태그를 통해서 데이터 전송 시 해당 form 태그 내부에 있는 input 태그에 작성된 내용만 전송  
  
|속성|설명|
|:--:|:--|
|hyper|ㅁㅁ|




## CSS

style과 stylesheet  
  
  - style은 정해진 속성을 입력하여 웹페이즈를 꾸미는 것  
  - stylesheet는 웹페이지에서 반복적으로 쓰는style을 모아 놓은 것  
```
 P { color : red;  }  
```   
 선택자  속성  값  
 
 
 
stylesheet 종류  

  1. 내부 스타일 시트
    - html문서 내부의 <style></style>에 스타일 정보를 저장하는 방법
    
    
- 선택자

__CSS 단위 구성__

<table>
  <tr>
    <th>구분</th>
    <th>단위</th>
    <th>내용</th>
  </tr>
  <tr>
    <td rowspan="3">상대 크기<td>
    <td>
</table>
      
      
      
  <table>
    <tr>
      <th>표현방법</th>
      <th>내용</th>
    <tr>
    <tr>
      <td>영문색 이름</td>
      <td>영문으로 색 이름 작성<br>red,white,blue...</td>
      <td>16진수 표현</td>
      <td>rgb값을 기준으로 16진수로 작성<br></td>
 </table>   
    
    
 - font-family  
    - 폰트의 글꼴을 설정해주는 속성
    - 글꼴 이름1이 없으면 글꼴2,글꼴3으로 선택되어 설정
    - 글꼴이 모두 없으면 브라우저 기본 글꼴로 적용

    ```
    기본형식
    선택자 {
      font-maily:글꼴1[, 글꼴2,글꼴3];
    }
    ```   

 - font-size  
    - 글자의 크기를 조절하는 속성
    - 단위 : em,px,pt,ex   

    & ex:현재 소문자 x의 배수의 크기를 설정

    |속성 값|내용|
    |:--:|:--:|
    |normal|기본형태|
    |bold|굵게 표시|
    |bolder|더 굵게 표시|
    |lighter|더 가늘게 표시|
    |100~900|굵기의 정도를 숫자로 표시|

 - font-variant  
    - 영어를 작은 대문자로 표시해 주는 속성
    ```
    선택자 {
      font-style:normal 또는 italic 또는 oblique;
    }
- font-style  
  - 글자를 이텔릭체로 표시하는 속성
  ```
  선택자 {
    font-style  
    
텍스트 스타일
  
  color 
    - 글자색을 하는 속성
    
  text-decoration
  
    - 글자에 밑줄을 긋거나, 취소선을 긋거나, 윗선을 긋거나 밑줄을 표시하지 않는 속성
    
  ```
  선택자 {
    text-decoration: 속성값;
  }
  ```
  
  text-shadow   
    - 텍스트에 그림자 효과를 주는 속성
    
  ```
  선택자 {
    text-shadow: none 또는 (가로 또는 새로번짐 색상);
  }
  ```   
  
  white-space  
    - 공백을 리해 주는 속성   
  
  text-align  
    - 
    
  text-overflow
    - 영역을 벗어나는 텍스트 표시 속성
  
  
  [HTML](#HTML)color
