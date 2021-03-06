# __LALA__
## __프론트 엔드__
---
## __1. 인터넷__

### 1. 인터넷의 작동원리
### 2. 브라우저와 그 작동원리  
### 3. DNS와 그 작동원리
### 4. HTTP란?
### 5. 도메인이란?
### 6. 호스팅이란?

---
## __1. 인터넷의 작동원리__

### __1-1. TCP/IP란?__
    컴퓨터와 컴퓨터간의 지역네트워크(LAN)/광역네트워크(WAN)에서 원활한 통신을 가능하도록 하기위한 통신규약
    최초는 ARPANET(최초의 컴퓨터)에서 시작되었으며, 미국방위통신청에서 컴퓨터간의 통신을 위해 TCP/IP를 사용하도록 한것이 시초
    TCP/IP = 2개의 프로토콜  
    -> IP기반에 TCP가 사용 = IP 프로토콜 위에 TCP 프로토콜이 놓이게 됨.
    IP : 인터넷에 접속할 때, 컴퓨터의 주소를 부여받음 (4바이트)  
    TCP : 클라이언트 <-> 서버 간 데이터 신뢰성을 위해 만들어진 프로토콜  
    -> 근거리 통신망(LAN) / 원거리 통신망(WAN) / 인트라넷 / 인터넷의 데이터를 안정적으로 순서대로 에러없이 데이터 교환 역할  

  

### __1-2. TCP/IP를 선택한 이유__
    TCP/IP의 개방성
    -> 하드웨어/운영체제/접속메체에 관계 없이 동작이 가능 => 인터넷 통신을 위한 핵심으로 선택  

### __1-3. 인터넷의 정의__
    컴퓨터 <-> 컴퓨터 간의 TCP/IP통신 프로토콜을 이용해 서로 데이터를 주고 받도록 한 네트워크  
    -> 네트워크의 네트워크를 구현, 모든 컴퓨터를 하나의 통신망에 연결하도록 하는 의도에서 인터넷이라고 함.  

### __1-4. 네트워크__
    두개의 컴퓨터간 통신  
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FdQgzYe%2FbtqTcQXEZmq%2FKb26sNOu1MnNRI9bQONtx1%2Fimg.png" width = "600px" height="150px" title="두대의 컴퓨터간 통신">

    여러대의 네트워크
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FcibDry%2FbtqS29c9Xfw%2FwflLiKKdsMbvar8XbLSVl1%2Fimg.png" width = "500px" height="300px" title="여러대의 네트워크">  


### __1-5. 라우터 - 라우터 연결__
    라우터를 이용한 네트워크  
    -> 여러대의 컴퓨터를 연결 할 경우 위와 같이 복잡해지는 문제 해결을 위해 등장
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FzcfiH%2FbtqS1V7ksYm%2FJF2n5ssL6IBbm7uRmWtRvK%2Fimg.png" width = "500px" height="300px" title="라우터를 이용한 네트워크">

    라우터 - 라우터 연결을 통한 네트워크의 네트워크  
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbtfgF6%2FbtqS1VlW2xI%2FNq7TWrcz9C5aIwTOIYYgp1%2Fimg.png" width = "600px" height="300px" title="라우터-라우터 간의 네트워크">

### __1-6. 모뎀을 이용한 네트워크 연결__
    모뎀을 이용한 네트워크
    -> 먼 지역과 유선 케이블 연결 불가능한 문제 해결을 위해 등장 (전화선 이용)
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fdk7h7I%2FbtqS295lORM%2FNGqb2QqcbRSBy3No7ns8M1%2Fimg.png" width = "600px" height="300px" title="모뎀을 이용한 네트워크">

### __1-7. 네트워크 인프라__
    전체 네트워크 인프라
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fmk65I%2FbtqS29EeMIV%2FDWTGDmvx0JeBUCzzkcWWhK%2Fimg.png" width = "300px" height="1200px" title="전체 네트워크 인프라">

---

## __2. 브라우저와 그 작동원리__

