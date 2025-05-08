# LangChain RAG 시스템 구현

## 오늘의 진행사항
- RAG(Retrieval-Augmented Generation) 시스템 구현
- Chroma 벡터 데이터베이스 설정
- 문서 처리 및 임베딩 구현
- LLM을 활용한 질의응답 시스템 구축

## 주요 학습 내용
1. RAG 시스템 구성
   - 문서 로딩 및 분할 (Docx2txtLoader, RecursiveCharacterTextSplitter)
   - 임베딩 생성 (OpenAIEmbeddings)
   - 벡터 데이터베이스 구축 (Chroma)
   - LLM을 통한 응답 생성

2. 구현된 기능
   - Word 문서(.docx) 파일 처리
   - 문서 청크 분할 (chunk_size=1500, chunk_overlap=200)
   - 유사도 기반 문서 검색
   - 컨텍스트 기반 질의응답

3. 사용된 기술
   - langchain-community
   - langchain-chroma
   - OpenAI Embeddings
   - GPT-4 모델

## 다음 단계
- RAG 시스템 성능 개선
- 다양한 문서 형식 지원
- 프롬프트 템플릿 최적화
- 사용자 인터페이스 개발 