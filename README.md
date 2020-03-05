### CSS flex 속성을 활용한 Layout.

HTML과 CSS만을 활용한 레이아웃 프로젝트. (javascript 🙅🏻‍♂️)

flex속성을 연습하기 위해 진행.

![](/Users/jngmnghn/Documents/Study/Inflearn/css/flex/flex-grid-intro.png)

**프로젝트 구조**

```
components/
css/
images/
index.html
```

- components : 전체 레이아웃에 필요한 컴포넌트를 html로 작성. (메뉴/검색폼/불릿리스트/친구리스트/카드리스트/메시지리스트/모달)
- 전체 레이아웃에 적용하는 css와 컴포넌트에 적용하는 css을 나눠 작성.
    - style.css : 컴포넌트별 css 모음
    - style-page.css : 전체 레이아웃에 필요한 css
    - 외 reset.css

**구현기능**

- 메뉴 
    - 마우스 오버시 메뉴크기 및 색상 변경
- 불릿리스트
    - 불릿을 제외한 텍스트의 앞끝정렬
- 친구리스트/메시지리스트
    - 프로필 이미지 중앙정렬
    - 프로필이미지/텍스트 중앙정렬
    - 넘치는 텍스트 … 처리
- 카드리스트
    - 카드이미지 중앙정렬
    - 카드내용 컨텐츠에 맞게 크기 조정
- 모달
    - css 만으로 구현 실습
- 페이지
    - 반응형 구현
        - 1400px 이상 : 카드 3단으로 표시/양쪽 사이드메뉴 표시 및 폭 고정
        - 1400px 미만 600px이상 : 카드 2단으로 표시/불릿메시지,친구리스트,메시지리스트 하단으로 레이아웃
        - 600px 미만 : 카드 1단으로 표시