### __2-1. 브라우저의 기능__
    웹브라우저 진입 -> 서버에 요청 -> 응답(HTML/CSS/Img) -> HTML,CSS 명세에 따라 HTML파일 해석 후, 출력
    => 명세서 = W3C(웹 표준화 기구)에서 정함 
    *인터페이스는 표준 명세서가 없음
### __2-2. 브라우저의 구조__
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FkKheY%2FbtqTLyI9CSM%2Fcioz7KiHc5E4311sczKem0%2Fimg.png" width = "600px" height = "400px" title="브라우저의 구조">

    사용자 인터페이스 = URL, 입력창, 뒤로가기 등  
    브라우저 엔진 = 사용자 인터페이스와 렌더링 엔진 사이의 동작을 제어  
    렌더링 엔진 = 요청한 콘텐츠를 표시 -> HTML,CSS을 서버에 받아 파싱 후 화면에 표시.  
    통신 = 서버와의 통신  
    UI 백엔드 = UI구동이 가능하게 함  
    자바 스크립트 해석기(엔진) = 자바스크립트 코드 해석  
    자료 저장소 = 쿠키같은 종류의 자원을 저장(웹 데이터 베이스)  

### __2-3. 렌더링 엔진과 동작 과정__
    렌더링 = 서버로부터 받은 파일 -> 웹에 뿌려줌
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FsGFEb%2FbtqTDJeBGvp%2F1kJpGyZAuWYfypXJqVfEn1%2Fimg.png" width = "600px" height="400px" title="렌더링 엔진의 동작과정">

    1. DOM트리의 구축을 위한 HTML 파싱
    2. 렌더 트리 구축
    3. 렌더 트리 배치
    4. 렌더 트리 그리기

### __2-4. DOM트리의 구축을 위한 HTML 파싱__
    서버에서 응답받은 HTML문서를 파싱 -> 각 Element 요소 => DOM Tree의 구축을 위해 DOM 노드로 전환
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Ft949m%2FbtqTKMnwiOK%2FYdvoKOTIYVzYEOvTDFkkXk%2Fimg.png" title="DOM Tree">

### __2-5. 렌더 트리 구축__
    DOM Tree 구축 되는 동안 브라우저 -> 렌더 트리 구축
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FBXYRD%2FbtqTNBsa8lK%2Fw1rKc3hyA56zr6zPVOrHq0%2Fimg.png" title="렌더 트리">

### __2-6. 렌더 트리 배치__
    뷰포트 = 그래픽이 표시되는 브라우저의 영역,크기
    -> 뷰표트내에서의 정확한 위치와 크기 계산 => 렌더 트리 배치에서 진행

### __2-7. 렌더 트리 그리기__
    노드들의 위치,크기,스타일 계산이 완료된 렌더 트리를 이용해 실제 픽셀값을 채움

---

## __3. DNS와 그 작동원리__

### __3_1. DNS의 정의__
    DNS = Domain Name System
    -> 호스트의 도메인 이름을 호스트의 네트워크 주소로 바꾸거나 그 반대의 변환을 수행할 수 있도록 하기 위해 개발됨

### __3_2. DNS의 작동원리
<img src = "https://media.vlpt.us/images/goban/post/5717ceb7-79f2-41d3-86e5-7e48bfd6ac58/DNSLogic.png" title="DNS의 작동원리">

    1. 웹브라우저에 URL을 입력하면 Local DNS에게 hostname에 대한 IP주소 질의  
    -> Local DNS에 없을 경우 다른 DNS name 서버 정보를 받음 (Root DNS)  
        => Root DNS = 인터넷의 도메인 네임 시스템의 루트존
    2. Root DNS서버에 URL 질의
    3. Root DNS서버로 부터 "com 도메인"을 관리하는 TLD(Top-Level Domain) 이름 서버 정보 전달 받음
    4. TLD에 URL 질의
    5. TLD에서 "name.com" 관리하는 DNS 정보 전달
    6. URL 도메인을 관리하는 DNS서버에 URL 호스트네임에 대한 IP주소 질의
    7. Local DNS 서버에게 IP주소 응답
    8. Local DNS = URL에 대한 IP주소 캐싱, IP주소 정보 전달

