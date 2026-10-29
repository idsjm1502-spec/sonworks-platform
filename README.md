# 🏛️ SonWorks 35인 자율 이사회 & 글로벌 1인 창업 AI 플랫폼
> **Workspace Location**: `D:\MCP_workspace`  
> **GitHub Repository**: [https://github.com/idsjm1502-spec/sonworks-platform](https://github.com/idsjm1502-spec/sonworks-platform)  
> **Auth Account**: `idsjm1502-spec` (토큰: `ghp_w5HRAV9TP...`)

---

## 🚀 시스템 개요 (System Overview)
본 워크스페이스는 1인 글로벌 AI 창업을 위한 자율 완결형 엔터프라이즈 플랫폼으로, **35인 자율 이사회(MoE)** 와 **18개 모듈형 파이프라인**, 그리고 **멀티 레베뉴 출력 어댑터(Output Adapters)** 를 통해 하나의 트렌드 주제를 **유튜브 롱폼·쇼츠, 출판급 전자책(PDF/EPUB), 인스타·틱톡 바이럴 마케팅 패키지**로 동시 변환·수익화합니다.

---

## 🛠️ 3대 핵심 멀티 레베뉴 출력 어댑터 (Output Adapters)

### 1. 🎬 YouTubeAdapter (광고 수익 극대화 8~12분 최적화)
- **10분 정규 롱폼 (`youtube_10min_script.json`)**:
  - 유튜브 중간 광고(미드롤) 2개 최적 배치 (04:00 1차 브릿지 / 08:10 2차 브릿지).
  - 총 분량 약 2,600~3,500자 방송국급 구어체 나레이션.
- **1분 쇼츠 미끼 대본 (`youtube_1min_shorts.json`)**:
  - 0~5초 스크롤 정지 훅 + 50초 초압축 팩트 + 10분 본편 고정댓글 클릭 유도 CTA (350자 내외).

### 2. 📖 EbookAdapter (출판급 전자책 자동화)
- **A4 출판용 PDF (`SonWorks_Ebook_*.pdf`)**:
  - 표지, 목차, 5개 챕터 심층 분석, 법적 면책 고지 완비.
  - Windows 맑은 고딕(Malgun Gothic) 벡터 폰트 임베딩으로 한글 깨짐 0%.
- **EPUB 3.0 국제 표준 전자책 (`SonWorks_Ebook_*.epub`)**:
  - 리디북스, 교보문고, 크몽, Gumroad 등 전 세계 글로벌 달러 판매 규격 W3C 표준 컨테이너 패키징.

### 3. 📱 SNSViralAdapter (SNS 바이럴 홍보부)
- **인스타그램 릴스**: 첫 3초 시선강탈 카피 + 30~60초 대본 + 추천 BGM 오디오 분위기 + 프로필 링크 CTA.
- **5단 카드뉴스**: 표지 헤드라인, 함정 지적, 공시 지표 요약, 1인 기업 솔루션, 리포트 유입 안내.
- **틱톡 숏폼**: 15초 초고속 호흡 스크립트 + 화면 자막 텍스트.
- **해시태그 풀**: 도달률 극대화 6대 키워드 태그 풀 자동 매칭.

---

## 🧠 5-AI 하이브리드 MoE 추론 인프라 (32GB RAM 순차 파이프라인)
- **Cloud 1순위 (초고속)**: Groq Cloud API (`openai/gpt-oss-120b`, 초당 200+ 토큰)
- **Cloud 감사관**: Google Gemini 2.0 Flash (심층 팩트체크 및 RAG 오케스트레이션)
- **Local Gemma 3총사 (메모리 상주, 단일 순차 실행으로 OOM 방지)**:
  1. `gemma4:e4b` (6.6 GB) : 메인 기획, JEV 검증, 심층 집필
  2. `gemma4:e2b` (4.6 GB) : 실시간 요약, 숏폼 카피라이팅
  3. `qwen3.5:4b` (3.3 GB) : 한국어 자연스러운 구어체 윤문 및 정서 검수

---

## 🛡️ 4단계 엔터프라이즈 법무 필터링 및 5종 안전 출처
- **1단계**: 날짜/요일/시간 원천 삭제
- **2단계**: 기성 언론사명 및 병원·기관명 정제
- **3단계**: 실명/공직자 이니셜 마스킹 (`인물 P씨`) 및 대기업 가명화 (`S사`, `H사`)
- **4단계**: 자극적 클릭베이트('충격', '경악') 감지 시 자동 드랍(Drop)
- **5종 안전 출처 라벨링**: 5개 신뢰 표기를 턴마다 난수 순환 배정하여 단조로움 탈피.

---

## 📂 파일 구조 (File Structure)
```text
D:\MCP_workspace\
├── index.html                    # 3-in-1 하이브리드 포털 대시보드
├── tech_spec.html                # 시스템 기술서 인터랙티브 웹 뷰어
├── SYSTEM_TECHNICAL_SPEC.md      # 18개 모듈 전체 아키텍처 기술서
├── github_bridge.py              # GitHub 자동 커밋/푸시 REST API 브릿지
├── README.md                     # 본 프로젝트 문서
└── output_assets\                # 멀티 레베뉴 결과물 저장소
    ├── SonWorks_Ebook_*.pdf      # 출판급 전자책 PDF
    ├── SonWorks_Ebook_*.epub     # EPUB 3.0 국제 표준 전자책
    ├── youtube_10min_script.json # 8~12분 최적화 10분 롱폼 대본
    ├── youtube_1min_shorts.json  # 1분 쇼츠 미끼 대본
    ├── sns_viral_marketing_package.json # SNS 바이럴 종합 패키지
    └── debate_video_latest.mp4   # FFmpeg 렌더링 방송국급 비디오
```

---

## ⚡ GitHub 동기화 실행
```bash
python github_bridge.py
```
> GitHub 원격 저장소(`idsjm1502-spec/sonworks-platform`)와 100% 무인 자동 동기화됩니다.
