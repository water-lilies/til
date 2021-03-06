# 마크다운 문법

## 1. 제목(heading)

제목은 `#` 으로 표현 가능하다. 제목의 레벨은 `#` 의 개수로 나타내는데, 1~6단계까지 표현 가능하다.

### 제목3

#### 제목4

##### 제목5

###### 제목6

## 2. 목록

목록은 순서가 있는 목록과 순서가 없는 목록으로 구분 된다.

1. 순서가 있는 목록

2. 순서가 있습니다.

   1.  tab을 통해 단계를 표현할 수 있습니다.

   엔터

3. 엔터

엔터 -> 이런식으로 한단계씩 앞으로 나감

* 순서가 없는 목록
  * tab을 통해 단계를 표현할 수 있습니다.



## 3. 코드블록

인라인 코드 블록과 전체 코드 블록이 있으며, 전체 코드블록은 언어에 따른 syntax highlighting 기능을 대부분 지원한다. 

`inline` 

` ```python ` 이렇게 입력하면 됨

``` python
print('hello')
# 파이썬 주석
def foo(a):
    return a
```

` ```javascrpit `

```javascript
# 파이썬에서는 주석이지만
// 자바스크립트에서 이게 주석
```



## 4. 링크

[구글](http://www.google.com)

`[]()` 이런형태임



## 5. 인용문

> 인용문을 작성할 수 있습니다.



## 6. 표

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |
|      |      |      |

타이포라에서 `본문 > 표 > 표삽입`  이용

## 7. 이미지

![]()



절대경로(c드라이브)로 작성 된 이미지는 외부(github)에서 공개하면 이미지가 깨져서 보인다.



따라서, 다음과 같이 typora 설정을 하자.

- 파일 > 환경설정에서 `이미지` 탭 클릭하고 아래의 내용 모두 체크
  - 로컬 이미지에 위 규칙 적용
  - 온라인 이미지에 위 규칙 적용
  - 가능하다면 상대적 위치 사용
- copy image to custom folder 를 누른 후
  - ./images 로 설정
- 설정하면, 이후 이미지부터 마크다운 파일 위치를 기준으로 images 폴더를 생성하여 이미지를 복사함.

 `![두산](./images/두산.jpg)` 

![두산](./images/두산.jpg)





## 8. 기타문법

수직선

---

**굵게**

*기울임체(이탤릭체)*

~~취소선~~

