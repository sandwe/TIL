# TIL
모각코 TIL

### :four_leaf_clover: 21/07/10
* front-end, back-end 기본적인 환경 구축
* 구현할 웹페이지의 구성을 Adobe XD 사용하여 제작
* 1개의 메인 페이지 및 4개의 상세 페이지 구성
  
  <details>
  <summary>메인 페이지</summary>
  <div markdown="1">       
  
  <img width=50%, height=70%  src="https://user-images.githubusercontent.com/79586634/125152397-40dd1f80-e187-11eb-8914-c4642b26175d.PNG"/>
  
  </div>
  </details>
  <details>
  <summary>상세 페이지 1 - '기초학습' 및 '심화학습' 페이지</summary>
  <div markdown="1">       

  <img width=50%, height=70%  src="https://user-images.githubusercontent.com/79586634/125152664-14c29e00-e189-11eb-989b-85b2be8007c0.png"/>
  
  </div>
  </details>
  <details>
  <summary>상세 페이지 2 - '퀴즈' 페이지</summary>
  <div markdown="1">       

  <img width=50%, height=70%  src="https://user-images.githubusercontent.com/79586634/125152684-3c196b00-e189-11eb-8f32-17582fa3d3a2.png"/>
  
  </div>
  </details>
  <details>
  <summary>상세 페이지 3 - '질문하기' 페이지</summary>
  <div markdown="1">       

  <img width=60%, height=70%  src="https://user-images.githubusercontent.com/79586634/125152698-45a2d300-e189-11eb-8f26-662ecba54c20.png"/>
  
  </div>
  </details>
  <details>
  <summary>상세 페이지 4 - 게시글 작성 페이지</summary>
  <div markdown="1">       

  <img width=50%, height=70%  src="https://user-images.githubusercontent.com/79586634/125152700-4f2c3b00-e189-11eb-97d3-4604cbee51a6.png"/>
  
  </div>
  </details>
* 다음 스터디 시간까지 웹페이지 템플릿 찾아오기

### :four_leaf_clover: 21/07/17
* xd website template 공유
* 각 페이지 별 xd website template 선정
* Adobe xd로 template 수정
* 각 페이지 별 구현 사항
  * 메인 페이지
    1. 상단 메뉴 바: 소개, 기초학습, 심화학습, 질문하기, 마이페이지, 로그인(버튼)
    2. 기초/심화학습 및 질문 게시판: 도형 클릭시 페이지 이동
    3. 콘텐츠 미리보기: 캡쳐된 콘텐츠 미리보기 가능
  * 로그인 페이지
    1. 아이디/비밀번호 입력 칸
    2. 로그인 버튼
    3. 회원가입 클릭 시 회원가입 창으로 페이지 이동
    4. 홈 버튼: 홈으로 이동
  * 회원가입 페이지 
    1. 이름, 아이디, 비밀번호, 학년 설정(토글), 완료(버튼) 
    2. 홈 버튼: 홈으로 이동
  * 기초학습 및 심화학습 페이지
    1. 사이드바: 원하는 차시 선택시 해당 차시 콘텐츠로 전환 가능
    2. 콘텐츠: 콘텐츠를 나타냄
    3. 홈 버튼: 홈으로 이동
    4. 페이지 이동 버튼: 이전/다음 페이지 이동
    
### :four_leaf_clover: 21/07/21
  * Adobe xd로 마이페이지 제작 회원가입 완료 페이지 제작
    * 마이페이지
      1. 상단 메뉴 바: 소개, 기초학습, 심화학습, 질문하기, 마이페이지, 로그인(버튼)
      2. 프로필
      3. 차시 별 진도율: 매 차시 별 진도율 나타냄
      4. 전체 진도율: 학습 전체 진도율 나타냄
    * 회원가입 완료 페이지: 회원가입 완료 후 이 페이지를 거쳐 홈으로 이동
  * 그 외 페이지는 21/07/17의 페이지 별 구현 사항과 동일
    <details>
    <summary>전체 페이지</summary>
    <div markdown="1">       

    <img width=60%, height=40%  src="https://user-images.githubusercontent.com/79586634/126729982-fa25895f-71f9-4006-abd9-23815c2279d7.PNG"/>
  
    </div>
    </details>

