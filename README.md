# 해보는 언니 — 슬라이드 가이드 대시보드

> 몰랐지만 해봤고, 해봤으니까 쉬운 말로 전해드릴 수 있어요.

## 바로가기
- 🖥️ [대시보드 열기](https://hiation33-arch.github.io/slide-guide-dashboard/)
- 📖 [사용 가이드 보기](https://hiation33-arch.github.io/slide-guide-dashboard/guide.html)

## 소개
용도 → 세트 → 팔레트를 선택하면 Claude용 슬라이드 제작 프롬프트가 자동으로 완성되는 대시보드예요.

## 주요 기능
- **용도 선택** — 강의자료 / 공모전 / 제안서·사업계획서
- **세트 선택** — 미니멀 라인 / 카드+아이콘 / 매거진 / 다이나믹 / 기하학 (SVG 미리보기 제공)
- **팔레트 선택** — 머스터드 / 소프트 틸 / 포레스트 그린 / 더스티 블루 / 차콜
- **프롬프트 복사** — 셋 다 선택하면 Claude용 가이드가 한 번에 복사
- **레퍼런스 보관함** — PPT 이미지 Ctrl+V 붙여넣기 → Claude API로 스타일 프롬프트 자동 생성
- **자동 저장** — 선택 내역 및 레퍼런스 이미지 localStorage 저장

## 사용 방법
1. 대시보드에서 **용도 → 세트 → 팔레트** 순서로 선택
2. **용도 + 세트 + 팔레트 복사** 버튼 클릭
3. Claude 채팅창에 붙여넣기 + NotebookLM에서 정리한 강의 내용 추가
4. Claude가 HTML 슬라이드 생성

> 자세한 사용법은 [사용 가이드](https://hiation33-arch.github.io/slide-guide-dashboard/guide.html)를 참고하세요.

## 기술 스택
- HTML / CSS / JavaScript (프레임워크 없음)
- Claude API (레퍼런스 이미지 분석)
- localStorage (선택 내역 저장)

## 배포
GitHub Pages 사용 — Settings → Pages → Source: main 브랜치 루트(`/`) 설정
