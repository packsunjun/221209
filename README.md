# 221209
캔버스(canvas) 객체 다루기

2학년때 환경변수 많이다룸

※ 도형 그리기
캔버스에 도형 그리는 순서
beginPath() - 새로운 빈 경로 만들기(경로(path) 만들기)
moveTo(), lineTo(), rect(), arc() - 경로에 도형 담기
stroke() – 경로 속의 도형을 캔버스에 그리기

포트폴리오는 남의것 가져와서 추가하고 업그레이드해도 인정

get - 주소를 통해서 이동
post - headers를 통해서 이동

※ 쿠키란?
웹 서버가 브라우저에게 지시하여 사용자 로컬 컴퓨터에 저장하는 4K 이하의 작은 데이터
HTTP 의 무상태 프로토콜의 약점을 보완하기 위해 도입
//개념까지만

※ 웹 스토리지(Web Storage)
세션스토리지(session storage)와 로컬스토리지(local storage)
※ 웹 스토리지의 특징
문자열만 저장
(키, 값)으로 구성된 아이템 단위로 저장
동일한 ‘키’를 가진 아이템은 존재할 수 없음
‘키’와 ‘값’ 문자열은 대소문자 구분
저장, 검색, 삭제 등 웹 스토리지의 조작은 모두 자바스크립트 코드로 작성

클라이언트 접속
로그인유지(쿠키)
다른 웹 이동해도 유지되게 해주는 것 (세션등을 사용자에게 심어줌)

==============================
※ JavaScript 개념
https://developer.mozilla.org/ko/docs/Web/JavaScript/Language_Overview

아래는 let으로 선언한 변수의 스코프(scope)의 예시입니다.

// myLetVariable는 여기에서 보이지 *않습니다*

for (let myLetVariable = 0; myLetVariable < 5; myLetVariable++) {
  // myLetVariable는 여기에서만 사용할 수 있습니다
}

// myLetVariable는 여기에서 보이지 *않습니다*


연산자, 제어 구조 등등..


     $(document).ready(function () { //전체에서
            $("p").click(function () {  //셀렉터를 클릭하면
                $(this).hide(); //실행
            });
        });


https://www.w3schools.com/cssref/css_selectors.php - CSS셀렉터
https://www.w3schools.com/jquery/trysel.asp - jquery selectors