### :four_leaf_clover: 21/07/24
  * Adobe xd로 마이페이지 - 내 글 목록 및 질문게시판, 질문하기 페이지 제작
  * 상단 메뉴 바 - 로그인 버튼: 로그인 시 프로필과 이름이 보이도록 수정
    * 마이페이지
      1. 상단 메뉴 바: 소개, 기초학습, 심화학습, 질문하기, 마이페이지, 로그인(버튼)
      2. 프로필
      3. 차시 별 진도율: 매 차시 별 진도율 나타냄
      4. 전체 진도율: 학습 전체 진도율 나타냄
      5. 내 글 목록: 질문게시판에 등록된 내 글 확인 가능
    * 질문게시판
      1. 상단 메뉴 바: 소개, 기초학습, 심화학습, 질문하기, 마이페이지, 로그인(버튼)
      2. 서치 박스, 서치 버튼: 게시판 내 글 검색
      3. 글 목록: 작성자 프로필, 작성자 이름, 글 제목, 작성 일시
      4. 질문하기 버튼: 질문하기 모달창 띄움
      5. 페이지 넘기는 번호
    * 질문하기(모달창)
      1. 제목 입력: 글 제목 입력
      2. 질문 입력: 질문할 내용 입력
      3. 저장하기 버튼: 질문게시판에 게시
      4. 나가기 버튼: 모달창
    <details>
    <summary>전체 페이지</summary>
    <div markdown="1">       

    <img width=60%, height=30%  src="https://user-images.githubusercontent.com/79586634/126861217-07f9d8c0-be18-4cd5-9376-aacb2a85bc23.PNG"/>
  
    </div>
    </details>
      
### :four_leaf_clover: 21/07/28
* 학습 콘텐츠 개수 설정 (1 - 3차시)
* 학습 콘텐츠 기획
* 기초학습 및 심화학습 사이드 바 변경
  * 프로필: 마이페이지에서 사용자가 설정한 프로필이 나타남
  * 목차: 1차시/ 2차시/ 3차시로 구성
  * 소통하기: 질문하기로 구성
  <details>
  <summary>전체 페이지</summary>
  <div markdown="1">       


  <img width=60%, height=30%  src="https://user-images.githubusercontent.com/79586634/127661958-9a08bdc7-5181-4b5e-bc12-67160e7f0aaf.png"/>
  
  </div>
  </details>
  
### :four_leaf_clover: 21/08/04
* Adobe XD - 최종 플로우 확인 및 수정
  * 메인페이지 디자인 수정
  * 마이페이지 - 재생 버튼: 학습 페이지로 이동
  * 질문하기 - 저장 버튼: 질문게시판 페이지로 이동
* 플러그인(Export as React Componet) 사용해 xd 파일을 React파일로 내보냄

### :four_leaf_clover: 21/08/07
* Adobe XD 요소 이름 수정
* Adobe XD 파일 HTML 파일로 내보냄
* React 렌더링 방법 학습

### :four_leaf_clover: 21/08/11
* Home 페이지 및 Signin 페이지 구현
* Signin 페이지: 리액트 함수형 컴포넌트 & Hooks 이용해 로그인 input 상태 관리
* 라우터 기능 추가
  ```
  yarn add react-router-dom
  ```
  
### :four_leaf_clover: 21/08/18
* Signup 페이지 및 Mypage 페이지 구현
* Styled Components 이용해 요소 css
 * javascript에서 css 사용 가능하게 하는 CSS-in-JS 라이브러리
 ```
 yarn install styled-components
 ```
* flexbox를 이용한 반응형 웹 디자인
  * 외부 엘리먼트에 ```display: flex;``` 적용하면 외부 엘리먼트는 flex container / 내부 엘리먼트는 flex item으로 설정한다.
  * 이후 ```flex-direction: row | column ```를 적용해 flexbox의 방향성을 결정하여 내부 엘리먼트를 배치한다.
* React Router 컴포넌트
  * Link: ```<Link>``` 컴포넌트의 ```to``` prop을 통해 이동할 경로를 지정하고, ```<Link>``` 컴포넌트 클릭시 다른 페이지로 이동한다.

### :four_leaf_clover: 21/08/27
* 로그인 시 Topbar에 나타나는 프로필: dropdown 형식으로 로그아웃/회원정보 item 나타나도록 구현
* Signin 페이지 background-image 오류 수정
* 기초학습 1차시 - 마이크로비트 소개 페이지 구현


# 모각코 최종 회고록

