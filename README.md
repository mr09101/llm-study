# LangChain LLM 학습 프로젝트

이 저장소는 LangChain과 대형 언어 모델(LLM) 학습을 위한 자료와 코드 예제를 포함하고 있습니다.

## 프로젝트 구조
```
.
├── 1.langchain_llm_test.ipynb    # 테스트용 Jupyter 노트북
├── Scripts/                      # Python 스크립트
├── share/                        # 공유 리소스
└── 2024-04-29_study_summary.md   # 학습 진행 상황 및 노트
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
```

## 사용 방법
1. Jupyter 노트북 실행:
```bash
jupyter notebook
```

2. `1.langchain_llm_test.ipynb` 파일을 열어 테스트 시작

## 학습 자료
- `2024-04-29_study_summary.md`에서 일일 진행 상황과 주요 학습 내용 확인
- Jupyter 노트북에서 실용적인 예제와 코드 스니펫 확인

## 기여하기
다음과 같은 방법으로 기여할 수 있습니다:
- 새로운 예제 추가
- 문서 개선
- 학습 자료 공유
- 이슈 보고

## 라이선스
이 프로젝트는 교육 목적으로만 사용됩니다. 