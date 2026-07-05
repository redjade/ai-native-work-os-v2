# Codex와 Claude Code 선택 안내

## 먼저 알아둘 점

Codex와 Claude Code는 모두 저장소를 읽고, 파일을 수정하고, 명령을 실행하고, 결과를 검토할 수 있는 코딩 에이전트입니다. 현재 두 제품 모두 데스크톱·터미널·클라우드·모바일 작업 경로를 제공하므로, 초보자의 첫 프로젝트에서 핵심 능력 차이는 크지 않습니다.

수업의 목표는 특정 제품 숙련이 아닙니다. 어떤 도구를 선택하더라도 같은 산출물 루프를 사용합니다.

> 정의 → 위임 → 검증 → 기록 → 공유 → 개선

## 파일럿 운영 원칙

- 강사 시연의 기본 화면: **macOS의 Codex 앱**
- 참가자 선택 트랙: Codex 또는 Claude Code
- 공통 과제: `PROJECT.md`, 작업 지시서, 검증 기록, README
- 제품별 명령은 별도 안내서에서만 다룸
- 평가에서 제품 선택이나 모델 이름은 점수에 포함하지 않음
- 한 프로젝트에서 두 도구의 결과를 불필요하게 경쟁시키지 않음

Codex 앱을 기본 시연 화면으로 선택한 이유는 초보자가 프로젝트 폴더, 대화, 변경사항, Git diff와 실행 결과를 한 화면에서 확인하기 쉽기 때문입니다. 이것은 성능 우열 판단이 아니라 첫 수업의 설명 비용을 줄이기 위한 운영 결정입니다.

## 초보자 관점 비교

| 기준 | Codex | Claude Code |
|---|---|---|
| 첫 화면 | 전용 Codex 앱에서 프로젝트와 작업 스레드를 분리하기 쉬움 | Claude의 Chat과 Code를 오가며 질문과 제작을 이어 가기 쉬움 |
| 로컬 작업 | 앱·CLI·IDE에서 로컬 폴더 작업 가능 | 데스크톱 Code 화면·CLI·IDE에서 로컬 폴더 작업 가능 |
| 변경 확인 | 앱의 diff와 Git 도구가 초보자 설명에 유리 | 대화 중심으로 작업 흐름을 이어 가기 편하고 CLI 제어가 강함 |
| 모바일 | ChatGPT 모바일 앱에서 연결된 Mac·Windows의 Codex를 제어 가능 | Claude 모바일 앱의 Code 탭과 원격 제어를 통해 세션 이용 가능 |
| 클라우드 | GitHub 저장소와 클라우드 환경을 연결해 원격 작업 가능 | GitHub 저장소를 연결해 웹·모바일에서 원격 작업 가능 |
| macOS 설치 | 전용 앱부터 시작한 뒤 필요할 때 CLI로 확장 가능 | 앱 또는 CLI에서 시작 가능하며 터미널 사용 흐름이 자연스러움 |
| Windows 설치 | 전용 앱을 중심으로 시작하기 비교적 단순함 | 가능하지만 Git for Windows·PowerShell·WSL 선택에 따라 설명이 늘 수 있음 |
| 대화 경험 | ChatGPT와 같은 계정 생태계에서 일반 대화와 Codex를 사용 | Claude Chat과 Code가 한 앱 안에서 가까워 질문에서 작업으로 전환하기 편함 |
| 잘 맞는 참가자 | 파일 변경과 검토 과정을 화면에서 명확히 보고 싶은 사람 | Claude 대화를 이미 선호하고 대화에서 코드 작업으로 자연스럽게 이어 가고 싶은 사람 |

기능과 제공 범위는 계정, 구독, 조직 정책 및 앱 버전에 따라 달라질 수 있습니다. 수업 전 각 계정에서 실제로 보이는 기능을 확인합니다.

## 이렇게 선택합니다

### Codex를 먼저 선택하기 좋은 경우

- ChatGPT 계정을 이미 주로 사용한다.
- 앱 안에서 프로젝트, 변경사항과 Git diff를 보고 싶다.
- 터미널보다 전용 프로젝트 화면으로 시작하고 싶다.
- Mac이나 Windows 작업을 ChatGPT 모바일 앱에서 이어 가고 싶다.

### Claude Code를 먼저 선택하기 좋은 경우

- Claude의 대화 방식과 화면을 이미 선호한다.
- 일반 질문, 문서 검토와 코드 작업을 같은 Claude 경험에서 이어 가고 싶다.
- 터미널을 조금씩 배우는 것에 거부감이 없다.
- Claude 모바일·웹의 Code 작업 흐름을 사용하고 싶다.

### 아직 모르겠다면

Codex 앱을 주 도구로 선택합니다. 첫 결과물을 만든 뒤 같은 `PROJECT.md`와 작업 지시서를 Claude Code에서 읽혀 보고, 자신에게 더 이해하기 쉬운 도구로 바꿀 수 있습니다.

## 두 도구를 모두 준비하는 방법

두 도구를 모두 설치하되 역할은 다음처럼 나눕니다.

- 주 도구: 파일 수정과 실행
- 보조 도구: 설명 요청 또는 읽기 전용 검토

두 도구가 동시에 같은 파일을 수정하게 하지 않습니다. 보조 도구의 제안은 사람이 검토한 뒤 주 도구에 반영합니다.

## 공통 첫 과제

어느 도구를 선택하든 다음 요청을 사용합니다.

```text
이 프로젝트의 PROJECT.md와 README.md를 읽어 주세요.
아직 파일을 수정하지 말고 다음을 알려 주세요.

1. 이해한 프로젝트 목표
2. 완료 조건
3. 가장 작은 첫 결과물
4. 필요한 파일
5. 예상 위험과 검증 방법
```

이 답변을 참가자가 이해하고 수정할 수 있으면 첫 도구로 사용할 준비가 된 것입니다.

## 공식 참고 자료

- [Codex 개요](https://developers.openai.com/codex/overview)
- [Codex 앱 기능](https://developers.openai.com/codex/app/features)
- [Codex 원격 연결](https://developers.openai.com/codex/remote-connections)
- [Claude Code 시작하기](https://docs.anthropic.com/en/docs/claude-code/getting-started)
- [Claude Code on the web](https://support.claude.com/en/articles/12618689-claude-code-on-the-web)
- [Claude 모바일에서 Code 세션 열기](https://support.claude.com/en/articles/14898120-open-the-claude-mobile-app-with-a-link)