* 프로젝트명: 전래 동화와 함께하는 코딩 교육 웹페이지
* 프로젝트 소개
  * #. 웹사이트는 전래동화와 함께하는 코딩 교육 웹 페이지입니다. 저희 웹사이트는 우리에게 익숙한 전래 동화를 코딩과 접목시켜 코딩에 대한 막연함을 떨쳐내고, 전래 동화 속에 스며들어 코딩을 자연스럽게 접할 수 있도록 합니다. 주 대상은 초등학교 4~6학년으로 설정하였지만 대상을 한정하지 않고 코딩에 관심있는 다양한 연령층이 저희 웹사이트를 이용할 수 있도록 하는 것이 목표입니다. 또한, 개미와 베짱이를 위한 기타 만들기, 알라딘의 요술램프, 견우와 직녀를 위한 전화기 만들기 등 다양한 코딩 교육 컨텐츠를 제공하는 것이 목표입니다.

* 팀 소개
  * Front-end: 방희연, 서현주
    1. adobe XD를 사용하여 프로토타입 구축
    2. 자바스크립트 라이브러리 React를 사용하여 #. 웹사이트 구현
  * Back-end: 김효민, 이채영
    1. Node.js를 사용하여 서버 구축
    2. Mysql DB 구축
    3. AWS EC2 서버 배포

* #. 웹사이트 세부 페이지
  <details>
    <summary>홈페이지</summary>
    <div markdown="1">       
       기본 메인 페이지, 상단의 메뉴를 통해 기초학습, 심화학습, 질문하기, 마이페이지, 로그인 페이지로 이동할 수 있습니다.
    </div>
  </details>
  <details>
    <summary>로그인 페이지</summary>
    <div markdown="1">       
      회원인 경우 아이디, 패스워드를 입력해 로그인이 가능하고, 비회원인 경우 회원가입하기를 클릭하여 회원가입 페이지로 이동할 수 있습니다.
    </div>
  </details>
  <details>
    <summary>회원가입 페이지</summary>
    <div markdown="1">       
      이름, 휴대폰 번호, 아이디, 패스워드를 입력하고, 소속(선생님, 초등학생, 중학생, 고등학생)을 선택한 후 회원가입 버튼을 누르면 회원가입이 완료됩니다.
    </div>
  </details>
  <details>
    <summary>기초학습 및 심화학습 페이지</summary>
    <div markdown="1">       
      사이드 바에 학습 콘텐츠 목차가 나타나고, 차시를 선택하거나 이전/다음 이동 버튼을 이용해 원하는 콘텐츠를 학습할 수 있습니다.
    </div>
  </details>
  <details>
    <summary>질문하기 페이지</summary>
    <div markdown="1">       
      질문게시판에 올라온 회원들의 다양한 질문들을 확인하고, 검색할 수 있습니다. ‘질문하기’버튼을 눌러 제목/내용을 입력하여 질문을 게시할 수 있습니다.
    </div>
  </details>
  <details>
    <summary>마이페이지</summary>
    <div markdown="1">       
      저희 웹사이트 회원의 정보가 나타납니다. 회원 정보로는 프로필, 기초학습 및 심화학습 진도현황, 나의 질문, 전체 진도 현황이 있습니다. 프로필을 선택하면 자신의 로컬 컴퓨터에 있는 사진을 업로드할 수 있습니다. 기초학습 및 심화학습의 진도현황은 회원이 수강한 콘텐츠의 진도현황을 나타내고, 재생 버튼을 클릭해 회원이 학습을 멈췄던 시점부터 다시 학습을 시작할 수 있습니다. 나의 질문은 회원이 질문게시판에 게시한 질문을 확인할 수 있습니다. 전체 진도 현황은 기초학습, 심화학습 전체 진도현황을 확인할 수 있습니다.
    </div>
  </details>
  
* 모각코 회고
(다음의 회고록은 DAKI(Drop, Add, Keep, Improve) 방식을 사용하여 작성했습니다.)

