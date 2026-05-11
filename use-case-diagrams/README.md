# Use Case Diagram

온라인 설문조사 플랫폼의 Use Case Diagram. 본 과제 명세의 functional 
requirement를 UML 2.5 표준 표기로 표현한 결과입니다.

## 작성 도구 — Papyrus Web (papyrus-web.fr)

### 선정 기준

본 과제 명세는 Use Case Diagram 작성 도구에 대해 다음 조건을 
요구합니다.

- UML 2.x 지원
- C++ code generation 제공  
- 수기 작성 금지

### 선정 도구

| 도구 | UML 2.x | C++ codegen | 라이선스 / 접근성 | 비고 |
|---|:---:|:---:|---|---|
| Papyrus Web | UML 2.5 metamodel | C_Cpp 프로파일 내장 | 오픈소스 / 웹으로 협업가능 | **선정** |


### Papyrus Web을 선택한 추가 근거

**모델 재사용 가능 export**: 작성한 모델을 JSON 형식으로 export 후 
   git에 commit하여 협업 자산으로 활용할 수 있습니다. 본 디렉터리의 
   `papyrus-export/`가 이에 해당합니다.

## 파일 구성

| 파일 | 용도 |
|---|---|
| `UCD.png` | 보고서 본문 및 README 첨부용 |
| `UCD.pdf` | use case diagram 제출본 |
| `papyrus-export/` | Papyrus Web 모델 원본. papyrus-web.fr에서 import 시 본 다이어그램을 그대로 복원 가능 |