### __3_3. TLD의 구조
<img src = "https://media.vlpt.us/images/goban/post/679d8a2b-1933-4850-95b9-c13765b9ff6c/TLD.jpg" title = "TLD의 구조">

---

## __4. HTTP란?__

### __4_1. HTTP의 정의__
    HTTP = HyperText Transfer Protocol
    -> 초기에는 HTML과 같은 하이퍼미디어 문서 전송
        => 최근에는 plain text,JSON,XML 등 다양한 형태의 정보도 전송하느 ㄴ애플리케이션 레이어 프로토콜
    초기에는 웹 브라우저, 웹 서버 간의 커뮤니케이션을 위해 디자인
    -> 최근에는 모바일 애플리케이션 및 IoT등과의 커뮤니케이션과 같이 다른 목적으로도 사용

### __4_2. HTTP의 동작 방식__
    클라이언트 = 서버에게 요청을 보내는 리소스 사용자
    서버 = 클라이언트에게 요청에 대한 응답을 제공하는 관리자
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FdcUnst%2FbtqWXaFbg2p%2F86WwcX7OsOvnkoO71T0RbK%2Fimg.png" title="HTTP의 동작 방식">

### __4_3. HTTP의 요청 메서드__
    GET = 특정 리소스를 받기 위한 요청
    -> 리소스의 생성, 수정 및 삭제 등에 사용해서는 안됨.

    POST = 리소스 생성, 컨트롤러 실행

    PUT = 변경 가능한 리소스 업데이트에 사용, 항상 리소스 식별정보 포함해야 함.

    PATCH = 변경 가능한 리소스의 부분 업데이트에 사용, 항상 리소스 식별정보 포함해야함.
    -> PUT을 사용해 전체 객체를 업데이트 하는 것이 관례여서 거의 사용되지 않음.

    DELETE = 특정 리소스를 제거하는데 사용

    HEAD = 클라이언트가 본문 없이 리소스에 대한 헹더만 검색하는 경우 사용
    -> 일반적으로 클라이언트가 서버에 리소스가 있는 지 확인하거나 메타 데이터를 읽으려는 때만 GET대신 사용.

    OPTION = 클라이언트가 서버의 리소스에 대해 수행 가능한 동작을 알아보기 위해 사용
    -> 일반적으로 서버는 이 리소스에 대해 사용할 수 있는 HTTP 요청 메서드를 포함하는 Allow 헤더 반환

### __4_4. HTTP 메시지__
    요청(Request)
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fc7mI3U%2FbtqWX45M76d%2FgGoVLK6rcUJhekrxMcq6a1%2Fimg.png" title="요청">

    응답(Response)
<img src = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FCmjnf%2FbtqWTYTN3X1%2F34p8xLsQtEIk0xMzyjIw8k%2Fimg.png" title="응답">

---

## __5. 도메인이란?__

### __5_1. 도메인의 정의__
    도메인(domain) = ip는 사람이 이해하고 기억하기 어렵기 때문에 이를 위해 각 ip에 이름을 부여 하는 행위

### __5_2. 도메인의 체계__
    도메인은 역트리 구조로 구성되어 있음.
<img src = "https://t1.daumcdn.net/cfile/tistory/232A484D5905623334" title="도메인의 구조">
    
    1. 일반 최상위 도메인(gTLD) = com, net, org, biz 등
    2. 국가 최상위 도메인(ccTLD) = kr, jp, cn, us 등

---

## __6. 호스팅이란?__

### __6_1. 호스팅의 정의__
    호스팅 = 어떤 서비스를 빌려서 사용함

### __6_2. 호스팅의 종류__
    1. 웹 호스팅
    2. 서버 호스팅
    3. 클라우드 호스팅
    
### __6_3. 웹호스팅__
    개인이 HTML/CSS와 같은 코드로 웹 페이지를 만들었다고 하더라도, 배포과정과 도메인 연결과정이 필요함.
        -> 이 과정을 전문 업체에 맡김
