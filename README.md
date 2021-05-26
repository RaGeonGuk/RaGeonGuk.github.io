#### 작업예정
- 1달간은(프론트엔드) 주로 UI 계속 진행(VS code) 하면서, 
- 피곤할 때, 자바|스프링(이클립스-egov전자정부프레임워크개발환경) 기본언어실습진행.
- 피곤할 때, 오라클DB(SQL 디벨러퍼 개발환경) Ansi-SQL(표준SQL)기본언어실습진행 CRUD.
- 2달째부터, 주로 스프링으로 실습이 진행.(납품용-이력서포트폴리오용)
- eGov: 자바기반 -> JDK(Java Devleopment Kit 자바개발환경) 설치확인
- JDK 실행경로 추가.
- java -version (git --version)
- 자바 오라클자바는 8버전부터 유료. 이 이슈 때문에, 오픈JDK로 회사에서는 변경사용
- 그래서, 자바 8~11버전 지우고, 오픈JDK로 변경 후 이클립스를 사용할 예정.
- OPEN JDK 8버전 (egov와 100% 호환됨)
- 톰캣: 이클립스에서 웹프로그램 결과를 확인하는 라이브 서버입니다.(localhost:8080)
- 라이브서버(아파치): VS code에서 HTML 결과를 확인하는 라이브서버.(ocalhost:5500)
- JRE: Java Runtime Enviriment(자바실행환경) - 자바 앱을 실행할때만 사용.
- JDK 설치: 개발하고, 실행할때.
- 점심 후 웹프로젝트1개 (HELLO WORLD) 생성 play 후 지우고,
- 스프링프로젝트 1개(헬로 자바) -test 폴더에서 자바기초를실습
- 자바에 익숙해진 후 위 스프링 프로젝트를 이용해서 스프링 웹 프로젝트를 진행
- VS code 에서 만든 UI를 JSP로 변경 후 스프링웹 프로젝트를 진행합니다.
#### 20210527(목) 작업예정
- 관리자단 AdimnLTE적용.(회원관리 CRUD, 게시판 CRUD 대시보드)


#### 20210526(수) 작업.
- 검색엔진에 최적화? 의미있는 태그를 사용했는가? <header>, <section>, <footer>, <article>, 태그처럼 html5 부터 만들어진 태그를 사용하면, 구글 검색에 잘 노출됩니다.
- 유효성 검사 (validation) 입력값이 제대로 된 값인지 확인하는 과정.
- html5 내장된 유효성 검사? required(공백체크), type="email" (이메일 형식 체크), type="password"(입력값을 숨김처리), type="number" (숫자체크)
- js로 유효성 검사? 비밀번호 확인(2개 입력값을 체크)
- 반응형 서브페이지들(로그인, 회원가입, 마이페이지)
- HTML5부터는 유효성 검사가 내장되어있기 때문에, JS로 빈칸인지 코딩할 필요가 없습니다.
- 기획시, 메인1 CSS 네이밍, 서브1 CSS 네이밍. 
- 과장/이사급이 UI를 2개 파일 만듬 또는 테마포레스트 같은 디자인 (UIhtml +css+js를 구매) -> 기반으로 퍼블리셔, 프론트 개발자 CSS나 HTML 작업 이어서 합니다.
- 금액이 4000이상 2억 안팎인 프로젝트 자체 UI 사용



#### 20210525(화) 작업
- css: 계층: 조부 > 부 > 본인(timeline) > 자식(collapse) 손자(time-labe) > 증손자
- board_view.html 댓글 AdmiLTE3의 페이징 UI 추가 ok.
- 어제 스프링 프로젝트에서 5교시에 자바기초 시작 예정
- 위 시작전 이클립스에서 프로젝트(윈도우 탐색기와 동일한 구조) 익스플로러와 패키지(폴더경로를 .으로 구분) 익스플로러 차이 확인.

