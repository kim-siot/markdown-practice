# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

물끄러미 바라보다 문득
뚫어질까 걱정했어
눈을 감는 순간도 아까워서 잠을
안 자니까 흐릿해져 가는걸

# 줄바꿈(Line Breaks)

처음엔 너에게 눈이 멀었고, 지금은 눈이 멀었지  
너무 컸던 너는 멀리 보면 작은 점이었지  
건조해진 관계엔 눈물이 절실했고<br />
너는 그걸 어리광이라고 표현하곤 했어

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄 기능은 제공되지 않음</u>  

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. (스페이스4번) 순서가 필요한 목록
    1. (들여쓰기2번) 순서가 필요한 목록
    - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com" title="구글로">Google</a>

[Google](https://google.com "구글로")

마크다운에서 target 속성은 제공하지 않으므로 a태그를 이용해야 함

# 이미지(Images)

이미지 삽입  
![타이틀](경로)  
이미지에 링크 삽입  
[![타이틀](경로)](https://google.com)


# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문자  
> (출처: 네이버)
>> 중첩된 인용문
>>> 중중첩된 인용문  
>>> 중중첩된 인용문


# 인라인(inline) 코드 강조

멀쩡한 게 아니라 `그동안 많이 참아왔던 거야`
눈이 `시뻘게질` 만큼 너를 사랑했던 거야
그때 너는 내게 정말 전부였던 거야

# 블록(blcok) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
<!-- html 코드 -->
```

```css
body {background-color: red;}
/* CSS 코드 */
```

```javascript
function func(){
    const f = 'fff';
    returan f;
} // javascript 코드
```

```bash
$ git commit -m '터미널 코드'
```

```plaintext
일반 텍스트 작성할 때 plaintext
```

# 표(Table)

Position 속성을 표로 만들어 보자.  
:(콜론)으로 정렬을 할 수 있다.

값 | 의미 | 기본값  
--|:--:|--:  
static | 기준 없음 | O
relative | 요소 자신 | X

# 원시 HTML(RAW HTML)

물끄러미 <u>`바라보다`</u> 문득
뚫어질까 걱정했어<br />
눈을 감는 순간도 <span style="text-decoration: underline">아까워서 잠을 안 자니까</span> 흐릿해져 가는걸

<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>

# 수평선(Horizontal Rule)

---
***
___