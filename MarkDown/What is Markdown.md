# 마크다운(MarkDown) 이란

마크다운은 텍스트 기반의 경량 마크업 언어로서 다양한 장단점을 가지고 있습니다.

## 장점


간단하고 쉬운 문법: 마크다운은 간단하고 직관적인 문법을 가지고 있어 누구나 쉽게 배우고 사용할 수 있습니다.<br>
플랫폼 독립적: 마크다운은 플랫폼에 독립적이며, 모든 텍스트 에디터나 온라인 플랫폼에서 지원됩니다.<br>
가독성: 일반 텍스트로 작성되기 때문에 가독성이 뛰어나며, 원본 텍스트를 읽거나 수정하기가 용이합니다.<br>
빠른 작성: 복잡한 형식이나 디자인을 신경 쓰지 않고 빠르게 문서를 작성할 수 있습니다.<br>
버전 관리 용이성: 텍스트 기반이기 때문에 버전 관리 시스템(예: Git)과 같은 도구를 사용하여 쉽게 문서의 변경 이력을 관리할 수 있습니다.<br>

## 단점


디자인 제약: 마크다운은 주로 간단한 문서 작성에 적합하지만, 복잡한 디자인 요구사항을 충족시키기에는 제한적입니다.<br>
고급 기능 부재: 마크다운은 주로 텍스트 포맷팅을 위한 기본 기능만을 제공하기 때문에, 복잡한 레이아웃이나 동적인 콘텐츠를 표현하기에는 한계가 있습니다.<br>
표준화 부재: 마크다운 문법은 표준화되어 있지 않아 다양한 버전이 존재하며, 특정 플랫폼이나 도구에 따라 문법의 일부가 다를 수 있습니다.<br>
제한된 문법: 텍스트 기반으로만 작성되기 때문에, 이미지나 표와 같은 고급 요소를 표현하기에는 다소 제한적일 수 있습니다.<br>
마크다운은 간단하고 효율적인 문서 작성을 위한 훌륭한 도구이지만, 프로젝트의 특정 요구사항이나 디자인 요소를 고려할 때는 다른 마크업 언어나 편집 도구를 고려해야 할 수도 있습니다.<br>

# 마크다운(MarkDown) 문법



## Headers 헤더

- #으로 시작하는 텍스트, #은 하나부터 여섯개까지 가능 #이 늘어날때마다 제목이 작아짐 H1은 ==== H2는 ---로도 만들 수 있습니다.
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
## Horizontal Rules 수평선

