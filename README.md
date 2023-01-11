# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6 
  
  
# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  

# 줄바꿈 (Line Breaks)  
띄어쓰기 (스페이스 십) 두 번 해주거나
html의 비알 코드를 써준다.  

# 강조 (Emphasis)

_이탤릭_ 

**두껍게**  

**_이탤릭 + 두껍게_**

~~취소선~~ (물결표시 앞뒤로 두번씩)

밑줄 (원래 지원되지 않음. 따라서 유태그 쓰고 그 안에 밑줄)  
<u>밑줄그어라</u>
  
# 목록(list)

1. 순서가 필요한 목록
1. 순서가 필요한 목록 
1. 순서가 필요한 목록  
    1. 새로운 들여쓰기 목록  
    1. 스페이스바로 4번정도 들여쓰기로 했다.
1. 중간의 목록을 지워도 알아서 넘버링 해준다. 

- 순서가 필요하지 않은 목록
- 순서가 없을 땐 하이픈을 붙여서 하면
- 알아서 점으로 정리해준다.
    - 서브목록은 이렇게 만들었다.  
- 들여쓰기할 경우는 마찬가지로 들여쓰기를 하면 서브목록 생성

# 링크(Links)

<a href ="https://google.com"> GOOGLE </a>

이 내용을 마크다운에는
[GOOGLE](https://google.com)

<a href="www.naver.com" title="naver로 이동">NAVER</a>  
이것을 마크다운으로 나타낼 때는  
[NAVER](www.naver.com "naver로 이동")  

그러나 하이퍼링크에서 새로운 탭으로 열도록 하는 target="_blank"에 해당하는 마크다운 방법이 없음  
그래서 a 태그로 target="_blank"를 써줘야 한다.  
  
  # 이미지 (images)

![그림의 대체 텍스트](링크주소) 
느낌표를 반드시 추가해야 한다.
예시  
![내 아바타](https://avatars.githubusercontent.com/u/119927752?v=4)  
  

# 인용문(Citation)

남의 말이나 글에서 직접 또는 간접으로 따온 문장.
네이버 국어 사전  
  
  이것을 인용표시처럼 나타내고자 할때는 아래와 같다.  

 > 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
 > (네이버 국어 사전)

 중첩기능도 있다.

 > 중첩기능입니다.
 >>중첩하려면 이렇게.
 >>>꺽쇠를 계속 해서 써줍니다.
 >>>그러면 중첩된다.  

 # 인라인(Inline) 코드 강조  
 CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있다.
백틱기호로 쳐주면 강조가 된다.

# 블록(blcok) 코드 강조  

<a href="http://www.google.com" target="_blank">GOOGLE</a>  

이것은 a링크로 연결했다. 그러나 순수하게 코드라는 개념으로 나타내고 싶은 경우 아래처럼.

```html
<a href="http://www.google.com" target="_blank">GOOGLE</a>  
```  

```bash
$ git commit -m 'study markdown'
```  

```css
 .body {
  background-color: #fff;
  font-weight: 700;
  color: #333;
 }
```  
```plaintext
동해물과 백두산이 마르고 닳도록 하느님이 보우하사
우리나라 만세
```  

# 표(table)
  
  position 속성 -기본은 왼쪽 정렬  
  (왼쪽, 가운데, 오른쪽 정렬)
    
  값 | 의미 | 기본값
  --|:--:|--:|
  static | 기준 없음 | O
  relative | 요소 자신 | X
  absolute | 위치상 부모 요소 | X
  fixed | 뷰포트 | X  
 ___   
# 원시 HTML(Raw Html)
  
동해물과 <u>백두산이</u> 마르고 닳도록 하느님이 </br>
보우하사 우리나라 만세  
  
또 다른 예는 a 태그에서 target="_blank"를 입력하고 싶은데 안되기 때문에, 원시적으로 a 태그를 전부 써준다.  
  
또 이미지 태그에서도 넓이를 입력하고 싶은데, 마크다운에서는 그걸 할수가 없다. 따라서 코드로 모두 써줌.
<img width="70" src="주소주소" alt="설명">
  
 ---   
# 수평선(Horizontal Rule)
---
하이픈 3번. 또는 별표시 3번
***
또는 언더바 기호 3번 입력
___













