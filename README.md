# llpv (llProcessView) for Windows (v1.1)
활성화된 프로그램의 사용시간을 측정하여 컴퓨터를 생산적으로 사용할 수 있도록 도와주는 프로그램입니다.

## 1. 기능
* 1.1. 순위   
  - 프로세스명 또는 프로그램 제목 별 사용시간과 순위를 알려줍니다.
  - 실행시간: 프로그램이 켜진시간 ~ 현재시간
  - 24시간: 오늘날짜-1일 ~ 현재시간
  - 오늘: 오늘 00시~24시
  - 일주일: 오늘날짜-7일 ~ 현재시간
  - 한달: 오늘날짜-1달 ~ 오늘
  - 시간지정: 사용자 임의지정
  - 자동갱신 시간은 10초입니다, 단 동일한 프로그램이 10초 이상 사용중일때는 데이터 저장공간 효율을 위해 1분 단위로 갱신됩니다.
* 1.2. 검색
  - 프로세스명 또는 프로그램 제목으로 데이터를 검색할 수 있습니다. 검색 조건은 대소문자 구분없이 두가지 필드를 검색하며 한 글자라도 포함되면 검색합니다.
* 1.3. 제한
  - 설정에서 제한기능 사용 체크박스를 클릭해야 제한기능이 실행됩니다.
  - 프로세스명이나 프로그램 제목을 이용하여 프로그램 제한시간을 설정할 수 있습니다. 제한시간이 되기 5분, 1분전 알림을 주고 제한시간을 넘어가면 해당 프로그램이 강제 종료됩니다.
  - 프로세스명은 정확히 일치해야하며, 프로세스명만으로 제한 리스트에 추가할 수 있습니다. 그리고 프로그램 제목도 추가하면 프로세스명과 프로그램 제목을 동시에 조건을 갖추어야 카운트됩니다.
  - 프로세스명과 프로그램 제목이 동일한 리스트는 중복으로 만들 수 없습니다.
  - 예를들면 프로세스명 chrome.exe 프로그램 제목 YouTube 제한시간 60분
  - 예를들면 프로세스명 League of Legends.exe 프로그램 제목 (입력안함) 제한시간 120분
* 1.4. 설정
  - 제한기능 사용유무를 설정할 수 있습니다.
  - 실시간 순위집계는 llpv 홈페이지에 프로세스 순위 집계에 정보를 제공합니다. (개인적인 정보는 외부로 노출되지 않습니다.)
  - 알람 기능은 지정한 알림 시간만큼 컴퓨터를 사용하면 윈도우 화면잠금이 되고 휴식시간이 지나면 트레이 알림이 옵니다. (반복)
  - 데이터 삭제 버튼은 '검색'탭에서 볼 수 있는 저장된 데이터들을 삭제합니다
* 1.5. 메모
  - 간단한 메모 기능입니다. 한줄 한줄 작성할 때마다 왼쪽 공간에 시간이 기록됩니다. (자동저장 시간 10초)

* 다국어 기능 지원
  - llpv.properties에서 lang 값을 변경해주시면 됩니다.
  
## 2. 사양
	운영체제: Windows (정확한 프로세스명을 가져오기 위해 관리자 권한으로 실행을 권장합니다.)
	HDD: 최소 10MB 
	DB: H2
	JAVA: 1.8 이상
     
## 3. 홈페이지
https://www.llpv.kr

## 마무리
llpv.exe 바로가기를 시작프로그램에 등록하면 더 효율적으로 사용할 수 있습니다.   
[llpv_agent - Source Repository](https://github.com/eunbok/llpv_agent)   
질문이나 요청사항은 git 이슈에 남겨주세요.   