#### 20210524(월) 작업.
- 시간 형식(Type): date(년월일), dateTime(년월일시분초), TimeStamt(년월시분초)
- 1970년 생일: 타임스탬프가 1970년 1월 1일부터 현재까지의 초를 계산한 결과값
- 1970년 1월 1일 부터 16억2천...초가 흐른 시간이 현재(20210524)임
- 부트스트랩 용어: grid(12칸) modal, xs,sm,md,la,bs, -부트스트랩, fa-폰트어썸
- 팝업창: 모달창(modal - 필수창: 작업 후만 다음으로 가능), 모달리스창(modalless - 작업하고 상관없이 다른 창으로 이동가능 )
- 폰트 어썸(Font Awesome 아이콘 웹폰트) : 아이콘을 확대해도 깨지지 않음(백터 방식의 아이콘)
- 포토샵 디자인으로 아이콘을 만들면 확대 시 깨짐(비트맵 이미지 = 스칼라방식의 아이콘)
- 부트스트랩 레이아웃 용어: 화면을 12개의 컬럼으로 분리해서 크기를 반응형으로 만듭니다.
- row(가로줄), col(세로칸), col-md-12(화면 가로 크기를 12로 지정 = 100%, md 미디엄에서는 100% '970이상부터(태블릿)는  100% 잡아라.' 라는 의미)
- 반응형의 화면크기: xs엑스트라스몰(~750px), sm(750px~), md미디엄(970px~), 1g라지(1170px~)
- col-6(화면 가로 크기를 6으로 지정 = 50%)
- board_view.html 댓글 UI 디자인(부트스트랩) 추가.
- 반응형 서브페이지 (로그인, 회원가입, 마이페이지)
- 관리자단 AdminLTE적용. (회원관리 CRUD, 게시판 CRUD, 대시보드)
- 이클립스 헬로월드 만들기 실습. 1. 다이나믹 웹프로젝트(jsp 만드는 방식) 만든 후 사용자단  UI 실행만 하고, 삭제
- jsp(1세대 2000년 -게시판) -> 서블렛(2세대 2005년 servelet 게시판) -> 스트러츠(3세대 2010년대 프레임워크) -> 스프링 (4세대 2013년대, 프레임워크 )
- 스프링(MVC) 웹프로젝트 만들예정. 헬로월드 1개 - 2달간 이 프로젝트로 진행됩니다.
- 위 스프링 프로젝트에서 자바 기초도 이것으로 실습할 예정. -> htmlUI 만들 것을 jsp 변경 작업 들어갑니다.

#### 20210521(금) 작업.
- 반응형 게시판페이지(CRUD) CSS 처리: Create(Update) = board_write.html
- 글스기 폼: 첨부파일 부분, 내용 입력부분의 웹 에디터 추가
- 부트스트랩(AdminLTE): 제이쿼리 기반의 UI 템플릿(프레임워크)
- AdminLTE: dist(디스트리뷰트 = 배포), page(더미데이터), plugins(서머노트등등)
- 대시보드 파일샘플: index.html, index2.html, index3.html
- board_write.html 파일에 bootstrap코어 임포트 + 서머노트 플러그인 임포트
- 부트스트랩 가져온 홈페이지 https://github.com/ColorlibHQ/AdminLTE/releases/tag/v3.1.0

- 톰캣(jsp) vs VS 라이브서버(아파치 - html 해석)
- 자바소스(.java맵,.jps웹) -> 컴파일(라인단위x-인터프리터X) -> class파일(여기에 DB자료가 동적으로 입출력이 됨) -> html 번역(WAS -톰캣) -> 크롬(IE) 화면에 렌더링 결과 
- locahost 도메인 = 127.0.0.1 아이피와 바인딩되는 도메인

- 백엔드: 1. 이클립스(스프링), 2. 인텔리J(스프링부트 - 규모가 작은 프로젝트 개발)
- 2. 스프링 (MVC) 웹프로젝트 만들예정. 헬로월드 1개 - 2달간 이프로젝트로 진행됩니다.
- 위 스프링프로젝트에서 자바 기초도 이것으로 실습할 예정. -> htmlUI 만들것을 jsp변경작업 들어갑니다.


