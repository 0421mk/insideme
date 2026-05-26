# Changelog — InsideMe

버전 규칙: `MAJOR.MINOR.PATCH`
- MAJOR: 사이트 구조 전면 개편
- MINOR: 새 테스트 추가, 페이즈 추가
- PATCH: 버그 수정, 텍스트·디자인 수정

---

## [v1.2.0] — 2026-05-25
### Added
- 연애 성향 테스트 (`love.html`) — 20문항, 4가지 유형 (불꽃 낭만형·전략적 헌터형·수줍은 달빛형·쿨한 관망형)
- `robots.txt` — 검색엔진 크롤링 허용
- `sitemap.xml` — 전체 페이지 색인 등록

### Changed (SEO 전면 적용)
- 모든 페이지 Primary 메타태그 추가 (title, description, keywords, canonical)
- 모든 페이지 Open Graph 태그 추가 (카카오톡/SNS 공유 미리보기)
- 모든 페이지 Twitter Card 태그 추가
- 모든 페이지 JSON-LD 구조화 데이터 추가 (WebSite / Quiz 스키마)
- `social.html` noscript 폴백 콘텐츠 추가 (검색봇 대응)
- `index.html` 연애 성향 테스트 카드 활성화

---

## [v1.0.0] — 2026-05-25
### Added
- InsideMe 홈페이지 (`index.html`) — 테스트 목록 카드 UI
- 사회 성향 테스트 (`social.html`) — 20문항, 4가지 유형 결과
- 30초 광고 시청 후 결과 확인 플로우 (AD 페이즈)
- 구글 애드센스 자리 표시자 (로딩 화면 + 결과 화면)
- 결과 화면 → 홈으로 돌아가기 버튼
