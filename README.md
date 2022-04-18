# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4

<!-- # 갯수에 따라서 h1~h6 -->


# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)
<!-- 띄어쓰기 두번 or <br/> -->


동해물과 백두산이 마르고 닳도록<br>  하느님이 보우하사 우리나라 만세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    <!-- 들여쓰기2번 -->
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="네이버로 이동">NAVER</a>

[NAVER](https://naver.com "네이버로 이동") 

 <!-- 마크다운은 target 속성은 제공X -->

 # 이미지(Images)
 <!-- 링크와 이미지는 !여부의 차이 -->
![HEROPY](https://heropy.blog/css/images/logo.png)

<!-- 이미지에 링크 -->
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog)

#  인용문(BlockQuote)

>남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
>(네이버 국어사전)

>인용문의 중첩기능
>>중첩1
>>>중첩2

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

<!-- 백틱 3번 -->

```html
<a href="https://google.com">GOOGLE</a>
```

```plaintext
동해물과 백두산이
```

# 표(Table)

position 속성
<!-- 몸통 머리 구분과 정렬기능 -->
값 | 의미 | 기본값
:--:|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치상 부모 | X

# 원시 HTML(Raw HTML)

동해물과<br>
백두산이<br>
<u>마르고 닳도록</u>


<!-- a 태그의 target 속성이나
img의 width 속성 등은 html을 사용해야 한다 -->

# 수평선(Horizantal Rule)

---

***

___