#### 20210520(목) 작업.
- 메인페이지 시간이 걸리는 부분(프런트엔드) : 메뉴처리, 슬라이딩 처리 view.html
- 메인페이지 시간이 걸리는부분(백엔드): 최근 겔러리, 공지사항 DB 데이터를 출력하는 부분
- 보통 1주일 정도 걸립니다.
- 모바일 게시판페이지(CRUD) CSS 처리: Read(list,vieew페이지) 
- Read -리스트 형식(다중Map) board_list.html, 예, 회원리스트(회원목록)
- Read -단일 Map 형식, json형식 (key1:value,key2:value,key3:value...)board_view.html(회원상세보기)
- 상세보기 페이지 댓글 디자인은 부트스트랩 디자인시 추가 할 예정.
- 카멜 표기법(낙타등 표기법 예, .bbsListTbl,) _표기법(bss_title) 
- 게시물 타이틀 넘치는 부분 CSS 처리했음. 스프링 가서는 jsp에서 프로그램으로 처리 예정
- href: hypertext referance (웹문서 참조)
- 정적(static) 콘텐츠: html, css, js
- 동적(dymaic) 콘텐츠: jsp(java 스프링), py(pythin장고), php,C#(닷넷), Nodejs(익스프레스)
- (데이터변수) 바인딩: 정적인 콘텐츠에 동적인 데이터를 넣어주는 것을 바인딩이라고 함.(묶어주는 역할)
- 오후에 자바(스프링) 개발환경 설치예정.(이클립스: 전자정부표준 프레임 워크의 개발 환경을 설치)
- 전자정부표준프레임워크를 제작한 업체 : 삼성SDS, SK C&C, LG CNS
- 테블릿+pc용 CSS 스타일처리
- 모바일 서브페이지 CSS 스타일처리
- 테블릿+PC용 CSS 스타일처리
- 모바일+테블릿+PC 댓글시스템 CSS + 제이쿼리
- AdminLTE(부트스트랩 기반 템플릿-반응형)를 이용해서 관리자단 디자인 만들기
- UI디자인 끝 -----------------------------------
- UI구현 시작 -----스프링프로젝트 시작(자바+이클립스+오라클+스프링) 시작
- UI구현 ....... 위에서 제작한 UI디자인을 이용해서 프로그램을 입히게 됩니다. 


#### 20210518(화) 작업
- 테블릿 메인 CSS 스타일 처리, PC용 메인 CSS 스타일처리
- 반응형 페이지의 핵심기술은 미디어 쿼리 명령어 사용, 가로크기를 %로 지정 (px 고정크기가 아닌 비율로 내부 컨텐츠 크기를 지정하는 방법)
- 미디어 (PC화면, 스마트폰 화면, 프린터, 태블릿 화면) + 쿼리(질의어- 질문)
- @media 미디어 타입(screen, print 등등) and (min-width:801px) {스타일 구현내용}
- 태블릿은 마우스 오버 기능을 넣을 필요가 없습니다. (손가락으로 선택을 하기 때문에...)
- 배치 1: jQuery코어 임포트 이후에 사용자가 지정한 js 배치를 해야함.
- 배치 2: reset.css, mobile.css 임포트 이후에 사용자가 지정한 tablet.css pc.css 배치해야 레이아웃이 깨지지 않습니다. 




#### 20210517(월) 작업
- 외부 data.js 파일에서 json데이터를 저장한 후 html에서 불러와서 파싱.
- 외부 사이트에서 제공(RestAPI서버)하는 json데이터를 html에서 불러와 파싱
- RestAPI서버 중 코로나19 확진자 데이터를 받아서 html에서 파싱 (파싱 = 데이터를 분해해서 화면에 뿌려주는 작업)
- RestAPI 서버주소(빅데이터): https://coroname.me/getdata
- 수업시작전, jsonData 파싱부분에서 append 사용에 2번반복되는 부분 확인

- 메인페이지에 자바스크립트(jQuery)적용.(VS code + HTML5 + CSs + jQuery)
- 메뉴, 슬라이드이미지처리, top 상단으로 이동
- jQuery 적용부분: 메뉴, 슬라이드 이미지 3개 처리: 모바일 메인페이지만 마무리
- 보통 이미지 슬라이드 처리는 외부 라이브러리(Lib) 사용(니보슬라이드, 캐로셀슬라이드)
- 외부 Lib 사용안하고, 우리가 만들어봅시다.


#### 20210514(금) 작업 
- 구문오류: synex신택스(사인택스)) 오류(문법오류)
- CSS3, HTML5: 검사 기준입니다.
- 사용자단 모바일 메인페이지 footer영역 CSS 입히기.
- 과제물 제출 준비
- jQuery Json 데이터 파싱 실습
- 8교시에 과제를 다음카페로 제출

