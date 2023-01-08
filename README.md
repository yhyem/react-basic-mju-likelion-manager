#### 2주차 과제
Tic-Tac-Toe 프로젝트 파일 구조와 컴포넌트 분리 

## Folder structure
```
├── src
│   ├── components  
│   │   ├── Square.js
│   │   └── Table.js 
│   ├── pages  
│   │   └── Start.js 
│   └── styles
│       ├── Square.css
│       └── Table.css
├── App.js
│      
└── README.md
```

## 파일 구조 및 컴포넌트 분리 이유
파일 구조 -> components : , pages : 화면상 나타나는 페이지 (선언된 컴포넌트 사용), styles : css 스타일링 파일
Square : 하나의 사각형 컴포넌트
Table : 9개의 Square 컴포넌트를 불러 테이블 형태로 나타내는 컴포넌트
Start : 테이블 컴포넌트를 불러와 화면상에 나타내는 페이지

## 필요 함수 로직 이유


#### 커밋 컨벤션

| 머릿말   | 설명                               |
| -------- | ---------------------------------- |
| feat     | 기능 구현                          |
| setting  | 패키지 설치, 개발 설정             |
| refactor | 기능변화 없이 최적화, 코드 개선 등 |
| fix      | 버그 수정                          |
| style    | 스타일링, 변수명 수정              |
| docs     | README.md 작성,주석 추가           |

#### 브랜치 네이밍 컨벤션

주차별 단위 구현
branch는 main 에서 분기
예시) feature/week2

| 머릿말  | 설명                        |
| ------- | --------------------------- |
| main    | 최종 결과                  |
| feature | 기능 단위 구현              |
| fix     | main에서 발견된 버그 수정 |