# 마크다운(Markdown) 문서

확장자.md 로 된 파일들
HTML (markup language) 대체 기능

1. 장점
    - 간편하고 쉽다.
    - 다양한 플랫폼에서 지원한다.
2. 단점
    - 표준이 없다.(따라서 표현 매채마다 좀 다르게 보일수 있다.)
    - 모든 HTML 태그를 대체 하진 못한다.

---

# 수평선
각기호를 3개이상 입력
---
***
___

# 줄바꿈 ( line break)
'두번 띄어쓰기' 나 `<br>`
로 사용하면 된다.

동해물과 백두산이 
마르고 닳도록 
하느님이 보우하사 
우리나라 만세

동해물과 백두산이 
마르고 닳도록 <br>
하느님이 보우하사 
우리나라 만세

# 이탤릭, 굵게

이탤릭은 *별표* 사용 혹은 _언더바_ 사용  

**이탤릭 굵게**  
~~취소선~~ 
<u>밑줄</u> `<u></u>`

# 목록
1. 순서가필요한 목록
1. 순서가필요한 목록
1. 순서가필요한 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록2
        - 순서가 필요하지 않은 목록2
        - 순서가 필요하지 않은 목록2

# 링크
[google](https://google.com)  
[github](https://github.com)

# 이미지
![대채텍스트](https://www.w3schools.com/html/pic_trulli.jpg)

[![대채텍스트](https://www.w3schools.com/html/pic_trulli.jpg)](https://www.naver.com)

# 코드강조
### 인라인 코드강조
`background` 혹은 `background-image`속성으로 배경이미지 삽입  

### 블럭 코드 강조
` 를 3번 이상 입력하고 코드 종류도 적습니다.  

```html
<a href="hppts://www.naver.com" target="_blank">네이버</a>
```

```css
.list > li {
    position: absolute;
    top: 40px;
}
```

```java
public static void myFunc(int n, String str){
    System.out.println("hello world");
}
```

# 테이블 (표)
`<table>` 로 변환
|aa|bb|
|--|--|
|1|2|
|3|4|

### 열병합

|col1|col2|col3|col4|
|----|----|----|----|
|no span|span     |||


|값|의미|기본값|
|---|:---:|---:|
|static|배치|1|
|static|배치불가|11|
|static|배치불가불가|111|

# 인용문
>남의 말이나 글에서 직접 따온 문장

>인용문 작성
>>중첩 인용문
>>>중중첩