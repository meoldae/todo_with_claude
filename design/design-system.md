# 디자인 시스템

파랑-하늘색 계열 기반의 Windows 데스크톱 앱 디자인 가이드.  
**60 : 30 : 10 색상 비율** 원칙을 따른다.

## 60 : 30 : 10 색상 원칙

| 역할 | 비율 | 색상 | HEX | 사용처 |
|------|------|------|-----|--------|
| **Base** | 60% | 흰색·연백 | `#FFFFFF` / `#F5F8FF` | 페이지 배경, 카드, 입력창 |
| **Main** | 30% | 네이비 | `#1B3A6B` | 사이드바, 구조적 패널, 짙은 배너 |
| **Accent** | 10% | 스카이 블루 | `#0EA5E9` | 버튼, 활성 상태, 프로그레스 바, 뱃지 강조 |

## 전체 색상 토큰

| 토큰 | HEX | 용도 |
|------|-----|------|
| `--base-white` | `#FFFFFF` | 카드, 입력, 모달 배경 |
| `--base-page` | `#F5F8FF` | 콘텐츠 영역 페이지 배경 |
| `--main-navy` | `#1B3A6B` | 사이드바, 짙은 배너 |
| `--main-navy-hover` | `#254E8F` | 사이드바 호버 |
| `--accent` | `#0EA5E9` | 주요 액션 버튼, 활성 상태, 프로그레스 |
| `--accent-hover` | `#0284C7` | 버튼 호버 |
| `--accent-light` | `#E0F2FE` | 활성 칩 배경, 뱃지 배경 |
| `--accent-text` | `#0369A1` | 강조 텍스트 |
| `--border` | `#E2E8F0` | 기본 구분선, 카드 테두리 |
| `--border-accent` | `#BAE6FD` | 강조 구분선 |
| `--text` | `#1E293B` | 본문 텍스트 |
| `--text-muted` | `#64748B` | 보조 텍스트 |
| `--text-light` | `#94A3B8` | 비활성, 완료 텍스트 |
| `--success` | `#10B981` | 수입, 완료, 양호 |
| `--warning` | `#F59E0B` | 예산 임박 경고 |
| `--danger` | `#EF4444` | 예산 초과, 마감 임박 |

## 타이포그래피

- **폰트**: `Pretendard`, `Segoe UI`, `system-ui` 순으로 fallback
- **제목 (H1)**: 20px, weight 700, `--text`
- **소제목 (H2)**: 15px, weight 600, `--text`
- **본문**: 14px, weight 400, `--text`
- **캡션**: 12px, weight 400, `--text-muted`

## 레이아웃

- **앱 크기**: 1280 × 800px (기본)
- **사이드바 너비**: 220px (30% 영역의 핵심)
- **콘텐츠 영역**: 나머지 공간, 배경 `--base-page`
- **카드**: `border-radius: 10px`, `background: --base-white`, `border: 1px solid --border`

## 화면 목록

| 파일 | 화면 |
|------|------|
| `01-today.html` | 투두 — 오늘 뷰 |
| `02-todo-list.html` | 투두 — 전체 목록 |
| `03-ledger.html` | 가계부 — 거래 내역 |
| `04-budget.html` | 가계부 — 예산 현황 |
| `05-tax.html` | 가계부 — 연말정산 |