### __6_4. 서버 호스팅__
    웹 호스팅 = 서버 중 일부만 대여
    서버 호스팅 = 서버 하나를 대여 -> 서버 운영에 필요한 인프라/기술력 제공 서비스
        ->회사의 인트라넷 / 대형 쇼핑몰 등 고정적으로 대용량 트래픽과 DB가 많이 사용되는 곳에서 사용
    
### __6.5. 클라우드 호스팅__
    웹 호스팅 + 서버호스팅의 개념
        -> 개인이 서버 생성/관리 용이, 트래픽의 변동에도 유연하게 대처 가능

### __6_6. 각 호스팅별 특징 및 장단점__
<img src = "https://media.vlpt.us/images/dreamjh/post/f9d2a2b2-3b0b-4bfa-a4b9-580f2ef0c03f/image.png" title="호스팅별 특징 및 장단점">
<br/><br/>

---
## __2. HTML__
---
### __1. 기초다지기 (HTML의 정의)__
### __2. 폼과 입력 검증__
### __3. 작성 규칙(conventions)과 모범 사례__
---
### __1-1. 기초다지기(HTML이란?)__  
    HTML(HyperText Markup Language, 하이퍼텍스트 마크업 언어)  
    프로그래밍 언어 X, 웹페이지가 어떻게 구조화 되어 있는지 브라우저로 하여금 알 수 있도록 하는 마크업 언어  
    HTML은 elemnets로 구성, 적절한 방법으로 나타내고 실행하기 위해 각 컨텐츠의 여러 부분들을 감싸고 마크업  
    tags는 웹 상의 다른 페이지로 이동하게 하는 하이퍼링크 내용들을 생성, 단어 강조등의 역할을 함.

### __1-2. HTML 요소(elemnet)의 구조__
    <p> My cat is very grumpy </p>
    <Opening tag> content <Closing tag>
    [-------------Element-------------]  
    
    1. 여는 태그(Opening tag): 요소의 이름과(위의 경우 p), 열고 닫는 꺽쇠 괄호로 구성됨.
        -> 요소가 시작(단락의 시작부분)부터 효과가 적용되기 시작함.
    2. 닫는 태그(Closing tag): 요소의 이름 앞에 슬래시(/)가 있는것을 제외하면 여는 태그와 같음.
        -> 요소의 끝(단락의 끝부분)에 위치하고, 닫는 태그를 적지 않는다면 이상한 결과 도출됨.
    3. 내용(Content): 요소의 내용이며, 위 경우 단순한 텍스트
    4. 요소(Element): 여는 태그, 닫는 태그, 내용을 통틀어 요소(Element)라고 부른다.
<br/>

---
### __2-1. 폼과 입력 검증__
    form은 웹 개발 할 때 반드시 다뤄야 하는 기술
        -> 로그인 화면, 글 작성 화면, 데이터를 다루는 커머는 어드민 화면까지 form은 웹 개발에 폭넓게 사용되고 있음.

    검증속성(Validation attributes)
        대부분의 브라우저 = 사용자로부터 입력 받은 값을 검증하고 개발자가 사용할 수 있도록 API제공
            ex)이메일 필드를 반드시 입력해야 한다면 입력 요소에 required 속성을 추가

    HTML의 입력 요소 = 7가지 검증 속성 제공

    - required : 필수
    - minlength / maxlength :최소/최대 길이
    - min/max : 최소/최대 정수
    - type : 타입(이메일 등)
    - pattern : 패턴(정규표현식)
<br/>

### __2-2. 폼의 구성__
    form의 기본 형태
    <form action = " /my-handling-form-page" method = "post">
        ...
    </form>

    form의 태그들 -> label, input, textarea, button 등

    label
    -> 위젯에 맞는 id를 참조하여, 사용자가 라벨을 눌렀을 때, 해당하는 위젯을 활성화 시킴
    -> Form 태그 앞에 출력되어 나옴

    input
    -> type 속성은 어떻게 입력을 받을 것인가를 결정. (매우 중요한 속성)

    textarea
    -> 여러 줄의 긴 문장을 입력할 수 있는 입력 폼

    submit
    -> 폼 데이터를 <form>요소의 action 속성에 정의된 웹페이지로 전송

    reset
    -> 모든 폼 위젯을 기본 값으로 바꿈

    button
    -> 기본 행동이 없으며, 클릭했을 때 아무것도 하지 않음

