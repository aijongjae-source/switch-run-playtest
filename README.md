# SWITCH RUN! — Windows QA

현재 다운로드: **0.62.88-qa1**

**[설치본 EXE](https://github.com/aijongjae-source/switch-run-playtest/releases/download/v0.62.88-qa1/SwitchRun-0.62.88-qa1-Windows.exe)** · **[무설치 ZIP](https://github.com/aijongjae-source/switch-run-playtest/releases/download/v0.62.88-qa1/SwitchRun-0.62.88-qa1-Windows.zip)** · [SHA-256](https://github.com/aijongjae-source/switch-run-playtest/releases/download/v0.62.88-qa1/SwitchRun-0.62.88-qa1-Windows.sha256)

Windows QA 0.62.88 — LAN 설정·동시 방 검색 수정

- 게임 시작 때 방을 만들기 전부터 Windows LAN 통신 허용 상태를 확인합니다. 방장·참가자 모두 같은 ‘LAN 연결 설정’을 사용합니다.
- 허용 규칙이 없으면 ‘LAN 연결 설정 → 이 게임 LAN 허용’을 누르고 Windows 권한 창을 직접 확인하세요. 현재 게임 실행 파일의 UDP 통신만 같은 네트워크(LocalSubnet)의 개인·공용 프로필에서 허용합니다. 방 검색의 임시 응답 포트도 포함합니다.
- Windows 알림이 꺼진 공용 네트워크에서도 상태를 안내합니다. 게임이 방화벽 전체나 네트워크 분류를 바꾸지는 않습니다. 설치 경로·버전이 바뀌면 다시 확인해야 합니다.
- 여러 친구가 동시에 방을 검색할 때 한 사람에게만 응답하던 문제를 수정했습니다. 기존 7자리 코드·인원·인증 방식은 유지합니다.
- 이전086의 결승 관중/울타리 그림자/비눗방울/벼락산 수정도 포함합니다.

**SmartScreen 경고는 미해결입니다. 이 QA 설치본과 게임 EXE는 아직 정식 서명이 없습니다. ‘Windows의 PC 보호’가 사라졌다는 배포가 아닙니다.** 신뢰된 게시자 서명·평판 또는 Microsoft Store 배포가 별도로 필요합니다. 백신/SmartScreen 비활성화·자체 인증서 우회 기능은 넣지 않았습니다.

양쪽 PC가 같은088qa1을 새로 받아야 합니다. EXE 설치본 또는 무설치 ZIP을 사용하세요. ZIP은 전체 압축을 풀고 게임 실행.cmd를 실행합니다. GitHub 자동 Source code ZIP은 게임 실행본이 아닙니다. GPT·GitHub·Steam 계정은 필요 없습니다.

같은 공유기는 근처 방/7자리 코드로 접속합니다. 코드는 인터넷 중계·IP 익명화·비밀번호가 아닙니다. 게스트 Wi-Fi·PC방 단말 격리·관리자 차단은 이 설정으로 해제되지 않습니다. 서로 다른 집은 별도 VPN 또는 방장 UDP 포워딩이 필요합니다.

검증: 실제UDP동시3질의, Windows읽기전용 상태, 동일LAN소스의087 Main/ENet 코드입장239조건, 정확PCK의메뉴, 실제WindowsEXE2개 입장·경주·snapshot, 설치·제거를 확인했습니다. 실제UAC허용/방화벽규칙추가/물리2PC/WAN/SmartScreen통과/사람조작청음/일반FPS는 미검증입니다. 기존MTU경고·대량ENet누락·호스트지연은OPEN입니다.

[접속 안내](QA-GUIDE.ko.txt) · [현재 릴리스](https://github.com/aijongjae-source/switch-run-playtest/releases/tag/v0.62.88-qa1)
