# 마크다운(Markdown)

> 일반 텍스트 형식 구문을 사용하는 마크업 언어의 일종으로 사용법이 쉽고 간결하여 빠르게 문서 정리를 할 수 있습니다. 단, 모든 HTML 마크업을 대체하지는 않습니다.



# 1. 문법

## 1. 1 Header

> 헤더는 제목을 표현할 때 사용합니다. 단순히 글자의 크기를 표현하는 것이 아닌 의미론적인 중요도를 나타냅니다.

* `<hi>` 부터 `<h6>` 까지 표현 가능합니다.
* `#`의 개수로 표현하거나 `<h1></h1>` 의 형태로 표현 가능합니다.



# h1 태그입니다

## h2 태그입니다

### h3 태그입니다.

#### h4 태그입니다.

##### h5 태그입니다.

###### h6 태그입니다.



## 1. 2 List

> 목록을 나열할 때 사용합니다. 순서가 필요한 항목과 그렇지 않은 항목으로 구분할 수 있습니다. 순서가 있는 항목 아래 순서가 없는 항목을 지정할 수 있으며 그 반대도 가능합니다.

* 순서가 없는 목록
  - `1.` 을 누르고 스페이스 바를 누르면 생성할 수 있습니다.
  - `tab` 키를 눌러서 하위 항목을 생성할 수 있고 `shift + tab` 키를 눌러서 상위 항목으로 이동할 수 있습니다.
* 순서가 있는 목록
  * `-` (하이픈)을 쓰고 스페이스바를 누르면 생성할 수 있습니다.
  * `tab` 키를 눌러서 하위 항목을 생성할 수 있고 `shift + tab`  키를 눌러서 상위 항목으로 이동할 수 있습니다.



1. 순서가 있는 항목
2. 순서가 있는 항목
   1. 순서가 있는 하위 항목
   2. 순서가 있는 하위 항목



* 순서가 없는 항목
* 순서가 없는 항목
  * 순서가 없는 하위 항목
  * 순서가 없는 하위 항목



## 1. 3 Code Block

> 코드 블럭은 작성한 코드를 정리하거나 강조하고 싶은 부분을 나타낼 때 사용합니다. 인라인과 블럭 단위로 구분할 수 있습니다.

* Inline
  * 인라인 블럭으로 처리하고 싶은 부분을 ` (백틱) 으로 감싸줍니다.
* Block
  * ` (백틱)을 3번 입력하고   <code>enter</code> 를 눌러 생성합니다.



`add` 한 요소를 remote 저장소에 올리려면 `$ git push origin master`를 터미널에 입력합니다.



```git
$ git add .
$ git commit -m "first commit"
$ git push origin mastergit
```



## 1. 4 Image

> 로컬에 있는 이미지를 삽입하거나 이미지 링크를 활용하여 이미지를 나타낼 때 사용합니다.

* `![]()` 을 작성하고 `()` 안에 이미지 주소를 입력합니다. `[]` 안에는 이미지 파일의 이름을 작성합니다.
* 로컬에 이미 파일을 저장한 경우 절대 경로가 아닌 상대 경로를 사용하여 저장합니다.



![깃](data:image/png;base64,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)<img src="https://nextgen.group/hubfs/github_PNG65.png" alt="깃허브" style="zoom: 50%;" />



## 1. 5 Link

> 특정 주소로 링크를 걸 때 사용합니다.

* `[]()` 을 작성하고 `()` 안에 링크 주소를 작성하고 `[]` 안에 어떤 링크 주소인지 작성합니다.



[git 공식문서](https://git-scm.com/)

[github 공식문서](https://github.com/)



## 1. 6 Table

> 표를 작성하여 요소를 구분할 수 있습니다.

* `|` (파이프) 사이에 컬럼을 작성하고 `enter` 를 입력합니다.
* 마지막 컬럼을 작성하고 뒤에 `|` 를 붙여줍니다.

| working directory | statging area | remoe repo |
| ----------------- | ------------- | ---------- |
| working tree      | index         | history    |
| working copy      | cache         | tree       |





## 1. 7 기타

#### 인용문

* `>` 을 입력하고 `enter` 키를 누릅니다.

> git 은 컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템이다.

* 인용문 안에 인용문을 작성하면 중첩해서 사용할 수 있습니다

> $ git add. 
>
> > $ git commit -m "first commit"
> >
> > > $ git push origin master



#### 수평선

* `---` , `***`, `___` 을 입력하여 작성합니다.

Working Directory

***

Staging Area

***

Remote Repository

***



#### 강조

* 이탤릭체는 해당 부분을 `*` 또는 `_` (언더바)로 감싸줍니다.
* 볼드체는 해당 부분을 `**` 또는 `__` (언더바 2개)로 감싸줍니다.
* 취소선은 `~~` 표시를 사용합니다.

이것은 *이탤릭체*입니다.

이것은 **볼드체**입니다.

이것은 ~~취소선~~입니다.



# 2. 과제

> 현재의 pdf 문서를 마크다운 문법을 활용하여 `00_markdown__basic.md`로 만들어 보세요.



