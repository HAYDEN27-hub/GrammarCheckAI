# **📝 Mobile English Grammar Checker (Grammar Assistant)**

AI 기반으로 입력된 영어 문장의 문법 오류, 어색한 표현을 교정하고 더 나은 모범 답안 및 다양한 표현 변형을 제시해 주는 **모바일 최적화 영어 문법 교정 웹 애플리케이션**입니다.

## **📸 주요 기능 (Key Features)**

1. **📱 모바일 최적화 UI/UX**  
   * 모바일 화면 크기에 최적화된 컴팩트하고 깔끔한 화이트 & 에메랄드 톤 디자인  
   * 직관적인 입력창 및 결과 피드백 레이아웃  
2. **⚠️ 스마트 입력 검증 (Gibberish Detection & Error Alert)**  
   * 무작위 키보드 입력(asdfadsf, qwerty 등)이나 의미 없는 단어/특수문자 입력 감지  
   * 입력 오류 발생 시 결과 창 대신 **빨간색 삼각형 느낌표 경고 배너** 출력  
3. **🤖 Gemini API 기반 문법 분석**  
   * **문법 오류 및 어색한 점**: 문맥과 구문에 대한 상세 한글 설명  
   * **더 나은 표현**: 자연스러운 원어민 스타일의 대표 문장 추천  
   * **다양한 표현 변형**: 동일한 의미를 전달하는 다양한 형태의 문장 예시 제시  
4. **🔑 사용자 API Key 설정 모달**  
   * 헤더 우측의 API Key 버튼을 통해 개별 Google Gemini API 키 입력 지원  
   * 로컬 스토리지(localStorage)에 저장되어 재방문 시에도 설정 유지  
5. **🔄 빠른 재시도 (AGAIN 버튼)**  
   * 하단의 빨간색 **AGAIN** 버튼 클릭 시 입력 창 초기화 및 즉시 재검사 준비

## **🛠 기술 스택 (Tech Stack)**

| 구분 | 기술 / 라이브러리 |
| :---- | :---- |
| **Frontend** | HTML5, Vanilla JavaScript (ES6+) |
| **Styling** | Tailwind CSS (CDN) |
| **AI Model** | Google Gemini API (gemini-3-flash-preview) |
| **Font** | Inter (Google Fonts) |

## **🚀 사용 방법 (Usage Guide)**

1. **파일 실행**: grammar\_checker.html 파일을 웹 브라우저(또는 모바일 브라우저)에서 엽니다.  
2. **API Key 설정 (선택 사항)**:  
   * 상단 우측 API Key 버튼을 누르고 개인 Gemini API Key를 입력 후 저장합니다.  
   * 키를 설정하지 않더라도 기본 설정으로 작동할 수 있습니다.  
3. **문장 입력**:  
   * 중앙 입력창에 교정하고 싶은 영어 문장을 입력합니다.  
   * 초록색 **ENTER** 버튼을 누릅니다.  
4. **결과 확인**:  
   * 분석 결과 화면에서 문법 설명, 개선안, 대안 표현을 확인합니다.  
5. **다시 입력**:  
   * 하단의 빨간색 **AGAIN** 버튼을 누르면 초기 입력 화면으로 돌아갑니다.

