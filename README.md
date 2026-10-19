# SWITCH RUN! — Windows 멀티플레이 다운로드

**최신 버전0.62.46 · Windows10/11 64비트 · 최대8명 · 계정 불필요**

친구들과 주먹·밀기·잡기·랜덤 능력으로 방해하고 추월하는 파티 마라톤입니다. 혼자+AI 또는 사람과AI를 합쳐 최대8명이 플레이합니다.

**[설치본 EXE 다운로드](https://github.com/aijongjae-source/switch-run-playtest/releases/download/v0.62.46-qa1/SwitchRun-0.62.46-qa1-Windows.exe)** · **[무설치 ZIP 다운로드](https://github.com/aijongjae-source/switch-run-playtest/releases/download/v0.62.46-qa1/SwitchRun-0.62.46-qa1-Windows.zip)**

[릴리스/변경 내용](https://github.com/aijongjae-source/switch-run-playtest/releases/tag/v0.62.46-qa1) · [SHA-256](https://github.com/aijongjae-source/switch-run-playtest/releases/download/v0.62.46-qa1/SwitchRun-0.62.46-qa1-Windows.sha256) · [접속 안내](QA-GUIDE.ko.txt)

EXE는 설치 후 바탕화면 바로가기로 실행합니다. ZIP은 전체 압축을 풀고 `게임 실행.cmd`를 실행하세요. GPT·GitHub·Steam 계정이나 구매가 필요하지 않습니다. 친구들도 모두 같은0.62.46-qa1 버전을 사용하세요.

## 혼자 하기

플레이 → 혼자 달리기 → 인원/AI 성향 → 로비 만들기 → 경주 시작.

## 친구와 멀티

같은 공유기/가상LAN에서 방장은 플레이 → 방 만들기, 친구는 플레이 → 방 참가에서 **방장IP:7777** 입력 → 준비 완료 → 방장이 시작합니다.

다른 집에서는 기존과 같이 [Radmin VPN](https://www.radmin-vpn.com/help/)의 같은 네트워크에 참가하고 **방장의Radmin IP:7777**로 접속하거나, 방장 공유기의 **UDP7777** 포트 전달을 사용합니다. 자동 매칭/Steam 중계는 없습니다. 방장도 게임을 켜 두어야 하며 진행 중 참가·호스트 이전은 지원하지 않습니다.

## 이번 업데이트

041자동 자리바꾸기·042관측 고정·043토끼와 거북이·044헤르메스의 신발·045멋쟁이 포징·벼락산 및 누적 최소 안정화 수정을 포함합니다. 일반 추첨45능력/맵후보26입니다.

실제0.62.46 실행본의 시작 화면과 한PC 두 실행본의ENet 접속(2유저+1AI)을 확인했습니다. 실제 타PC/VPN/WAN·모든 조합·사람조작/청음·수시간 안정성은 이번 배포에서 검증하지 않았습니다. 전체 프레임 저하나 대량 전송 누락을 모두 해결했다는 의미는 아닙니다.

코드 서명이 없는 개발 테스트 배포입니다. 포함SHA-256으로 파일을 확인할 수 있습니다. 개발 소스는 별도 비공개로 관리합니다. 기존[0.62.39-qa1](https://github.com/aijongjae-source/switch-run-playtest/releases/tag/v0.62.39-qa1)은 역사 원본으로 유지합니다.
