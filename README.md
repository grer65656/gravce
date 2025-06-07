Levenshtein Distance 기반 챗봇

과제 목적
기존 TF-IDF + cosine_similarity 기반 챗봇 코드를
Levenshtein 거리 기반으로 수정하여 유사도 비교 방식으로 구현

실행 방법 (Google Colab 기준)
1. `AI개발실무_한지수.ipynb` 파일을 Colab에서 열기
2. `ChatbotData.csv` 파일을 업로드
3. 사용자 질문 입력 → 가장 유사한 질문의 답변 출력
4. '종료' 입력 시 챗봇 종료

사용된 주요 기술
- `python-Levenshtein` : 문자열 간 거리 계산
- `pandas` : CSV 데이터 처리
