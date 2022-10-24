   # Usopp
   > 프로젝트 기간
   > 2022.08.12 ~ 2022.8.26 <br>
  
  |포지션|이름|담당|
   |---|---|---|
   |FRONT|김준호|로그인, footer|
   |FRONT|소재현|nav bar, 제품상세페이지 장바구니 추가|
   |FRONT|이빛나| 메인페이지, 제품상세페이지|
   |BACK|류예린|장바구니 CRUD 구현.|
   |BACK|이상우|로그인 & 회원가입 구현.|
   |BACK|이상엽|사이트 페이지 구현.|
<br>

# 프로젝트 시연 영상 및 이미지


[![Video Label](https://user-images.githubusercontent.com/105201721/197597252-1f97a028-b7b9-42c0-8251-344a09af74a4.png)](https://youtu.be/CnpaR1a_kIE)
👉 화면을 클릭하면 영상으로 이동합니다.

# Nav-bar 구현
![Video Label](https://velog.velcdn.com/images/so960225/post/b9558b8f-1b81-4611-b4fe-92a0219a2621/image.gif)

#  제품상세페이지
![Video Label](https://user-images.githubusercontent.com/105201721/197598394-49d69b0b-5689-4090-83d0-6dc169496846.gif)



# 기술 스택
<a href="https://developer.mozilla.org/ko/docs/Web/HTML" target="_blank"><img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white"></a> <a href="https://developer.mozilla.org/ko/docs/Web/CSS/Reference" target="_blank"><img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white"></a> <a href="https://developer.mozilla.org/ko/docs/Web/JavaScript" target="_blank"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=black"></a> 
 <br>
 <a href="https://ko.reactjs.org" target="_blank"><img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=black"></a><a href="https://sass-guidelin.es/ko" target="_blank"><img src="https://img.shields.io/badge/Sass-CC6699?style=flat&logo=Sass&logoColor=white"></a>
 <br>
 
 
  

 

<br>





## :: 구현 목표
- 로그인 및 회원가입 구현.
- 장바구니 CRUD 구현.
- 제품 메인, 카테고리, 상세 페이지 구현.


- 로그인 입력시 유효성 검사 함수에 따른 화면 구현 
- 이메일 정보를 호출하여 DB에 없다면 메세지 출력과 회원가입으로 이동.
- 이메일 정보 일치시 비밀번호 입력란 호버 출력.
- 정규집에 맞는 아이디 및 비밀번호 일치시 게정 생성.
- 메인 페이지 및 카테고리별, 상품별 페이지 구현.
- 장바구니에 상품 담기, 삭제, 수량조절 구현.

<br />

## :: 구현 사항 설명

1. 로그인 입력 데이터 유효성 검사

- 입력창에 변화가 일어날 때 마다 유효성 검사 함수가 실행된다.
- 유효성 검사 함수의 반환값(boolean)에 따라 버튼의 배경색과 disabled 속성이 변화한다.
- 테스트 방법 : `/login` 페이지 이동 >>> 로그인 input 데이터 입력

2. 장바구니 구현

- 장바구니 추가 버튼 클릭시 데이터를 백엔드로 전달해서 장바구니로 다시전달 

3. 메인페이지 상세페이지 
- 이솝 홈페이지 usefarams, map함수, props를 사용하여 UI구현 

<br />

## :: 성장 포인트 

- 프론트엔드와 백엔드간의 소통의 중요성.
- 프론트엔드와 백엔드 각 프로젝트 플로우 인지.
- 각 분야별 DB처리 방식 및 통신 오류 요소 및 해결.
- PM으로써 프런트엔드와 백엔드의 중간에서 조율하고 팀이 좋은 방향으로 나아갈 수 있도록 노력했습니다
- 첫프로젝트라 팀원들과 어떤점을 소통해야하는지 알게되었습니다
- 백엔드에 부담을 덜어주기위해 상수데이터로 Nav-bar를 관리했습니다
- Git,trello,gather,slack을 활용하여 동료와 협업하는 기술을 배웠습니다
- Git을 통한 협업 과정에서 발생하는 기술적 conflict에 대한 해결능력을 키웠습니다

<br />

# Reference
이 프로젝트는 원티드를 참조하여 학습목적으로 만들었습니다.<br>
학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.<br>
이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.






