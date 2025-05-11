# LangChain LLM 학습 프로젝트

이 저장소는 LangChain과 대형 언어 모델(LLM) 학습을 위한 자료와 코드 예제를 포함하고 있습니다.

## 프로젝트 구조
```
.
├── 1.langchain_llm_test.ipynb    # 테스트용 Jupyter 노트북
├── 2.rag_with_chroma.ipynb       # RAG 시스템 구현 노트북 (Chroma)
├── 3.rag_with_pinecone.ipynb     # RAG 시스템 구현 노트북 (Pinecone)
├── Scripts/                      # Python 스크립트
├── share/                        # 공유 리소스
├── 2024-04-29_study_summary.md   # 학습 진행 상황 및 노트
└── 2024-05-09_study_summary.md   # RAG 시스템 구현 요약
```

## 개발 환경
- Python 3.10.13
- pyenv (Python 버전 관리)
- Windows 10

## 설치 방법
1. Python 3.10.13 설치:
```bash
pyenv install 3.10.13
pyenv local 3.10.13
```

2. 가상환경 생성 및 활성화:
```bash
# 가상환경 생성
python -m venv inflearn-llm

# Windows PowerShell에서 가상환경 활성화
.\inflearn-llm\Scripts\Activate.ps1
```

3. 필요한 패키지 설치:
```bash
pip install -r requirements.txt
```

4. API 키를 포함한 .env 파일 생성:
```
OPENAI_API_KEY=your_api_key_here
PINECONE_API_KEY=your_pinecone_api_key_here
PINECONE_ENVIRONMENT=your_pinecone_environment
```

## 사용 방법
1. Jupyter 노트북 실행:
```bash
jupyter notebook
```

2. RAG 시스템 테스트:
   - `2.rag_with_chroma.ipynb`: Chroma DB를 사용한 RAG 시스템
   - `3.rag_with_pinecone.ipynb`: Pinecone을 사용한 RAG 시스템 (개발 중)

## 구현된 기능
- Word 문서(.docx) 파일 처리
- 문서 청크 분할 (chunk_size=1500, chunk_overlap=200)
- 유사도 기반 문서 검색
- 컨텍스트 기반 질의응답
- Chroma 벡터 데이터베이스 통합
- Pinecone 벡터 데이터베이스 통합 (진행 중)

## 학습 자료
- `2024-04-29_study_summary.md`에서 일일 진행 상황과 주요 학습 내용 확인
- `2024-05-09_study_summary.md`에서 RAG 시스템 구현 내용 확인
- Jupyter 노트북에서 실용적인 예제와 코드 스니펫 확인

## 다음 단계
- Pinecone 벡터 데이터베이스로 마이그레이션
- RAG 시스템 성능 개선
- 다양한 문서 형식 지원
- 프롬프트 템플릿 최적화
- 사용자 인터페이스 개발

## 기여하기
다음과 같은 방법으로 기여할 수 있습니다:
- 새로운 예제 추가
- 문서 개선
- 학습 자료 공유
- 이슈 보고

## 라이선스
이 프로젝트는 교육 목적으로만 사용됩니다. 