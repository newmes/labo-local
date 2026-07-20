<h1 align="center">LABO</h1>

<p align="center"><strong>Lab Orchestrator — 연구실을 위한 AI 협업 워크스페이스</strong><br/>
회의, 문헌, 집필, 개발까지 연구실의 일이 한곳에서 이어집니다.</p>

<p align="center"><sub><a href="README.md">English</a> · 한국어</sub></p>

<h3 align="center"><a href="https://github.com/newmes/labo-local/releases"><ins>다운로드</ins></a> · <a href="https://labo.parrotvox.com">웹사이트</a></h3>

---

<p align="center">
  <img src="docs/assets/hero-chat-thread.png" alt="LABO 연구방: 왼쪽은 랩미팅 챗, 오른쪽은 논문 서지가 붙은 디스커션 스레드" width="960" />
</p>

## LABO는

연구 하나에 필요한 도구들이 너무 많습니다. 랩미팅은 녹음 앱으로, 논문은 서지 관리 도구와 구글 스콜라로, 집필은 Overleaf, 코드는 GitHub. LABO는 이 흐름 전체를 워크스페이스 하나로 모으고, 그 사이를 메신저가 잇습니다. 연구원 각자의 AI 에이전트를 방에 초대하세요.

| | |
|---|---|
| **회의록** | 랩미팅이 그대로 회의록이 되고, 확인한 할 일을 작업판에 올립니다. |
| **문헌 서재** | 대화에 인용한 논문이 서지·PDF와 함께 방 서재에 자동 등록되고, 필기하거나 논문 토론을 열 수 있습니다. |
| **LaTeX 집필** | 문헌과 같은 방에서 초안부터 컴파일까지 이어집니다. |
| **개발 세션** | 각자 쓰는 코딩 에이전트를 방에 연결합니다. 지금은 Claude Code와 Codex를 연결할 수 있고, Cursor는 지원 확대 중입니다. |
| **봇 함대** | 모든 에이전트를 한 화면에서, 폰에서도 지켜봅니다. |

## 로컬 우선

LABO 데스크탑 앱은 원격 프로필과 내 컴퓨터 프로필을 지원합니다. 데이터가 어디에 저장되는지는 고른 프로필에 따라 달라집니다. 원격 프로필은 운영 서버에 방을 두어 팀이 함께 작업하고, 내 컴퓨터 프로필은 백엔드가 내 컴퓨터에서 돌아가고 대화, 문서, 논문도 그곳에 저장됩니다. 프로필은 앱을 처음 설정할 때 고릅니다.

팀원과 방을 공유할지는 선택입니다. 공유 방의 종단 간 암호화는 준비 중입니다. 릴레이는 암호문을 그대로 전달하도록 만들어 두었지만 키 관리는 아직 제공하지 않아서, 지금은 완료된 기능이 아닙니다.

LABO는 AI 사용권을 재판매하지 않습니다. 연결한 코딩 에이전트 사용량은 해당 제공사의 본인 구독에 포함됩니다. 음성 인식, 회의록, 이미지 생성 등 일부 기능은 별도 외부 서비스를 사용하며 처리 방식은 데이터 전송 안내에 표시합니다.

## 설치

공식 릴리스 페이지 [github.com/newmes/labo-local/releases](https://github.com/newmes/labo-local/releases)에서 운영체제에 맞는 설치 파일을 받으세요.

| OS | 파일 |
|---|---|
| Windows | `labo-desktop-*-setup.exe` |
| macOS (Apple Silicon 전용) | `Labo-*-arm64.dmg` |
| Linux | `Labo-*.AppImage` |

macOS는 Apple Silicon(M 시리즈) 전용입니다. 인텔 맥은 지원하지 않습니다.

**받은 파일을 검증하세요.** 릴리스마다 파일별 SHA-256 체크섬을 함께 올립니다. 내려받은 뒤 파일의 체크섬을 계산해 릴리스 페이지에 적힌 값과 같은지 확인한 다음 설치하세요.

- macOS / Linux: `shasum -a 256 <파일>`
- Windows(PowerShell): `Get-FileHash <파일> -Algorithm SHA256`

아직 코드서명 전이라 설치할 때 운영체제 경고가 뜰 수 있습니다. 위 공식 릴리스 페이지에서 받고 체크섬까지 확인한 파일에 한해서만 경고를 넘기세요. Windows는 SmartScreen에서 **추가 정보 → 실행**, macOS는 **우클릭 → 열기**로 진행합니다.

## 얼리액세스

지금은 승인제 얼리액세스로 운영하고 있습니다. [웹사이트](https://labo.parrotvox.com)에서 신청해 주세요.

<p align="center">
  <img src="docs/assets/feature-kanban.png" width="49%" />
  <img src="docs/assets/feature-journal-pdf.png" width="49%" />
</p>
<p align="center">
  <img src="docs/assets/feature-writing.png" width="49%" />
  <img src="docs/assets/feature-docs.png" width="49%" />
</p>

<sub>스크린샷 속 인물과 데이터는 모두 가상으로 연출한 데모 연구방입니다.</sub>
