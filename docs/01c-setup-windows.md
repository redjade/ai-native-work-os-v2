# Windows 설치 안내

Windows도 과정 전체를 지원합니다. 다만 터미널 종류, Git Bash, PowerShell과 WSL 선택 때문에 macOS보다 설치 경로가 다양할 수 있습니다. 초보자는 먼저 전용 앱과 PowerShell을 사용하고, WSL은 프로젝트에 필요할 때만 추가합니다.

## 목표 상태

- Git이 설치되어 있다.
- GitHub에 로그인할 수 있다.
- Obsidian에서 수업 작업 폴더를 열 수 있다.
- Codex 또는 Claude Code 중 주 도구 하나가 작동한다.
- 테스트 프로젝트의 `README.md`를 읽을 수 있다.
- 실제로 작업 중인 폴더 경로를 확인할 수 있다.

## 1. Windows 기본 확인

- [ ] Windows 업데이트를 확인했다.
- [ ] 프로그램 설치 권한을 확인했다.
- [ ] 저장공간이 10GB 이상 남아 있다.
- [ ] 파일 탐색기에서 파일 확장자 표시를 켰다.
- [ ] PowerShell을 실행할 수 있다.

## 2. Git 설치와 확인

1. [Git for Windows](https://git-scm.com/download/win)를 설치합니다.
2. 설치 후 PowerShell을 다시 엽니다.
3. 다음을 실행합니다.

```powershell
git --version
```

버전이 표시되는지 확인합니다. 수업에서는 PowerShell을 기본 터미널로 사용하고, Claude Code에 Git Bash가 필요한 경우에만 추가 설정합니다.

## 3. Obsidian 설치

1. [Obsidian 다운로드](https://obsidian.md/download)에서 Windows 앱을 설치합니다.
2. 수업용 폴더를 새 볼트로 만듭니다.
3. 첫 파일로 `HOME.md`를 만듭니다.
4. 초기에는 플러그인을 최소한으로 유지합니다.

## 4A. Codex를 주 도구로 선택한 경우

1. [Codex 시작 안내](https://developers.openai.com/codex/quickstart)를 확인합니다.
2. Codex 앱을 설치하고 로그인합니다.
3. 테스트 프로젝트 폴더를 앱에 추가합니다.
4. 실제 선택된 폴더 경로를 확인합니다.
5. 다음 요청으로 읽기 테스트를 합니다.

```text
이 폴더의 파일 목록과 README.md의 목적을 설명해 주세요.
파일은 수정하지 마세요.
```

## 4B. Claude Code를 주 도구로 선택한 경우

Claude Code의 Windows 설치 방법은 앱 버전과 설치 방식에 따라 달라질 수 있습니다. [공식 설치 안내](https://docs.anthropic.com/en/docs/claude-code/getting-started)의 Windows 항목을 우선 사용합니다.

가능한 경로:

- Windows용 공식 설치 방법
- PowerShell과 Git for Windows
- Git Bash
- 필요한 프로젝트에 한해 WSL

초보자는 WSL을 자동으로 선택하지 않습니다. 강사가 프로젝트 요구사항과 오류 상태를 확인한 뒤 결정합니다.

설치 후 새 PowerShell 또는 Git Bash에서 확인합니다.

```text
claude --version
```

## 5. 테스트 프로젝트

문서 폴더나 바탕화면 대신 짧은 영문 경로를 권장합니다.

```text
C:\projects\ai-workspace\test-project\
  README.md
  PROJECT.md
```

OneDrive 동기화 폴더와 Git 저장소를 처음부터 겹쳐 사용하면 파일 충돌이 생길 수 있습니다. 수업 초기에는 로컬 프로젝트 폴더 하나를 기준으로 사용합니다.

## 6. 설치 완료 확인

- [ ] `git --version`이 작동한다.
- [ ] 파일 확장자가 보인다.
- [ ] Obsidian에서 작업 폴더가 열린다.
- [ ] 주 도구가 테스트 프로젝트를 읽는다.
- [ ] PowerShell, Git Bash 또는 WSL 중 실제 사용하는 터미널을 알고 있다.
- [ ] 변경 전 계획과 변경 후 diff를 확인할 수 있다.
- [ ] GitHub 비공개 저장소 초대를 수락했다.

## 오류 전달 형식

```text
Windows 버전:
선택한 도구:
사용한 터미널:
실행한 명령:
전체 오류 메시지:
마지막으로 정상 작동한 단계:
```

비밀번호, API 키 또는 로그인 복구 코드는 오류 화면과 함께 보내지 않습니다.

