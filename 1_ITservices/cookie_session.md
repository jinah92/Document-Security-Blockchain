# Ⅰ. 쿠키와 세션

## ⅰ. HTTP의 특징

<Ul>
    <li> HTTP 프로토콜 환경에서, 서버는 클라이언트가 누구인지 확인해야 함 (HTTP는 Connectionlass, Stateless)</li>
    <li> Connectionless : 클라이언트는 요청을 한 후, 응답을 받으면 연결을 끊는다.</li>
    <li> Stateless : 통신이 끝나면, 상태를 유지하지 않는다.</li>
</Ul>

## ⅱ.  쿠키(Cookie)

<strong>개념</strong>

<ul>
    <li>클라이언트(브라우저) local에 저장되는 키와 값이 들어있는 작은 데이터 파일</li>
    <li>유효 시간이 정해지면, 브라우저가 종료되어도 인증이 유지됨</li>
    <li>사용자가 따로 요청하지 않아도, 브라우저가 요청 헤더에 쿠키 값을 넣어 자동으로 서버에 전송함</li>
</ul>

<strong>구성요소</strong>

<ul>
    <li>이름 (각 쿠키의 식별)</li>
    <li>값 (쿠키의 이름과 관련된 값)</li>
    <li>유효시간 (쿠키의 유지시간)</li>
    <li>도메인 (쿠키를 전송할 도메인)</li>
    <li>경로 (쿠키를 전송할 요청 경로)</li>
</ul>

<strong>쿠키 동작방식</strong>

<ol>
    <li>클라이언트가 페이지 요청</li>
    <li>서버에서 쿠키를 생성하고, HTTP 헤더에 쿠키를 포함시켜 응답</li>
    <li>브라우저 종료되어도, 쿠키 만료시간 내 클라이언트에서 보관</li>
    <li>같은 요청일 경우, HTTP 헤더에 쿠키를 함께 보냄</li>
    <li>서버에서 쿠키를 읽어, 이전 상태 정보 변경이 필요하면 쿠키를 업데이트한 후, HTTP 헤더에 포함시켜 응답</li>
</ol>

<strong>사용 예시</strong>

<ul>
    <li>?방문 사이트에서 로그인 시, "ID와 PW를 저장하시겠습니까"</li>
    <li>쇼핑몰의 장바구니 기능</li>
    <li>자동로그인, 팝업에서 "오늘 더이상 이 창을 보지 않음" 체크</li>
</ul>

## ⅲ 세션(Session)

<strong></strong>

<ul>
    <li></li>
</ul>
















