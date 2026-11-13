# 에이전틱 AI 사용 지침

에이전틱 AI를 효과적이고 안정적으로 활용하기 위한 실무 지침을 정리하는 공간입니다.

## 지침 목록

<details>
<summary><strong>초기 프롬프트 작성</strong></summary>

초기 프롬프트를 설계할 때 참고할 수 있는 세부 항목입니다.

1. [목적과 기본 원칙](docs/INITIAL_PROMPT.md#1-목적과-기본-원칙)
2. [프로젝트 배경과 목표 설정](docs/INITIAL_PROMPT.md#2-프로젝트-배경과-목표-설정)
3. [작업 정의와 범위 설정](docs/INITIAL_PROMPT.md#3-작업-정의와-범위-설정)
4. [명확한 프롬프트 작성](docs/INITIAL_PROMPT.md#4-명확한-프롬프트-작성)
5. [맥락과 관련 정보 제공](docs/INITIAL_PROMPT.md#5-맥락과-관련-정보-제공)
6. [작업 분할](docs/INITIAL_PROMPT.md#6-작업-분할)
7. [검증 방법과 완료 기준 지정](docs/INITIAL_PROMPT.md#7-검증-방법과-완료-기준-지정)
8. [기존 프로젝트 사전 분석](docs/INITIAL_PROMPT.md#8-기존-프로젝트-사전-분석)
9. [AI 자율성 및 작업 권한 설정](docs/INITIAL_PROMPT.md#9-ai-자율성-및-작업-권한-설정)
10. [초기 프롬프트 체크리스트](docs/INITIAL_PROMPT.md#10-초기-프롬프트-체크리스트)
11. [초기 프롬프트 템플릿](docs/INITIAL_PROMPT.md#11-초기-프롬프트-템플릿)

</details>

<details>
<summary><strong>Codex 실행 환경 설정</strong></summary>

Codex의 모델, 추론 강도, 샌드박스, 승인 정책 및 기능을 설정하는 방법입니다.

1. [config.toml의 역할](docs/CODEX_CONFIG.md#1-configtoml의-역할)
2. [설정 파일 위치와 적용 범위](docs/CODEX_CONFIG.md#2-설정-파일-위치와-적용-범위)
3. [config.toml 생성 및 편집](docs/CODEX_CONFIG.md#3-configtoml-생성-및-편집)
4. [자주 사용하는 핵심 설정](docs/CODEX_CONFIG.md#4-자주-사용하는-핵심-설정)
5. [기본 설정 예시](docs/CODEX_CONFIG.md#5-기본-설정-예시)
6. [현재 설정 확인](docs/CODEX_CONFIG.md#6-현재-설정-확인)

</details>

<details>
<summary><strong>프롬프트 역설계</strong></summary>

잘 도출된 대화 결과를 분석하여 비슷한 결과를 재현할 수 있는 프롬프트를 도출하는 방법입니다.

1. [프롬프트 역설계의 목적과 원칙](docs/PROMPT_REVERSE_ENGINEERING.md#1-목적과-기본-원칙)
2. [역설계 진행 절차](docs/PROMPT_REVERSE_ENGINEERING.md#2-역설계-진행-절차)
3. [역설계 요청 프롬프트](docs/PROMPT_REVERSE_ENGINEERING.md#3-역설계-요청-프롬프트)
4. [도출한 프롬프트 검증](docs/PROMPT_REVERSE_ENGINEERING.md#4-도출한-프롬프트-검증)

</details>

## 문서 관리

<details>
<summary><strong>현재 레포지토리 관리 프롬프트</strong></summary>

현재 이 지침 저장소의 문서 구조와 파일을 생성·수정·관리할 때 사용하는 프롬프트입니다.

1. [레포지토리 관리 프롬프트](docs/REPOSITORY_MANAGEMENT.md#현재-레포지토리의-생성-및-관리-프롬프트)

</details>

새로운 지침 주제가 추가되면 이 페이지에 동일한 방식으로 접이식 목차를 추가하고,
세부 내용은 주제별 Markdown 파일로 관리합니다.

학습 및 활용 순서는 파일명의 번호가 아니라 이 README.md의 위에서 아래 순서로 관리합니다.