- 또는*또는_을3개 이상 작성(-을 사용할 경우 header로 인식할 수 있으니 이 전 라인은 비워두어야 합니다.
```
* * *
***
*****
- - -
-------------------
```
* * *
***
*****
- - -
-------------------

## Line Breaks 줄바꿈

- br를 활용해서 줄바꿈을 할 수 있습니다.
- 엔터로 칸을 띄면 다음 행으로 넘어가게 됩니다. <br>은 하나의 문장에서 줄바꿈

```
살면서 듣게 될까?
언젠가는 바람의 노래를
세월 가면 그때는 알게 될까?
꽃이 지는 이유를
```
살면서 듣게 될까?<br>
언젠가는 바람의 노래를<br>
세월 가면 그때는 알게 될까?<br>
꽃이 지는 이유를<br>

## Emphasis 강조

- 기울여 쓰기(italic) : * 또는 _로 감싼 텍스트.
- 두껍게 쓰기(bold) : ** 또는 __로 감싼 텍스트.
- 취소선 : ~~로 감싼 텍스트.
- 이탤릭체와 두껍게를 같이 사용할 수 있습니다.

```
_과거는 잊어라. 미래를 가릴 뿐이니까._
**과거의 선택이 현재를 만든다.**
~~아름다움은 사그라들기 마련. 그래서 아름다운 거야.~~
_자신의 한계를 인정하는 것이 실패의 첫걸음이지._
```

_과거는 잊어라. 미래를 가릴 뿐이니까._<br>
**과거의 선택이 현재를 만든다.**<br>
~~아름다움은 사그라들기 마련. 그래서 아름다운 거야.~~<br>
_자신의 한계를 인정하는 것이 실패의 첫걸음이지._<br>

## Blockquotes 인용

### 노인과 바다
```
> But man is not made for defeat. A man can be destroyed but not defeated.
> 하지만 인간은 패배하도록 만들어지지 않았다. 파괴될 수는 있어도 절대 패배할 수 없다.

> > Now is no time to think of what you do not have. Think of what you can do with what there is..
> > > 내가 가지지 못한 것에 대해 생각할 시간은 없다. 내가 가진 것을 활용하여 무엇을 할 수 있는지를 생각해야 한다.
```

> But man is not made for defeat. A man can be destroyed but not defeated.<br> 
> 하지만 인간은 패배하도록 만들어지지 않았다. 파괴될 수는 있어도 절대 패배할 수 없다.

> > Now is no time to think of what you do not have. Think of what you can do with what there is..<br> 
> > > 내가 가지지 못한 것에 대해 생각할 시간은 없다. 내가 가진 것을 활용하여 무엇을 할 수 있는지를 생각해야 한다.

인용구 안에는 제목이나 리스트, 텍스트박스 도 넣을 수 있습니다.
```
> # h1
> * list
> `textbox`
```

> # h1
> * list
> `textbox`

## Lists 목록
```
* 탑
  * 정글
    * 미드
+ 탑
  + 정글
    + 미드
- 탑
  - 정글
    - 미드
 ```

* 탑
  * 정글
    * 미드
+ 탑
  + 정글
    + 미드
- 탑
  - 정글
    - 미드

## Ordered lists 순서가 있는 목록

- 숫자를 입력하면 순서가 생깁니다.
- 들여쓰기를 하면 모양이 바뀝니다.
```
1. 탑
2. 정글
3. 미드
5. 원딜 <!-- 5번을 썻는데도 4번으로 표시된다. -->
```

1. 탑
2. 정글
3. 미드
5. 원딜 <!-- 5번을 썻는데도 4번으로 표시된다. -->

- 리스트 안 리스트를 사용하려면 tab과 함꼐 숫자 1번 서부터 나열해야 적용이 됩니다.
```
1. 탑 1번 
    1. 탑 1-1번
2. 정글 2번 
3. 미드 3번 
    1. 미드 3-1번 <!-- 리스트 안 리스트를 사용하려면 tab과 함꼐 숫자 1번 서부터 -->
    2. 미드 3-2번
```

1. 탑 1번 
    1. 탑 1-1번
2. 정글 2번 
3. 미드 3번 
    1. 미드 3-1번 <!-- 리스트 안 리스트를 사용하려면 tab과 함꼐 숫자 1번 서부터 -->
    2. 미드 3-2번
 
## Backslash Escapes

- 특수문자를 표현할 때, 표시될 문자 앞에 \를 넣고 특수문자를 쓰면 됩니다.
```
* 특수문자 출력안됨
- 특수문자 출력안됨

\* 특수문자 출력

\- 특수문자 출력
```

* 특수문자 출력안됨
- 특수문자 출력안됨

\* 특수문자 출력

\- 특수문자 출력

예시
\*12345\*

\#12345\#

\[12345\]

## 이미지
```
- 인라인 이미지 ![alt text](/test.png)
- 링크 이미지 ![alt text](image_URL)
- 링크와 비슷하지만 앞에 !가 붙습니다.
- 이미지의 사이즈를 변경하기 위해서는 <img width="OOOpx" height="OOOpx"></img>와 같이 표현합니다.
```
```
1. ![텍스트](이미지파일경로.jpg)
2. ![텍스트](이미지파일URL)
```

### 링크와 이미지를 합친 문법 (이미지를 링크로 사용)
```
1. [ ![텍스트](이미지URL) ]( 링크URL )
```
[![](https://t1.daumcdn.net/cafeattach/1D7bO/a72dde3a47d0ca50b567bc4d74702f8a53aa1cbe)](https://github.com/kkamagnun)


### <img>태그를 이용한 이미지 크기 조절

<img src="https://i.namu.wiki/i/u6RY6Cwfgl5LU3zbiqxbOzmRfe2IEeICXexXNykfzxwnhMwIvV8KddLNkUxyNyDQzBwtvD9swGszVOXM_A0UFw.webp" width="200" height="200" />


## Links (Anchor) 링크

- 외부 링크

[Google](http://www.google.com "구글")

[Naver](http://www.naver.com "네이버")

[Github](http://www.github.com "깃허브")

(꺽쇠 갈화 없이도 자동으로 링크를 사용)


- 링크이름변경
```
[링크는 젤다의전설 주인공 이름](http://zeldahagoshipda.com)
```

[링크는 젤다의전설 주인공 이름](http://zeldahagoshipda.com)

- 내부(해시) 링크
```
[보여지는 내용](#이동할 헤드(제목)) 괄호 안의 링크를 쓸 때는 띄어쓰기는 -로 연결, 영어는 모두 소문자로 작성 

[1. Headers 헤더](#1-headers-헤더)

[2. Emphasis 강조](#2-emphasis-강조)

[3. Blockquotes 인용](#3-blockquotes-인용)
```

[1. Headers 헤더](#1-headers-헤더)

[2. Emphasis 강조](#2-emphasis-강조)

[3. Blockquotes 인용](#3-blockquotes-인용)

## 코드블럭
```
- 간단한 인라인 코드는 텍스트를 앞뒤로 `기호로 감싸면 됩니다.
- ``` 혹은 ~~~ 코드.
- 코드가 여러 줄인 경우, 줄 앞에 공백 네 칸을 추가하면 됩니다.
- ``` 옆에 언어를 지정해주면 syntax color가 적용됩니다.
  

javascript
function test() {
 console.log("look ma’, no spaces");
}
```
```
## 체크리스트

- 줄 앞에 - [x]를 써서 완료된 리스트 표시.
- 줄 앞에 - [ ]를 써서 미완료된 리스트 표시.
- 체크 안에서 강조 외에 여러 기능을 사용할 수 있습니다.
```
- [x] this is a complete item
- [ ] this is an incomplete item
```

- [x] this is a complete item
- [ ] this is an incomplete item

예시
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
```

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported

## Table 테이블

- 헤더와 셀을 구분할 때 3개 이상의 -(hyphen/dash) 기호가 필요합니다.
- 헤더 셀을 구분하면서 :(Colons) 기호로 셀(열/칸) 안에 내용을 정렬할 수 있습니다.
- 가장 좌측과 가장 우측에 있는 |(vertical bar) 기호는 생략 가능합니다.

```
테이블 생성

헤더1|헤더2|헤더3|헤더4
---|---|---|---
셀1|셀2|셀3|셀4
셀5|셀6|셀7|셀8
셀9|셀10|셀11|셀12
```

테이블 생성

헤더1|헤더2|헤더3|헤더4
---|---|---|---
셀1|셀2|셀3|셀4
셀5|셀6|셀7|셀8
셀9|셀10|셀11|셀12


테이블 정렬

```
헤더1|헤더2|헤더3
:---|:---:|---:
Left|Center|Right
1|2|3
4|5|6
7|8|9
```

테이블 정렬
헤더1|헤더2|헤더3
:---|:---:|---:
Left|Center|Right
1|2|3
4|5|6
7|8|9
```

## 글자색(깃허브 x)

```
<span style="color:red"> red </span>
<span style="color:#ffd33d"> yellow </span>
<span style="color:blue"> blue </span>
<span style="color:brown"> brown </span>
<span style="color:orange"> orange </span>
<span style="color:green"> green </span>
<span style="color:violet"> violet </span>
<span style="color:yellowgreen"> yellowgreen </span>
<span style="color:blueviolet"> blueviolet </span>
<span style="color:gray"> gray</span>
<span style="color:indigo"> indigo </span>
```

## 형광펜(깃허브 x)

```
<span style="background-color:#fff5b1"> 노란형광펜 </span>
<span style="background-color:#FFE6E6"> 빨강형광펜 </span>
<span style="background-color:#E6E6FA"> 보라형광펜 </span>
<span style="background-color:#C0FFFF"> 파랑형광펜 </span>
<span style="background-color:#FFFFF0"> 노란형광펜 </span>
<span style="background-color:#F5F5F5"> 회색형광펜 </span>
<span style="background-color:#DCFFE4"> 초록형광펜 </span>
```

## 깃허브 글자색 바꾸기

- 깃허브는 마크다운문법으로 글자에 색을 넣을 수 없음....
```
${\color{red}Red}$
${\color{green}Green}$
${\color{lightgreen}Light \space Green}$
${\color{blue}Blue}$
${\color{lightblue}Light \space Blue}$
${\color{black}Black}$
${\color{white}White}$
```
${\color{red}Red}$<br>
${\color{green}Green}$<br>
${\color{lightgreen}Light \space Green}$<br>
${\color{blue}Blue}$<br>
${\color{lightblue}Light \space Blue}$<br>
${\color{black}Black}$<br>
${\color{white}White}$<br>