1. Drop, 다음에는 이러지말자!
    * 구글링해서 나온 정보를 토대로 일단 시도해보자
    <br/>리액트를 처음 다뤄보면서 학습과 개발을 병행해야 했다. 프로젝트는 정해진 기간이 있고, 컴포넌트 하나라도 빨리 개발을 해야한다는 생각에 마음이 조급해졌다. 그러다보니 나의 상황에 맞는 최적의 정보를 찾아야한다는 강박감이 생겨 구글링하는데에 시간을 거의 할애했다. 예를 들어 리액트 컴포넌트 작성 시 요즘은 함수 컴포넌트를 거의 사용한다고 해서 함수형 컴포넌트를 적용하려 했다. 그러나 어떤 기능을 구현하기 위해서 검색을 했을 경우 그렇게 오래전 코드가 아니어도 클래스 컴포넌트를 사용하여 기능을 구현한 것도 매우 많았다. 이러한 부분에 있어서 함수 컴포넌트와 클래스 컴포넌트에 대한 차이를 공부해가며 개발을 진행했으면 나의 리액트 실력 향샹에 도움이 되었을 것 같다는 생각이 들었다.
    
    * Background 반응형 웹으로 만들기
    <br/>처음에 반응형 웹에 대해 인지를 하지 못한 채 개발을 진행한 결과, 백그라운드는 물론이고 웹사이트의 레이아웃을 이루는 다양한 내용들도 반응형 웹으로 작동하지 않았다. 단순히 엘리먼트를 원하는 위치에 배치하려고 position으로 직접 위치를 설정해줘서 발생한 일이었다. 이러한 일을 겪고 검색을 시도한 결과 flexbox를 이용하여 반응형 웹을 구현할 수 있다는 것을 알게 되었다. display: flex; 속성을 줌으로써 부모와 자식 관계인 container와 item 들이 flexbox 레이아웃으로 바뀌고, 다양한 속성을 줌으로써 자식요소들을 다양하게 배치할 수 있다는 것을 알게 되었다.
    
2. Add, 다음에는 이런 시도를 해볼까?
    * styled-components 재사용
    <br/>```<text>```나 ```<input>``` 태그 같은 경우 css 속성 적용 시 몇몇 속성만 다르고, 공통되는 부분이 많았다. 이러한 경우 ```<Text>```,```<Input>```과 같이 특정 컴포넌트를 만들어 공통된 스타일링을 적용하고, 각 컴포넌트마다 발생되는 스타일링 차이만 ```style={{}}```를 이용해 추가하면 코드의 재사용성을 높이고, javascript에 영향을 받는 스타일링을 간편하게 구현할 수 있겠다는 생각이 들었다.

3. Keep, 이런 것들은 계속하자!
   * Git 관리
   <br/>요번에 팀 프로젝트를 하면서 Git Flow 전략을 처음 접해보았다. Git flow는 배포를 전용으로 하는 master 브랜치와 개발을 진행하는 develop 브랜치 두개를 유지하고 develop 내에서 feature 브랜치를 파서 기능을 구현하는 것으로 진행이 되었다. 이 전략을 파악하고 적용을 하려고 하니 처음에는 익숙하지가 않아 내 로컬 저장소의 파일을 원격 저장소에 올리면서 실수를 할 것 같고 불안해서 섣불리 git 명령어를 실행시키지 못했다. 이대로는 안될 것 같아 push, pull, merge 등 다양한 명령어들의 사용법 및 다양한 옵션을 알아보고, 오류 메시지가 떴을 때는 오류 메시지를 그대로 검색해 어떤 오류인지 파악하고 해결 방안을 모색했다. 그리고 팀원들의 도움을 받아 나의 깃 사용법이 맞는지도 확인을 진행했다. 이렇게 문제를 해결하는 과정을 통해 git을 사용하는 것에 대한 두려움이 조금 사라졌고, 기본적인 checkout, push, pull, merge 명령어 이외에도 다양한 명령어들을 공부해보고 실습하여 앞으로의 협업에서 git을 더 잘 다루고 싶다.
   
4. Improve, 이번에는 아쉬웠지만 다음에는 이렇게 해보자!
   * UX/UI 공부
   <br/>처음에 웹사이트 디자인을 시작할 때 ux/ui 지식이 부족하다고 판단해 웹사이트 템플릿을 선정하고 조합하여 adobe xd를 사용하여 웹사이트를 디자인했다. 여러 웹사이트 템플릿을 혼용하다 보니 각 템플릿에 이미 정해진 양한 스타일링 및 애니메이션의 충돌이 일어났고 우리가 생각하는 웹사이트 디자인으로 바꾸기 위해 시간을 할애했다. adobe xd로 프로토타입을 제작한 후 export 했을 때도 adobe xd 조작 미숙으로 인해 몇몇 페이지들이 export 되지 않았다. 따라서 프로젝트 중간에 계속 제작했던 프로토타입 대신 직접 자바스크립트로 웹사이트를 구현하는 것으로 방향을 돌렸다. 따라서 이후에 ux/ui 공부를 통해 사용자 경험에 친화적인 레이아웃을 파악하고, 나만의 웹사이트를 제작해보고 싶다.


