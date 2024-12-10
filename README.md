# Nnetlify 사용 하기
1. netlify login as github
2.  https://app.netlify.com/sites/dgwebsample/overview
3.  신규 로 git 의 내용을 연결 하면 됨  https://dgwebsample.netlify.app
4.  필요시 신규 도메인을 사용 하여 등록 하면 됨

# Git 변경 사항 저장 하기
1. git status
2. git add .
3. git commit -m '로그인 페이지 완성'
4. git remote add origin https://github.com/dany015/dSunJ  (repository name)
5. git push origin main



# Git Clone 하기 
1. git 을 install 한다
2. 전체 dir로 이동한다 ex C:\DGLEE
3. cd C:\DGLEE
4. git clone https://github.com/dany015/dSunJ.git
5. 이후 작업을 진행 한다



# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
# 문장

동해물과 백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세

# 줄 바꿈

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사</br> 우리나라 만세  
무궁화 삼처리

# 강조

_이탤릭_ 

**두껍게**

**_이탤릭 + 두껍께_**

~~취소선~~

<u>밑줄</u>


# 목록

1. 순서가 필요한 목록 
1. 순서가 필요한 목록
1. 순서가 필요한 목록 
    1. 순서가 필요한 목록 
    1. 순서가 필요한 목록 
    1. 순서가 필요한 목록 
1. 순서가 필요한 목록 

- 순서가 필요하지 않는 목록
- 순서가 필요하지 않는 목록
- 순서가 필요하지 않는 목록

# 링크

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.om">NAVER</a>

[NAVER](https://naver.com)" NAVER 로 이동"

<a href="https://naver.om"
title="NAVER 로 이동!" target="_blank">NAVER</a>

# 이미지

![HEROPY]  ( 이미지 링크)

[image 링크 집어 넣기]( 링크 추가)

# 인용문(BlockQuote)

>남의 말이나 글에서 직접 또는 간접으로</br>
>>따온 문장 인용문 

# 인라인 코드 강조

CSS 에서 `background` 혹은 background-image 속성으로 요소에 배경 `이미지를` 삽입할 수 있습니다.

선택후 백탭 기호를 누르면 block 표시됨

# 블럭 강조 

아래와 같이 코드를 그대로 보여줌.


```html 
<a href="https://google.com">GOOGLE</a>
```

```css
```

```javascript
```

```plaintext
동해물과 
```

# 표(table)

position 속성  
: 가운데 정렬
--: 오른쪽 정렬

값 | 의미 | 기본값 
-- | :--: | --:
static  | 기준 없음 | O 
relative | 요소 자신 | X
fixed | 뷰포트 | X

# 원시 HTML (Raw HTML)

동해물과 <u>백두산이</u> 마르고 닳도록 <br/>
하느님이 보우 하사 우리나라 만세

<span style="text-decoration: underline;">
백두산</span>

# 수평선


```  
***  
