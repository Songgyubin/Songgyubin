![header](https://capsule-render.vercel.app/api?type=waving&color=364765&textBg=282829&fontColor=FAF7F5&height=300&section=header&text=Songgyubin&desc=Android%20Developer&fontSize=40)


[![js](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thd0427@gmail.com)

## 🚀 Contributor to


### NowInAndroid
[NowInAndroid](https://github.com/android/nowinandroid)는 최신 안드로이드 개발을 보여주는 프로젝트입니다.

<details>
  <summary><strong>✨ Recent Contributions: 화면이 오버랩되는 버그 수정</strong></summary>
  
  - [PR #1573: Fix Overlap When Moving Between Tabs](https://github.com/android/nowinandroid/pull/1573)
  - [Issue #1523: Quickly switching the bottom tabs can cause the screens of two tabs to overlap](https://github.com/android/nowinandroid/issues/1523)
  - **참고:** [navigation library 문제 제기](https://issuetracker.google.com/issues/338975163#comment11), [adaptive library 문제 제기](https://issuetracker.google.com/issues/360717840)
  
</details>

---
### DroidKaigi
[DroidKaigi](https://github.com/DroidKaigi/conference-app-2024)는 일본에서 열리는 연례 안드로이드 컨퍼런스를 위한 오픈 소스 앱입니다.
<details>
  <summary><strong>✨ Recent Contributions: 구성 변경 시 데이터 유지되지 않는 부분 개선</strong></summary>

  - [PR #941: fix input values not maintained](https://github.com/DroidKaigi/conference-app-2024/pull/941)  
  - [Issue #737: In ProfileCardScreen, edited content disappears when screen size is changed while editing a Profile](https://github.com/DroidKaigi/conference-app-2024/issues/737#event-14129178164)
  
</details>

---
### oh-my-claudecode
[oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)는 Claude Code를 위한 멀티 에이전트 오케스트레이션 레이어입니다.
<details>
  <summary><strong>✨ Recent Contributions: 플러그인 컨텍스트에서 omc update 시 CLAUDE.md 버전이 갱신되지 않는 버그 수정</strong></summary>

  - [PR #2002: fix(installer): update CLAUDE.md even when running in plugin context](https://github.com/Yeachan-Heo/oh-my-claudecode/pull/2002)
  - **문제:** Claude Code 세션 내에서 `omc update` 실행 시 `CLAUDE_PLUGIN_ROOT` 환경 변수가 자식 프로세스에 상속되어 CLAUDE.md 업데이트 블록이 통째로 스킵되는 버그
  - **수정:** CLAUDE.md 업데이트 블록을 `!runningAsPlugin` 가드 밖으로 이동하고 `!projectScoped` 조건으로 대체
  
</details>
