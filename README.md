
# 메이플스토리 주간 보스 관리 도구

메이플스토리 주간 보스를 효율적으로 관리하기 위한 웹 애플리케이션입니다. 사용자는 캐릭터를 등록하고 주간 보스를 선택하여 결정석 가격을 계산할 수 있습니다.

---

## 주요 기능

### 1. 캐릭터 관리

<<<<<<< HEAD

- **캐릭터 검색:** 넥슨 API를 이용하여 캐릭터를 검색.
- **캐릭터 등록:** 검색한 캐릭터를 저장 및 관리.
- **캐릭터 선택 및 삭제:** 등록된 캐릭터를 선택하여 보스 관리 또는 삭제 가능.

### 2. 주간 보스 관리

- **보스 선택:** 보스 이미지를 클릭하여 보스를 선택하거나 해제.
- **난이도 설정:** EASY, NORMAL, HARD, EXTREME 등의 난이도를 설정 가능.
- **파티원 수 설정:** 보스별 파티원 수를 조정하여 총 가격 계산.
- **가격 계산:** 선택한 난이도와 파티원 수에 따라 결정석 가격 자동 계산.

### 3. 총 결정석 가격 계산

- **캐릭터별 총 결정석 가격:** 각 캐릭터의 선택된 보스들의 결정석 가격 총합 표시.
- **모든 캐릭터의 총 결정석 가격:** 등록된 모든 캐릭터의 결정석 가격 합산.

### 4. 사용자 경험 향상

- 반응형 레이아웃으로 다양한 화면 크기에 적응.
- 간결하고 직관적인 사용자 인터페이스.
- # 캐릭터와 보스 선택 시 애니메이션 효과 제공.
- **캐릭터 등록:** 넥슨 API를 이용해 캐릭터 검색 및 등록.
- **선택 및 삭제:** 등록된 캐릭터 선택 및 삭제 가능.
- **개별 보스 관리:** 각 캐릭터마다 독립적인 주간 보스 관리 인터페이스 제공.

### 2. 주간 보스 관리

- **보스 선택:** 보스 이미지를 클릭하여 선택 및 해제.
- **난이도 선택:** NORMAL, HARD, EXTREME 등 난이도를 선택 가능.
- **파티원 수 조정:** 보스별 파티원 수 조정 가능.
- **동적 가격 계산:** 난이도 및 파티원 수에 따라 결정석 가격 자동 계산.

### 3. 결정석 가격 계산

- **캐릭터별 총 가격:** 선택한 보스의 결정석 가격 총합 표시.
- **전체 캐릭터 총 가격:** 등록된 모든 캐릭터의 결정석 가격 총합 표시.

### 4. 사용자 경험 향상

- 반응형 레이아웃으로 다양한 화면 크기에 적응.
- 메이플스토리 감성을 반영한 모던한 UI/UX 디자인.
- 보스 선택 및 난이도 변경 시 애니메이션 효과 제공.

---

## 사용된 기술

### 프론트엔드

<<<<<<< HEAD

- **React**: 컴포넌트 기반의 사용자 인터페이스 개발.
- **CSS**: 커스텀 스타일과 CSS 변수 활용.

### API 통합

- # **넥슨 API**: 넥슨 메이플스토리 API를 활용하여 캐릭터 및 보스 데이터를 가져옴.
- **React**: 컴포넌트 기반 UI 개발.
- **CSS**: CSS 변수를 활용한 커스텀 스타일.

### API 통합

- **넥슨 API**: 넥슨의 메이플스토리 API를 활용하여 캐릭터 데이터를 가져옴.

---

## 설치 방법

### 사전 준비

<<<<<<< HEAD

1. Node.js와 npm이 설치되어 있어야 합니다.
2. 넥슨 API 키를 발급받아야 합니다.

### 설치 과정

=======

1. Node.js와 npm이 설치되어 있어야 합니다.
2. 넥슨 API 키가 필요합니다.

### 설치 과정


1. 프로젝트를 클론합니다.
   ```bash
   git clone https://github.com/your-repo/MapleStory-Weekly-Boss-Manager.git
   cd MapleStory-Weekly-Boss-Manager
   <<<<<<< HEAD
   ```
2. 의존성을 설치합니다.
   npm install
3. .env 파일 생성 및 API 키 설정

   VITE_NEXON_API_KEY=your_api_key_here

---

### 파일 구조

src/
├── components/
│ ├── CharacterManager.jsx # 캐릭터 관리 컴포넌트
│ ├── WeeklyBossManager.jsx # 주간 보스 관리 컴포넌트
│ ├── CrystalCalculator.jsx # 총 결정석 가격 계산 컴포넌트
├── data/
│ ├── bosses.js # 보스 데이터
├── styles/
│ ├── main.css # 전체 스타일링
├── App.jsx # 메인 애플리케이션
├── index.jsx # 애플리케이션 엔트리 포인트

---

## 기능 설명

### 캐릭터 검색 및 등록

검색: 검색창에 캐릭터명을 입력 후 버튼을 눌러 캐릭터를 검색.
등록: 검색된 캐릭터를 저장하여 관리 가능.
선택 및 삭제: 캐릭터별로 보스를 관리하거나 캐릭터를 삭제 가능.

### 주간 보스 관리

보스 이미지를 클릭하여 선택/해제.
난이도와 파티원 수를 조정.
현재 선택한 보스의 결정석 가격을 실시간으로 계산.

### 총 결정석 가격

각 캐릭터의 결정석 가격 총합 표시.
모든 캐릭터의 총 결정석 가격 합산 표시.

---

## 향후 개선 사항

1. 로컬 스토리지 또는 백엔드를 통한 데이터 저장.
2. 다국어 지원.
3. 선택된 캐릭터 및 보스 데이터를 CSV로 내보내는 기능 추가.
