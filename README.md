# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장 (Paragraoh)

마크다운에 대해서 배우는 중

# 줄바꿈 (Line breaks)

마크다운에 대해서 배우는중
마크다운에서는 두번의 띄어쓰기와 엔터로  
줄바꿈이된다. 그냥 <br /> 태그를 써도된다.

# 강조 (Emphasis)

_이텔릭_ 원하는 문장에 앞뒤로 언더바기호 기입
**두껍게** 이스터리스크로 감싸준다  
**_이텔릭 + 두껍게 _** 두개 한꺼번에  
~~취소선~~ 틸드로 감싸준다  
<u>밑줄</u>  

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록 (들여쓰기 두번)
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지않은 목록
- 순서가 필요하지않은 목록
- 순서가 필요하지않은 목록
    - 순서가 필요하지않은 목록
    - 순서가 필요하지않은 목록
- 순서가 필요하지않은 목록

# 링크 (Links)

<a href="http://google.com">GOOGLE</a>  
[GOOGLE](http://google.com)  
<a href="http://naver.com" title="NAVER로 이동!">NAVER</a>  
[NAVER](http://naver.com "네이버로 이동!")  
<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>   

# 이미지(Images)

![]()

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/css/images/logo.png)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)  

> 인용문을 작성하세요!  
>> 중첩된 인용문  
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 2  

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>

```html
<a href="https://www.google.co.kr/" 
target="_blank">GOOGLE</a>
```  

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```
```bash
$ git commit -m 'Study Markdown
```

```plaintext
그냥 텍스트
```

# 표(Table)
position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산이</span> <u>마르고</u> 닳도록</br>
하느님이 보우하사 우리나라 만세

# 수평선 (Horizontall Rule)

---

***
___