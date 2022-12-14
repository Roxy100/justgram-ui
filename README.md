# JUSTGRAM [Instagram Clone]

## 미션1 로그인 페이지 레이아웃

#### 디자인

구현해야할 로그인 페이지는 실제 instagram 로그인 부분과 유사합니다.

- instagram 사이트 로그인 페이지를 참고하여 로그인 영역만 개발합니다.
- 아이콘은 flaticon 사이트를 이용해 다운받아 사용해 주세요.
  - 🖇️ [아이콘 링크](https://www.flaticon.com/free-icon/instagram_1384031?related_item_id=1384031&term=instagram)
- instagram 로고는 아래의 폰트를 이용해 'justgram'으로 작성해주세요.
  - 🖇️ [폰트 링크](https://fonts.google.com/specimen/Lobster?preview.text=&preview.text_type=custom)

#### HTML 작성

디자인 이미지를 보면서 다음 요구사항에 맞게 HTML을 작성해주세요.

(로그인 되지 않은 [https://www.instagram.com/](https://www.instagram.com/) 화면을 참고하셔도 괜찮습니다. 🙂 )

- 로그인 전체를 감싸고 border가 적용된 div 태그
- 폰트를 변경한 'justgram'이 들어간 로고
- 로그인 입력칸 input 태그
  - type은 text와 password 사용
  - placeholder 속성 사용 → "전화번호, 사용자 이름 또는 이메일", “비밀번호”
- 로그인 버튼 button 태그
  - disabled 속성 사용 → 버튼 비활성화

#### CSS 작성

HTML 작성 단계가 끝났다면, css 파일을 작성하여주세요.

## 미션2 ID, PW 입력 시 로그인 버튼 활성화 기능 & ID, PW validation

#### 입력 이벤트 등록

Input 요소(Element)에 이벤트를 등록하여 글자 변화를 감지하게 만들어주세요.

- 요소에 addEventListener로 이벤트 등록
- ID 입력칸과(AND) PW 입력칸에 글자가 하나라도 들어가면 로그인 버튼 활성화

#### 유효성 검증 함수 작성

- [Mission 2](https://www.notion.so/Project-JUSTGRAM-UI-876b6ef09ccb4058b918f91744f5db8b) 에서 등록된 이벤트에 사용할 유효성 검증 함수 작성
- 실제 로그인 하는 경우를 생각하며 **validation(유효성 검사)** 기능을 추가해주세요.
- 유효성 검증에 따른 버튼 활성화 분기
- ex) id >>> '@' 포함 / pw >>> 5글자 이상

## 미션3 메인 페이지 레이아웃

#### 디자인

구현해야할 메인 페이지는 실제 instagram 메인페이지와 거의 비슷한 디자인입니다.

- 좌측 로고 아이콘은 flaticon 사이트를 이용해 다운받아 사용해 주세요.
  - 🖇️ [아이콘 링크](https://www.flaticon.com/free-icon/instagram_1384031?related_item_id=1384031&term=instagram)
- 우측 메뉴 아이콘은 아래 주소를 사용해주세요.
  - 탐색: [https://s3.ap-northeast-2.amazonaws.com/cdn.wecode.co.kr/bearu/explore.png](https://s3.ap-northeast-2.amazonaws.com/cdn.wecode.co.kr/bearu/explore.png)
  - 하트: [https://s3.ap-northeast-2.amazonaws.com/cdn.wecode.co.kr/bearu/heart.png](https://s3.ap-northeast-2.amazonaws.com/cdn.wecode.co.kr/bearu/heart.png)
  - 마이: [https://s3.ap-northeast-2.amazonaws.com/cdn.wecode.co.kr/bearu/profile.png](https://s3.ap-northeast-2.amazonaws.com/cdn.wecode.co.kr/bearu/profile.png)
- 피드 사진, 프로필 사진
  - 개인이 가지고 있는 사진 활용
  - 혹은 무료 이미지 사이트 [Unsplash](https://unsplash.com/) 활용
    - 저작권 문제가 발생할 수 있사오니 타 이미지보다는 Unsplash 사이트를 이용해주세요!

#### HTML 작성

디자인 이미지를 보면서 다음 요구사항에 맞게 HTML을 작성해주세요.

(로그인 된 [https://www.instagram.com/](https://www.instagram.com/) 화면을 참고하셔도 괜찮습니다. 🙂 )

- 헤더 부분
  - 아이콘, 로고, 검색창, 탐색, 하트, 마이는 적절한 tag를 사용해서 구현
- 피드 부분
  - 크게 4가지 div로 나누어서 진행
    - 피드 헤더, 피드 사진, 메뉴바, 댓글 부분
  - 피드는 3개 이상 나타나게 구현

#### CSS 작성

HTML 작성 단계가 끝났으면 이제 css 파일을 작성하여주세요.
