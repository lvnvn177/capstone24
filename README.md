# 소개 

클라이언트 및 모델 서버로 분리 후 진행한 캡스톤 프로젝트 입니다.


사용자는 논문 PDF 문서를 업로드 후 해당 문서에 관한 번역 및 요약 기능을 LLM 모델에게 요구할 수 있습니다.


사용한 LLM 모델 - https://huggingface.co/MLP-KTLim/llama-3-Korean-Bllossom-8B


# Installation

### 환경 준비 
    npm install
    venv 가상환경 접속 
    pip install -r requirements.txt


### 서버 실행
    npm run dev (Client) 
    uvicorn main:converter --reload --host 0.0.0.0 --port 2000 (API, ModelServer)
