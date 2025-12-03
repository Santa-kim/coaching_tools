# Culture Map 슬라이드 프로젝트

문화적 차이를 이해하기 위한 Culture Map 슬라이드(Erin Meyer 8차원)입니다. 브라우저에서 바로 열어볼 수 있는 정적 HTML/CSS/JS로 구성되어 팀 교육이나 워크숍에 바로 쓸 수 있습니다.

## 주요 파일
- `cultureMap-slides.html`: 현재 사용하는 메인 슬라이드 파일 (풀스크린 데크, 키보드/도트 내비게이션 포함)
- `culture-map-slides.html`: 동일 주제의 변환본(스타일/텍스트 유사)
- `images/`: 마지막 슬라이드에서 쓰는 예시 이미지(`team-discussing.jpg`)

## 슬라이드 구성 요약
1) Introduction: Culture Map 개요와 8개 문화 차원 소개, 왜 필요한지 한 줄 요약  
2) 8 Dimensions: 각 차원의 하이/로우 스펙트럼 표 정리  
3) Why It Matters: 다문화 협업에서 마찰이 생기는 이유와 인식 전환 포인트  
4) Example Dimension: 저맥락 vs 고맥락(직접/간접 커뮤니케이션) 사례와 상호 적응 팁  
5) Team Activity: 우리 팀이 위치한 곳, 가장 큰 간극, 필요한 행동/의사결정 방식에 대한 토론 질문

## 실행 방법
- `cultureMap-slides.html` 파일을 더블클릭하거나 브라우저에서 열면 바로 슬라이드 모드로 표시됩니다.
- 내비게이션: 화면의 Next/Prev 버튼, 하단 도트, 혹은 키보드 `←` `→`.
- 반응형: 1024px 이하에서는 단일 컬럼으로 재배치되어 모바일/태블릿에서도 읽기 쉽게 표시됩니다.

## 커스터마이징 팁
- 텍스트 수정: 각 슬라이드의 `<section class="slide" data-index="...">` 블록 안 내용을 직접 편집하세요.
- 이미지 교체: `<div class="slide-img">` 안 `img` 태그의 `src`를 교체하거나 `images/` 폴더에 새 이미지를 두고 경로를 변경하세요.
- 슬라이드 추가: 기존 섹션을 복사해 붙여넣고 `data-index`를 0부터 순서대로 부여하면 하단 도트/카운터가 자동 반영됩니다.
- 폰트: Google Fonts `Noto Sans KR`를 사용합니다. 오프라인 사용 시 로컬 폰트 스택으로 자동 대체됩니다.
