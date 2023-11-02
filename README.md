# Markdown_Grammar
마크다운(Markdown) 문법을 정리한 파일입니다.

1. 주석 처리 문법은 다음과 같습니다.
```
<!-- 주석 -->
```

2. 헤딩 처리는 다음과 같습니다. 목차를 만들거나 내부 링크를 걸 때 꼭 있어야 합니다.
```
# 머릿말 1
## 머릿말 2
### 머릿말 3
#### 머릿말 4
##### 머릿말 5
###### 머릿말 6
```

3. 수평선을 만드는 방법은 다음과 같습니다. 언더스코어 3개 이상이면 라인이 생성됩니다.
```
___
```

4. 텍스트 속성은 3가지가 있습니다.
```
**강조체** 또는 __강조제__ (애스터리스크 또는 언더스코어를 양쪽에 2개씩) 또는 <b>강조체</b>
*이탤릭체* 또는 _이탤릭체_ (애스터리스크 또는 언더스코어를 양쪽에 1개씩) 또는 <i>이탤릭체</i>
~~취소선~~ (틸드를 양쪽에 2개씩)
```

5. 인용구는 다음과 같습니다. (중첩도 사용 가능함)
```
> 인용문
>> 인용문 (중첩1)
>>> 인용문 (중첩2)
```
> “Everyone has a plan until they get hit. Then, like a rat, they stop in fear and freeze.” - Mike Tyson

6. 불릿 리스트는 다음과 같습니다.
```
* Apple
* Pear
  - Orange
  - Banana
```
* Apple
* Pear
  - Orange
  - Banana

7. 숫자 리스트는 다음과 같습니다.
```
1. 첫번째
2. 두번째
3. 세번째
```

8. HTML 링크는 이렇게 걸 수 있습니다.
```
Click [hear](링크 주소)
```

9. 이미지 HTML 링크는 이렇게 걸 수 있습니다.
```
???
```
[![image](https://github.com/Soonbum/Markdown_Grammar/assets/16474083/64bd3896-959d-4a36-bc22-8fe39dbf000d)](https://regex101.com/)

9. 이미지는 이렇게 걸 수 있습니다.
```
![이미지 설명](링크 주소)
```
![image](https://github.com/Soonbum/Qt_for_Python/assets/16474083/24d3c325-2737-4baa-994e-41f5ca3ec324)

10. 동영상은 이렇게 걸 수 있습니다. (유튜브에서 저런 형식으로 제공해 줌)
```
[![동영상 설명](썸네일 이미지 주소)](동영상 주소)

썸네일 이미지 링크는 동영상 주소의 접미사를 활용하면 됩니다.
- 0.jpg : 480*360 ( Player background ) 
- 1.jpg : 120*90 ( start )
- 2.jpg : 120*90 ( middle )
- 3.jpg : 120*90 ( end ) 
- hqdefault.jpg : 480*360 ( Player background )
- mqdefault.jpg :320*180 ( Player background )
- default.jpg :120*90  ( Player background )
- sddefault.jpg : 640*480 (480p의 경우)
- maxresdefault.jpg : 1920*1080 (1080p의 경우)
```
[![Video Label](http://img.youtube.com/vi/kMEb_BzyUqk/0.jpg)](https://youtu.be/kMEb_BzyUqk)



<!-- 테이블 -->
|헤더|설명|
|--|--|
|Cell1|Cell2|
|Cell1|Cell2|
|Cell1|Cell2|

|--:| --> 오른쪽 정렬
|:--| --> 왼쪽 정렬
|:--:| --> 가운데 정렬

<!-- 코드의 경우 ` (backtick 키) 입력할 것 -->
`console.log('message')`

```ts
코드 블럭의 경우 백틱 3개로 위아래 감싸기
위의 ts는 타입스크립트 형식으로 표현하도록 함 (bash, cs, cpp, css, diff, html, http, ini, json, java, js 또는 javascript, php, perl, python, ruby, sql)
```

<!-- 작업 목록 (깃허브 전용) -->
- [x] 해야 할 일 1
- [x] 해야 할 일 2
- [x] 해야 할 일 3
- [ ] 해야 할 일 4


<!-- 목차 만들기 -->
목차
[1.개발을 하고 싶어요](#개발을-하고-싶어요)
[2.코딩을 잘하고 싶어요](#coding을-잘하고-싶어요)

## 개발을 하고 싶어요
## Coding을 잘하고 싶어요

! 띄어쓰기는 - 문자로 대체
! 영어는 소문자로
