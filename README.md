# 제목(Header)

# 제목 1
## 제목 2
### 제목 3



# 문자(Paragraph)

안녕하세용 스타벅스 용인상하DT점 바리스타
고나우 입니다.



# 줄바꿈(Line break)

## 띄어쓰기는 줄바꿈(스페이스바)2번 혹은 <>br 태그

안녕하세용 스타벅스 용인상하DT점 바리스타  
고나우 입니다. 고나우(Gonow)가 무슨뜻이냐구요?<br>
구글에 검색 해보세요.



# 강조(Emphasis)

1. _이텔릭_
2. **두껍게**
3. **_이텔릭 + 두껍게_**
4. ~~취소선~~
5. <u>밑줄</u>



# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 들여쓰기 2번을 했을때
    1. 들여쓰기 2번을 했을때
    1. 들여쓰기 2번을 했을때  
1. 뭐야 1만 썼는데 왜 순서대로 나와


- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록(서브)
    - 순서가 필요하지 않은 목록(서브)
- 순서가 필요하지 않은 목록



# 링크(Link)

### 방법1
<a href="https://google.com">구글</a>

[구글](https://google.com)

### 방법2(타이틀)
<a href="https://naver.com" title="네이버로 이동">네이버</a>

[네이버](https://naver.com "네이버로 이동")

### 방법2(타켓)
<a href="https://youtube.com" 
title="유튜브로 이동"
target="_blank">유튜브</a>

markdown에서 타켓은 불가능



# 이미지(Image)

### 일반이미지
![GOOGLE](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)

### 링크 이미지
[![GOOGLE](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](https://google.com)


# 인용문(BlockQuote)

> 대충 검은바탕에 몇마디 적으면 명언같다  
>(간디)

>수정안 제출
>>수장안 제출ver.2
>>>최종 수정안 제출
>>>>진짜 마지막 수정



# 인라인(Inline) 코드 강조

안녕하세용 스타벅스 용인상하DT점 바리스타  
`고나우` 입니다. `고나우(Gonow)`가 무슨뜻이냐구요?<br>
구글에 검색 해보세요.



# 블록(Block) 코드 강조

```html
<a href="https://youtube.com"
target="_blank">유튜브</a>
```

```css
 div {
  background-color: red;
  border: 1px solid gray;
  }
```

```javascript
  function sum(a, b) {
    return a + b;
  }
```

```bash
  $ git commit -m '수정안'
```

```plaintext
안녕하세용 스타벅스 용인상하DT점 바리스타  
고나우 입니다. 고나우(Gonow)가 무슨뜻이냐구요?
구글에 검색 해보세요.
```



# 표(Table)

position 속성
값 | 의미 | 기본값
:--:|:--:|:--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치상 부모 | X
fixed | 뷰포트 | X



# 원시 HTML(Raw HTML)

안녕하세용 스타벅스 용인상하DT점 바리스타  
<u>고나우</u> 입니다. <br>
고나우(Gonow)가 무슨뜻이냐구요?
구글에 검색 해보세요.

<img width="100" src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png">



# 수평선(Horizontal Rule)

---
안녕하세요

***
반값습니다
___
저는 백우혁 입니다.