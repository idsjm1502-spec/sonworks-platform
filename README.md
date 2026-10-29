# 🏛️ SonWorks 35인 자율 이사회 | D:\MCP_workspace

본 디렉토리(`D:\MCP_workspace`)는 GitHub 개인 토큰(`ghp_w5HRAV9TP...`)을 통해 원격 관리되는 글로벌 웹 워크스페이스입니다.

## 🚀 탑재된 핵심 엔진
1. **GitHub Bridge (`github_bridge.py`)**:
   - 로컬 웹사이트 파일들을 GitHub(`idsjm1502-spec/sonworks-platform`)에 원클릭 동기화/커밋하는 REST API 자동화 브릿지.
2. **글로벌 웹 포털 (`index.html`)**:
   - 3-in-1 하이브리드 전문 검색창 (🌐 기본 속보 / 🔬 전문 리포트 / 🔮 하이브리드)
   - YouTubeAdapter: 10분 롱폼(중간광고 2개 최적화) + 1분 쇼츠 미끼 대본
   - EbookAdapter: PDF 및 EPUB 3.0 출판 자동화
3. **연동된 AI 백엔드**:
   - Groq Cloud API: `Llama 3.3 70B`
   - 로컬 Ollama: `gemma4:e4b`, `gemma4:e2b`, `qwen3.5:4b`
   - 구글 Gemini 2.0 Flash 통제관

## 💡 관리 명령어
```bash
# GitHub 동기화 테스트 및 원격 저장소 자동 생성
python github_bridge.py
```
