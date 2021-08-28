# frontend_0814

## 참고링크

https://github.com/

https://codesandbox.io/

www.w3schools.com

https://opentutorials.org/course/1

https://github.com/edu-ministori/frontend_08 > 선생님 github주소

https://codesandbox.io/s/itac-08-0ye9v?file=/index.html > 선생님 csb 주소

https://www.dbcut.com/bbs/index.php > 홈페이지 샘플들 볼 수 있는 사이트

## HTML

> 기본구조 만들 때 html:5 + tab 하면 됨

### Introduxtion

https://www.w3schools.com/html/html_intro.asp

> 웹 페이지 구조 표시

> 웹 페이지 컨텐츠 표시
>
> - 텍스트 콘텐츠
> - 멀티미디어 콘텐츠 : 이미지, 비디오, 오디오 등
>   <br>

### HTML Basic

> 기본 구조 Example Link : https://www.w3schools.com/html/html_intro.asp > <br>

### HTML Elements

> https://www.w3schools.com/html/html_elements.asp

`(backtick)

```
<tagname> 첫번째 수업 </tagname>
* 시작태그만 있는 경우 : Empty Element
```

> 포함관계(nested)

```
<html>
  <body>
    <h1>Heading</h1>
  </body>
</html>
```

> html-body-h1 관계<p>
>
> > html : body와의 관계 - 부모요소 / h1과의 관계 - 조상요소<p>
> > body : html과의 관계 - 자식요소 / h1과의 관계 - 자식요소<p>
> > h1 : body와의 관계 - 자식요소 / html과의 관계 - 자손요소
> > <br>

### HTML Attributes

> https://www.w3schools.com/html/html_attributes.asp<br>
> {X = 'Y'} ▶ 이 묶음을 '속성'이라고 한다.<br>
> Y값은 Value, X값은 name 이라고 한다.
> <br>

### HTML Headings

> h1~h6 : 제목태그 (h > heading)
> <br>

### HTML Paragraphs

> https://www.w3schools.com/html/html_paragraphs.asp > <br>

### HTML Links

> https://www.w3schools.com/html/html_links.asp

```
<a href="url">link text</a>
```

> a : anchor
> URL(Uniform Resource Locator) : 파일식별자(위치표시), 가장 넓은 의미의 인터넷 주소<br>

> 인터넷 주소<br>
>
> - IP(Internet Protocol) : 숫자로 구성된 주소 (ex) 192.168.0.1) \*원래주소
> - Domain Name : www.naver.com \*www가 서버를 나타냄!
> - ex) blog.naver.com/blog/123456 >> 서버 주소 + 상세 도메인 => url
> - 절대url 과 상대 url의 차이 알기
>   <br>

### HTML File 경로

https://www.w3schools.com/html/html_filepaths.asp

절대 vs 상대

- 경로 위치 표시 방식
- 경로 표시 기준의 변경 여부
  > 1. 절대경로
- ex) 대한민국 서울특별시 서초구 ~ 동 대호빌딩 801호 (절대경로방식)
- 도메인주소 + 상세경로까지 있는 url을 절대경로라고 한다.
- ex) https://www.naver.com/blog/image/jpg
  > 2. 상대경로
- ex) 강남역 11번 출구에서 3분 대호빌딩 (상대경로방식 - 출발지 위치를 기준으로 표기)
- 가능한 경우 상대 파일 경로를 사용하는 것이 가장 좋습니다.
- ex) /blog/image.jpg 혹은 image/jpg

  # frontend_0821

  ### HTML Link Bookmark

  https://www.w3schools.com/html/html_links_bookmarks.asp <br>
  컨텐츠의 양이 적을 때에는 원페이지 사이트로 북마크를 주기도 함

  ### HTML List

  https://www.w3schools.com/html/html_lists.asp <br>
  복잡한 목록의 경우 같은수준 상위항목 > 같은수준 하위항목 순서로 코드를 입력하는 방법이 좋습니다.

  > 중첩목록(Nested List)

  ### HTML Tables

  https://www.w3schools.com/html/html_tables.asp <br>
  Table generator : https://www.tablesgenerator.com/html_tables <br><br>
  요즘에는 모바일 반응형까지 고려하여 코드를 짠다. but table은 가로로 좁아지는 형태만 가능함 (table은 많이 쓰이지 x)

  ### HTML Images

  > alt attribute : alternative 의 약자로, 이미지가 화면에 보이지 않을 때 나타나는 텍스트 & 웹 접근성을 위함\

  ### HTML Videos

  https://www.w3schools.com/html/html_media.asp
  https://www.w3schools.com/tags/tag_video.asp <br>
  muted & autoplay 쓸 때에는 muted를 반드시 앞에 써야함<br><br>

  & > 공백 여러개 띄우고 싶을 때 하는 것

  ### HTML Forms

  https://www.w3schools.com/html/html_forms.asp

  ### HTML Entity code

  https://www.w3schools.com/html/html_entities.asp

  > 주로 쓰이는 7가지는 기억하는게 좋다.

  ### 새로운 CSS 페이지 만들기

  https://freebiesbug.com/psd-freebies/website-template/
  https://www.photopea.com

  > UI 분석하기 EX) 02_Home.jpg

  ### HTML Semantics

  https://www.w3schools.com/html/html5_semantic_elements.asp <br>
  가장 많이 쓰이는 레이아웃 관련 Semantics 요소는 기억하는게 좋다.

  > header, nav, section, article, aside, footer (그림 참고하기)

  ### HTML Block and Inline Elements

  https://www.w3schools.com/html/html_blocks.asp

  > 영역의 특성

  > - 블럭요소 : 가로길이 - 부모에 채워짐 / 세로길이 - 자식요소에 맞춰짐
  > - 인라인요소 : 가로길이와 세로길이 모두 자식요소에 맞춰짐
  > - 예외 : a - 인라인 요소이지만 블럭 요소를 포함 가능

  > 화면에 표시되는 디자인적 구분에 따라 blocks 또는 inline 요소로 나눈다.
  > div tag > 아무런 의미 없이 나눌 때 / 디자인적 구분 요소이다.
  > span tag > div tag와 반대되는 태그로, 줄 바꿈x & 전체공간 차지 x. (옆으로 나열됨)

  > <b>포함관계</b>

  > - 블럭요소 : 다른 블럭요소, 인라인 요소와 컨텐츠를 포함할 수 있다.
  > - 인라인요소 : 다른 인라인 요소와 컨텐츠를 포함할 수 있다. (블럭요소는 포함x)
  > - 예외 : a - 인라인 요소이지만 블럭 요소를 포함할 수 있다.

  > figure 요소 : 그래픽 요소를 감쌀 때 사용한다.

### HTML id & Class Attributes

https://www.w3schools.com/html/html_id.asp
https://www.w3schools.com/html/html_classes.asp

> id attributes
>
> - id 속성이 붙는 이름은 한 문서 안에서 고유해야 함 (한 번만 사용 가능함) \* 화면상 오류는 없음
> - id는 한 대상의 html element에 하나의 이름만 지정할 수 있음 \* 화면상 오류 있음

> class attributes
>
> - class 속성이 붙는 이름은 한 문서 안에서 여러번 중복 사용할 수 있다.
> - class는 한 대상의 html elements에 여러개의 이름을 지정할 수 있음
> - class는 여러거 만들어 놓고 각 elements마다 필요한 class를 여러개 넣어서 쓸 수 있는 것이다.

★숙제 : https://ko.wikipedia.org/wiki/HTML 해당 페이지 만들어보기

## CSS

### CSS 구문

https://www.w3schools.com/css/css_syntax.asp

> Selecter { Property : Value; } // 중괄호를 > Decoration 이라고 한다.

> 선언 블록에는 세미콜론으로 구분된 하나 이상의 선언이 있을 수 있다.

### CSS How to

https://www.w3schools.com/css/css_howto.asp

> internal 방식을 쓰는 것은 권장하지 않음.

> 자바는 자바, css는 css, html은 html 코드만 넣어서 개별 파일로 작업한는 것이 좋다.

### CSS Selectors

https://www.w3schools.com/css/css_selectors.asp

> simple selector 를 잘 활용하는 것이 중요하다.

### CSS Comments

https://www.w3schools.com/css/css_comments.asp

### CSS Text

> 단락의 개념
> https://www.w3schools.com/css/css_text.asp

> p = color : 글꼴 색 바꾸는 것
>
> p = text-align : 텍스트 정렬 변경하는 것
>
> p = line-hight : 텍스트의 줄높이를 변경하는 것 (배수로 표시하는게 좋음 > 폰트 사이즈 변경에 대비)
>
> p = letter-spacing : 자간을 변경하는 것
>
> p = white-space : 줄바꿈을 제어하는 것 (줄바뀌지 않게 하는 것 > 가로스크롤만 생기게 하는 것)

### CSS 상속

> 부모요소에 적용된 CSS 속성이 자식요소에 적용되는 것

### CSS Font

> 글자 자체에 대한 성질
> https://www.w3schools.com/css/css_font.asp

> serif : 명조체

> sans-serif : 고딕체

### CSS web Font

> 웹에서 사용하는 폰트는 브라우저에서 랜더되기 때문에 기존에는 사용자 pc에 설치되어 있는 폰트를 사용함.<br>
> 사용자 pc에 있는 폰트를 찾지 않고, 서버에 폰트를 저장해서 사용하는 방식 > 웹폰트 방식<br>

> 웹폰트 서비스
>
> - 구글폰트 (영문 + 한글) https://fonts.google.com/?subset=korean
> - 눈누폰트 (한글) https://noonnu.cc/

### font-family

> 항상 폰트 목록 끝에 기본 폰트 이름을 입력해야 한다.
>
> - 고딕 : sans-serif / 명조 : serif
>
> font-size
>
> font style : italic > 폰트 기울임체
>
> font-weight
>
> - 100,200,300 ... : 숫자로 표시

### CSS Link

https://www.w3schools.com/css/css_link.asp

> a : link >> 보통 상태 , 아직 클릭하기 전의 상태
>
> a : visited >> 이미 클릭한 링크일 경우
>
> a : hover >> 마우스 오버 했을 때
>
> a : active >> 누리는 동작 (클릭하고 클릭을 떼었을 때 ! )
>
> Link 사용을 위한 규칙
>
> - 위 4가지 상태 항목을 모두 써야하는 규칙이 있지만, 기본 a태그에 대한 서식을 정해두고, <br>

    그 아래에 상태 항목을 추가해 나가는 방식으로 하면 된다.

> \*\* 기존 html 코드가 가지고 있는 css적 요소를 제거하고 새로 css 적용을 하기 위해 리셋 가능하다.
> https://meyerweb.com/eric/tools/css/reset/

### CSS Image

> 이미지의 크기 변경하기 (나중에 다시 설명)

### CSS Box Model (각 요소별 박스모델을 만들고 해당 박스를 레이아웃 하는 것.)

https://www.w3schools.com/css/css_boxmodel.asp

> - content : width or height (컨텐츠의 높이나 너비가 되는 것)
> - padding : 안쪽 여백
> - border : 테두리
> - margin : 바깥 여백

### CSS Height and Width

https://www.w3schools.com/css/css_dimension.asp

> - 블럭요소의 가로길이와 세로길이 적용시
> - auto : 요소의 기본 특성을 따라간다. / 디폴트 값 (적용하지 않은 상태와 같음)
> - px : px 값으로 고정된 크기를 가짐
> - % : 부모요소를 기준으로 특정 비율만큼 설정<br>

        (hight 는 %가 쓰이지 않음. 자식요소에 맞춰지는 속성이기 때문에)

> - 인라인 요소의 가로길이 / 세로길이는 적용되지 않은 ex) span 에는 적용 안됨 > > > 꼭 알고 가야 하는 기본 배경
>   영역의 특성
>
> - 블럭요소 : 가로길이 - 부모에 채워짐 / 세로길이 - 자식요소에 맞춰짐
> - 인라인요소 : 가로길이와 세로길이 모두 자식요소에 맞춰짐
> - 예외 : a - 인라인 요소이지만 블럭 요소를 포함 가능

## padding

> - padding-top / padding-right / padding-bottom / padding left
> - padding : 10px 20px 30px 40px;
> - padding : 10px 20px 30px;
> - padding : 10px 20px;
> - padding : 10px;

## margin

> 마진 겹침 : 박스의 마진이 상하배치 되어있을 때 마진이 한쪽만 적용되는 현상
>
> - 두 박스 모두 마진 적용하지 않고 한쪽에만 마진을 적용하게 한다.

## border

> border : 1px solid red;
>
> boder-top / boder-right / boder-bottom / boder-left

## background

https://www.w3schools.com/css/css_background.asp

> background-image : url() \*괄호가 들어가는 걸 함수 라고 한다.
>
> background_color

## color 표현방식

> RGB : red & green & blue - 가산 총합
>
> - 스크린에서 color 표현 (색을 섞을수록 밝아짐)
>
> CMYK : cyan & magenta & yellow & black - 감산혼합
>
> - 프린터에서 color 표현 (색을 섞을수록 어두워짐)
>
> color 코드 값
>
> - 10진수 표현 : rgb (255, 255, 255) \*0-225
> - 16진수 표현 : #1a9cf0
>   색 찾는 방법 : color picker

## box-sizong

> box-sizong : border-box => width 가 전체 박스의 가로 길이가 된다.
