# Rinux2
### Ubuntu
#### 1. 리눅스란 ?
- 리누스 베네딕트 토르발스가 리눅스 커널을 최초 개발
- GNU 프로젝트에 의해 응용 프로그램(기본 인터페이스, 문서 편집 등)의 추가
- 리눅스 커널과 GNU 프로젝트에 의한 응용 프로그램들을 합쳐 일반 사용자에게 배포
- 리눅스는 리눅스 커널을 의미
- 리눅스 운영체제는 리눅스 배포판(리눅스 커널 + 응용 프로그램)을 의미
- 리눅스 배포판
  - 리눅스 커널과 여러 가지 유틸리티를 합친 운영체제
  - 계열
    - Red Hat
    - Debian
    - Slackware
  - 크게 세가지 계열에서 비롯된 수백 개의 배포판이 존재
#### 2. 우분투
- “타인을 향한 인간애(humanity to others)” 라는 의미를 가진 반투어 우분투에서 유래
- 리눅스 배포판 중에서도 인기가 많은 배포판(Top 5 이내)
- 데비안(Debian) 배포판의 파생
- 우분투는 데비안계열 리눅스 배포판
- 2년마다 LTS(Long Term Support) 버전 배포
- 우분투의 특징
  - Windows에 비해 가벼운 운영체제
  - 여러 사용자가 동시에 접속, 작업가능
  - 자유로운 수정 가능
  - 완전 무료
  - 개인용 환경과 서버 환경에 최적화 되어있음.
  - 자세한 스펙 : https://ko.wikipedia.org/wiki/%EC%9A%B0%EB%B6%84%ED%88%AC_(%EC%9A%B4%EC%98%81_%EC%B2%B4%EC%A0%9C)
- 우분투 Desktop 버전의 기본 어플리케이션 (18.04 LTS 기준)
  - GUI 인터페이스 : GNOME
  - 파일관리 : Nautilus(노틸러스)
  - 웹브라우저 : Firefox(파이어폭스)
  - 오피스 문서 프로그램 : Libre office(리브레오피스)
  - 소프트웨어 매니저 : Ubuntu Software (우분투 소프트웨어)
  - 터미널 : GNONE Terminal (그놈 터미널)
  - 음악 프로그램 : Rhythmbox
  - 그외 수 많은 어플리케이션!
#### 3. 우분투 단축키
- 단축키 설정 및 확인 방법
  - 런처에서 설정(Settings) -> Keyboard(키보드) 클릭
  - 대시홈에서 설정(Settings) 검색 후 실행 -> Keyboard(키보드) 클릭
- 유용한 단축키
  - Super 한번 : window 및 workspace 펼치기
  - Super + 화살표 위 : window 최대화
  - Super + 화살표 아래 : window 최대화 풀기
  - Super + Tab : window 변경
  - Alt + F4 : window 닫기
  - Ctrl + Alt + T : 터미널 새로 열기
  - Super + D : 열려있는 모든 window 내리기
  - Super + PageUp / PageDown : 작업공간 변경
  - Ctrl + Space : 한/영 전환
  - etc.
#### 4. 우분투 시스템 종료 방법
- 메뉴 바 오른쪽의 전원버튼을 클릭하여 컴퓨터끄기
- 메뉴 바 오른쪽의 화살표 버튼 -> 컴퓨터 끄기/ 로그아웃 -> 컴퓨터 끄기
- 터미널/콘솔(CUI)로 종료 명령 실행
  - >power off
  - >shutdown -h now
  - >halt
  - >init 0
#### 5. 시스템 사용자 인터페이스
- 컴퓨터와 상호작용하는 방법
  - GUI(Graphical User Interface) : 그래픽으로 구현된 파일/폴더를 이용하는 방법
  - CUI(Character User Interface)  : 텍스트로 주고 받는 방법
  - GUI와 CUI의 비교 
    - 그래픽 처리를 위한 리소스의 필요 유무
    - 컴퓨터에 대해 내릴 수 있는 명령 수준의 한계
    - 사용자에 따라 다른 사용성
- Command Line Interface : 콘솔
  - 사용자가 할당되는 작업 공간
  - 시스템의 로컬 환경에서 작동됨을 의미
  - 사용자가 내리는 명령을 쉘(Shell)에게 전달
  - Ctrl + Alt + F3~F6 : tty3번 콘솔부터 tty6번 콘솔까지의 콘솔로 전환
- Command Line Interface : 터미널
  - 사용자가 할당되는 작업 공간
  - 콘솔의 의미에서 확장해 원격 제어를 위한 콘솔의 의미
  - 사용자가 내리는 명령을 쉘(Shell)에게 전달
  - Ctrl + Alt + t 혹은 대쉬홈에서 Terminal검색해 실행
#### 6. 파일과 파일 시스템
- 파일
  - 메모리 상에 있는 바이트의 연속으로 이루어진 정보
  - 리눅스는 입출력 장치를 포함한 모든 장치를 파일로 취급
- 파일 시스템
  - 컴퓨터에서 파일이나 자료를 쉽게 발견 및 접근할 수 있도록 보관 또는 조직하는 체제
  - 각각의 운영체제는 각자의 정책에 따라 다른 파일 시스템을 갖음
  - 메모리 주소가 가리키는 공간에 저장된 데이터를 파일과 디렉토리라는 논리적 공간으로 관리
  - 컴퓨터의 기억 장치 상에 존재하는 데이터들의 위치를 인간이 구별할 수 있도록 하는 논리적 구조
- 리눅스 파일 종류
  - 일반 파일(regular file)
  - 텍스트 파일 : 파일 내용을 확인하는 기능의 명령으로 확인 가능
  - 바이너리 파일 : 파일 유형에 맞는 응용 프로그램을 통해 확인 가능
    - 실행 파일
    - 이미지 파일
  - 디렉토리(Directory) : 데이터를 보관하는 논리적 공간
  - 심벌릭 링크(Symbolic link) : 원본 파일을 대신하는 링크 파일
  - 장치 파일(Device) : 하드 디스크, 키보드, 마우스 등 시스템에 부착되어 있는 장치들
- 디렉토리
  - 메모리의 저장 곤간에 대한 이름 공간(폴더)
  - 물리적으로 저장된 데이터를 논리적(개념적)이름과 연결한 것
![image](https://user-images.githubusercontent.com/78472987/112283816-e13c3080-8ccb-11eb-99a6-f24fa5bce31b.png)