#### 20210513(목) 작업내역
- 픽사베이 이미지 3개: 로고1, 슬라이드 이미지1, NoImage 1 받고 경로 적어놓기
- 로고: https://pixabay.com/ko/illustrations/%EC%8B%AC%EC%9E%A5-%ED%99%94-%EC%97%BC-%ED%99%94%EC%9E%AC-%EC%95%84%EC%9D%B4%EC%BD%98-2320561/
- 슬라이드이미지: https://pixabay.com/ko/photos/%EB%B6%80%EB%93%9C%EB%9F%AC%EC%9A%B4-%EA%B3%BC%EC%9D%BC-%EB%B8%94%EB%A3%A8%EB%B2%A0%EB%A6%AC-3504149/
- 슬라이드이미지2: https://pixabay.com/ko/photos/%EC%95%84%EC%9D%B4%EC%8A%A4-%ED%81%AC%EB%A6%BC-%EB%94%94%EC%A0%80%ED%8A%B8-%EC%9D%8C%EC%8B%9D-1274894/
- 슬라이드이미지3: https://pixabay.com/ko/photos/%EB%B0%B0%EA%B2%BD-%EB%B9%84%EC%B9%98-%EC%95%84%EB%A6%84-%EB%8B%A4%EC%9A%B4-2413081/
- NoImage: https://pixabay.com/ko/vectors/%EC%9A%B4%EC%A0%84-%EA%B8%88%EC%A7%80-%EA%B8%88%EC%A7%80-%EB%8F%84-%ED%91%9C%EC%A7%80%ED%8C%90-146893/
- 작업폴더를 나누는 이유: 시청(관공서), 대학, 기업의 웹프로그램(사이트) 제작 할때, 1년간은 무상 유지보수 이후 2천, 리뉴얼 4천 비용이 책정
- home폴더 기존작업물, 리뉴얼 home에 덮어쓰는 방식이 아니고, 
- 리뉴얼 할때는 home 2022 폴더에 작업을 하시게 됩니다.
- jQuery 코어 다운받기 :min 버전(압축-속도up), 일반버전(개발-속도Normal)
- kQuery 미처리 작업은 다음주에 하고,
- 오늘부터는 모바일 메인페이지1개 만들어서 과제물로 제출 -> 스프링에서 프로그램 입히는 소스로 사용하게 됩니다.
- 원격 제어프로그램 애니데스크(독일)AnyDesk 
- html5.html, css.html, js.html 여기까지
- jQuery 기본구조만 실습


#### 20210512(수) 작업내역
- ㅎㅎㅎㅎ
#### 20210511(화) 작업내역
- 로렘입숨
- 로렘입숨 
- URL경로(path): /루트, /test/html5.html
- html5의 레이아웃 구조 제작합니다.
- 서버(응답하는 프로그램=reponse) = 아파치서버, 톰캣서버
- 클라이언트(요청하는 프로그램=request) =웹브라우저
- HTML은 마크업이 태그로 구성. <의미있는 문자>...</의미있는문자>
- http:127.0.0.1:[8080|9000|5500|6500]
- PC의 네트워크 내부주소(공통):127.0.0.1 == localhost
- 고유주소: yahoo.com(도메인) == 74.6.143.25(IP주소) ==주민번호
- IP주소버전: IPv4,IPv6
- HTML도 버전: HTML5, HTML4.01(구버전old)
- 




#### 20210510(월) 작업내역
업로드 절차: 1. 커밋(commit) 2. 푸시(push)
다운로드절차: 1. 풀(pull) : 교실에서 작업한 결과를 집에서 이어서 작업할상황
레포지도리(저장소) 초기화: git init
개발PC(html) 와 깃 저장소와 연결시킵니다.
포트의 역할이 트랜드로 많이 사용됩니다.
포트(port): 포트번호로 서비스를 만드는 것이 트렌드
이전에는 80포트에 모든 서비스를 묶어놓았습니다.
모든서비스를 개별로 분리하는 트랜드가 있습니다.: 마이크로 서비스라고 합니다. == RestAPI로 구현이 됩니다.
도메인(예, https://naver.com:1451241/네이버 인증서비스 개발) 
외부인원(네이버직원아닌) 위 포트기준으로 제작한 서비스를 갖다가 사용
html : hyter Text MarkUp Language
md : MarkDown language 태그를 사용하지 않는 언어

