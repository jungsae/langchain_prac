# LangChain 학습

LangChain 프레임워크 학습 과정을 기록한 저장소입니다.

## 📁 구조
```
langchain/
├── langchain-basic/          # 기본 개념
│   ├── 1.chat.ipynb         # LLM 대화
│   ├── 2.prompt.ipynb       # 프롬프트 템플릿
│   ├── 3.output parser.ipynb # 출력 파서
│   ├── 4.runnable.ipynb     # Runnable 체인
│   └── 5.review.ipynb       # 종합 복습
├── langchain-rag/           # RAG 학습
│   ├── 1. embedding_test.ipynb # 임베딩 테스트
│   ├── 2. rag_with_chroma.ipynb # Chroma RAG
│   ├── 3. rag_with_upstage.ipynb # Upstage RAG
│   ├── 3.1 rag_without_langchain_with_chroma.ipynb # LangChain 없이 RAG
│   ├── 4. rag_with_pinecone.ipynb # Pinecone RAG
│   ├── 4.1 rag_with_pinecone_with_upstage.ipynb # Pinecone + Upstage
│   └── tax.docx # 테스트용 문서
└── README.md
```

## 📚 학습 내용
- **Basic**: LLM 통합, 프롬프트 관리, 출력 파싱, 체인 구성
- **RAG**: 임베딩, 벡터 검색, 다양한 DB(Chroma, Pinecone) 활용

## 🛠️ 사용 기술
- **LLM**: Ollama, Upstage Solar
- **벡터 DB**: Chroma, Pinecone
- **프레임워크**: LangChain

---
