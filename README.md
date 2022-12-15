# 스케쥴

---

# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6

### BlockQuote

> This is a first blockquote
>
> > This is a second blockquote
>
> This is a first blockquote

### 목록 (List)

#### 1) 순서가 있는 목록

1. 목록1
   1. 목록 1-1
   2. 목록 1-2
2. 목록2
   1. 목록 2-1
   2. 목록 2-2
3. 목록3
4. 목록4

#### 2) 순서가 없는 목록

- 목록1
  - 목록 1-1
  - 목록 1-2
- 목록2
  - 목록 2-1
  - 목록 2-2
- 목록3

### 표만들기

- | (vetical val) : 테이블 표현
- : 정렬
- (---) 헤더와 셀 구분

|  이름  |  주소  |   전화번호    |
| :----: | :----: | :-----------: |
| 홍길동 | 서울시 | 02-1234-5678  |
| 여진구 | 경기도 | 031-1234-5555 |

### 코드(code)

#### 1) 인라인 코드(inline code)

- 백틱(\`)으로 강조할 내용을 감싼다.
  repository에서 프로젝트의 설명을 부여해줄 때 `README.md`를 사용한다.

#### 2) 블럭코드 (block code)

- 백틱(`) 3개로 html, css, java등 코드를 작성할 때 사용한다.

  ```java
  public static void main(String[] args){
      System.out.println("Hello Java");
  }
  ```

### 글자 강조

**굵은 글씨**
_이텔릭_
_이텔릭_
~~취소선~~
<u>밑줄</u>

### 링크(Links)

[naver](https://www.naver.com/)
[link](a.txt)

다음 홈페이지 : <https://www.daum.net/>

### 이미지(images)

![naver](https://s.pstatic.net/dthumb.phinf/?src=%22https%3A%2F%2Fs.pstatic.net%2Fshop.phinf%2F20221207_98%2F1670411213834BMMbN_JPEG%2FIMG_9832.jpg%22&type=nf340_228) 이미지의 링크로 출력

![box](./images/images.jfif) 이미지 저장 후 출력
[![daum](images/image1.jfif)](https://www.daum.net/) 이미지 클릭 시 해당 사이트로 이동

### 원시 HTML(Raw HTML)

<img src='images/image1.jfif' alt='daum'>
