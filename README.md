# SWITCH RUN! — Windows 친구 QA

**Windows 10/11 · 64비트 · 게임 0.62.39 / QA 패키지 qa1**

친구들과 주먹·밀기·잡기·랜덤 능력으로 방해하고 추월하는 파티 마라톤입니다. 혼자+AI 또는 사람과 AI를 합쳐 최대 8명이 플레이합니다.

**[EXE 설치본 다운로드](https://github.com/aijongjae-source/switch-run-playtest/releases/download/v0.62.39-qa1/SwitchRun-0.62.39-qa1-Windows.exe)** · **[설치 없는 ZIP 다운로드](https://github.com/aijongjae-source/switch-run-playtest/releases/download/v0.62.39-qa1/SwitchRun-0.62.39-qa1-Windows.zip)**

[파일 확인용 SHA-256](https://github.com/aijongjae-source/switch-run-playtest/releases/download/v0.62.39-qa1/SwitchRun-0.62.39-qa1-Windows.sha256) · [전체 사용 안내](QA-GUIDE.ko.txt)

다운로드와 게임 실행에 GPT, GitHub, Steam 계정이 필요하지 않습니다. EXE는 현재 사용자에게 게임 파일을 설치하고 바탕화면 바로가기를 만듭니다. ZIP은 전체 압축을 푼 뒤 `게임 실행.cmd`로 실행하세요. 필요한 파일이 함께 있으므로 `SwitchRun.exe`만 따로 옮기면 안 됩니다.

## 혼자 플레이

플레이 → 혼자 달리기 → 참가 인원/AI 성향 → 로비 만들기 → 경주 시작. 참가 인원 1명은 혼자, 2~8명은 나+AI입니다.

## 다른 집의 친구들과 멀티

1. 모두 [공식 Radmin VPN](https://www.radmin-vpn.com/help/)을 설치합니다. 원격 제어용 Radmin Server는 필요 없습니다.
2. 한 명이 VPN 네트워크를 만들고, 친구들은 같은 이름과 비밀번호로 참가합니다.
3. 게임 방장은 플레이 → 방 만들기. 필요하면 빈자리를 AI로 채웁니다.
4. 친구들은 플레이 → 방 참가에서 **Radmin 창에 표시된 방장 IP:7777**을 입력합니다.
5. 친구들이 준비 완료하면 방장이 경주 시작을 누릅니다.

같은 공유기에서는 VPN 없이 게임 로비의 주소 복사를 사용해도 됩니다. 기본 전송은 UDP 7777이며 같은 QA 버전끼리 접속해야 합니다. 다른 집에서 일반 `192.168.x.x` 주소로는 접속할 수 없습니다. 방화벽에서 해당 게임의 통신을 허용하되 방화벽 전체를 끄지 마세요. 게임 안에 자동 중계/방 코드는 없으며 Radmin을 사용하면 공유기 포트 개방 대신 가상 LAN으로 연결합니다.

## 조작과 제보

WASD 이동 · 마우스 시점 · Space 점프 · 왼쪽 클릭 공격 · 오른쪽 누르는 동안 뒤돌아보기 · E 잡기 · Q 밀기 · Shift 능력 · Esc 메뉴 · F1 조작법 · Alt+Enter 전체 화면.

맵별 테스트는 게임 폴더의 `맵 테스트`를 사용하세요. 발견한 문제는 포함된 `QA 제보 양식.txt`에 버전·맵·능력·인원·재현 순서를 적어 개발자에게 보내 주세요. 로그가 자동 전송되지는 않습니다.

개발 중인 미서명 QA 배포입니다. Windows의 게시자/SmartScreen 확인이 나타날 수 있습니다. 원본 링크와 SHA-256을 확인하세요. 기존 꾸미기/설정은 PC에 보관하며 설치본 제거 시 삭제하지 않습니다.

이 공개 저장소는 실행 파일과 테스트 안내 배포용입니다. 개발 소스 저장소는 별도로 비공개 관리합니다. 게임·에셋을 오픈소스로 제공하는 저장소는 아니며 포함된 각 제3자 라이선스는 패키지에서 확인할 수 있습니다.

검증 범위: 실제 설치/제거와 한 PC에서 싱글·8인 AI·두 실행본 ENet 연결을 검사합니다. **실제 다른 PC 간 Radmin/WAN, 사람 플레이·음향, 장시간 성능은 지인 QA로 확인할 항목입니다.** 브라우저 테스트판과 연결되지 않습니다.

## English quick start

Download the EXE installer, or extract the entire ZIP and run `게임 실행.cmd`. No Steam/GPT/GitHub login is needed. Select English on the game's first screen. Choose Play → Solo for AI races. For Internet multiplayer, everyone joins the same [Radmin VPN network](https://www.radmin-vpn.com/help/); the host creates a game and guests join the host's **Radmin IP:7777**. Use the same QA version and allow the game through the appropriate firewall interface. Host migration and joining a race already in progress are not supported. Two-process tests on one PC do not certify multi-PC VPN/Internet play.
