## Band Website Clone Project

HTML과 CSS의 기초를 다지기 위해 제작한 밴드 소개 웹사이트 클론 프로젝트입니다.

### 1. 개요

- **목적**: 시맨틱 태그 활용 및 CSS 레이아웃(Flexbox, Positioning) 실습
- **주요 특징**: JavaScript를 사용하지 않고 정적 마크업과 스타일링만으로 구성

### 2. 사용 기술

- **Language**: HTML5, CSS3
- **Font**: Pretendard (Web Font)
- **Icons**: Font Awesome 6.7.2

### 3. 주요 구현 내용

- **Navigation**: 상단 고정 헤더 및 드롭다운 메뉴(Hover 시 표시) 구현
- **Layout**: Flexbox를 활용한 멤버 소개 및 투어 일정 카드 배치
- **Design**: CSS 변수(`:root`)를 사용한 일관된 컬러 시스템 및 다크 테마 대응 구조 설계
- **Interactive**: `transition`을 활용한 버튼 및 이미지 호버 애니메이션
- **Typography**: `@font-face`를 통한 사용자 정의 폰트 적용

### 4. 프로젝트 구조

- `index.html`: 웹페이지 전체 구조 마크업
- `css/`
    - `base.css`: CSS Reset 및 공통 스타일, 변수 설정
    - `fonts.css`: 외부 폰트 파일 로드 및 설정
    - `index.css`: 메인 페이지 세부 컴포넌트 스타일링