### __2-3. 폼의 유효성 검사__
#### __Form의 유효성 검사란?__  
    서버로 데이터를 제출하기 전,
    포함되어야 할 정보들이 올바른 형식이고, 입력 조건에 맞게 잘 입력되었는지 확인하는 것을 말한다.

    - 예시
        - 회원가입 시, 아이디, 비밀번호, 이메일 주소 등을 입력하도록 하는 것
        - 비밀번호 입력 시, 문자, 숫자, 기호 조합 8자리 이상 지정하도록 하는 것

    - Form의 유효성 검사 방법
        - HTML5의 유효성 검사기능(built-in form validation)
        - JavaScript를 이용
<br/>

---

## __3-1. 작성 규칙(conventions)과 모범사례__
#### __HTML 코드 작성 규칙__  
    - DTD를 제외한 모든 요소와 애트리뷰트는 소문자로 작성한다.  
    - 애트리뷰트 값은 큰따옴표(" ")로 묶는다.  
    - 아이디와 클래스의 속성 값은 숫자, 대문자, 특수문자로 시작할 수 없다.  
    - 애트리뷰트의 속성의 값은 숫자, 특수문자로 시작할 수 없으며, 대문자로는 시작 가능.  
<br/>

### __모범 사례__
    1. 유효하고, 읽을 수 있는 DOM 작성
        - 모두 대문자로 작성
        - 들여 쓰기 = 가독성의 핵심
        - 과도한 주석 사용 X
        - DOM 구성 : 추가 div 또는, 추가 element가 필요한 경우에 항상 필요한 것만 만들고 페이지의 큰 부분만 html요소로 나눌 것

    2. 인라인 스타일과 스크립트 사용 X
        - 문서가 빠르게 복잡해지는 문제점
        - 외부 스타일 시트 사용, 그렇지 않을 경우 import 추가 서버요청 생성/CSS 파일에서 명령문 생성 X

    3. 인라인 크리티컬 CSS
        - 중요 CSS를 가장 위에 배치, 페이지의 첫 부분이 더 빨리 렌더링 됨
        - 링크 태그의 순서에 따라 규칙 재작성 소요가 발생할 수 있으니 주의

    4. 스크립트 태그를 맨 아래에 배치
        - 문서 하단에 스크립트 태그를 배치
        - 브라우저는 문서를 위에서 아래로 한 줄씩 해석하기 때문에, 본문의 닫기 태그 배치할 경우 다운로드가 지연되고 문서 먼저 DOM에 로드되고 사용자에게 표시가 가능
        - 스크립트 태그의 내용을 로드하기 전에 본문의 모든 내용이 로드되기 때문에, 페이지를 빠르게 로드할 수 있음

    5. 접근성 관리
        - 탐색하기 쉽고, 사용자가 이해하기 쉽게 만들 수 있다는 것은 말 그대로 접근성이 높아질 수 있는 부분

    6. 이미지에 alt태그 사용
        - alt태그는 이미지의 대체 텍스트를 지정, 따라서 어떠한 사유로 표시되지 않았을 경우 텍스트가 대신 표시될 수 있도록 설정

    7. 페이지 당 하나의 h1
        - 검색 엔진이 사이트를 올바르게 찾아낼 수 있도록 설정하는것이 좋기 때문에

    8. 제목 및 메타 태그 사용
        - 페이지 제목과 적절한 설명 메타 태그를 사용하여 이 또한 위와 같이 사이트 색인을 생성하는데 사용되기 때문에, 유용한 정보를 제공하는것이 좋음

    9. 압축
        - 모든 작업 이후에 사이트를 라이브로 만들 수 있다면 압축을 하는 것이 페이지 로드 속도에 유리

    10. HTML 확인
        - HTML의 유효성을 검사, 결함이 있을 경우 수정을 할 수 있고, 최적화가 잘 되어있는지 확인할 수 있음

