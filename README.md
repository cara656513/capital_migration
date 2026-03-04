# Overview (개요)
- 프로젝트 이름: MG캐피탈 웹퍼블리싱 소스 공통
- 프로젝트 설명: MG캐피탈 홈페이지 리뉴얼 프로젝트 종료 후, 웹퍼블리싱 소스를 정리하여 포맷화하였습니다.

<br/>
<br/>

# Key Features (주요 기능)
- **alert**:
  - 설명, 이미지

- **button**:
  - 설명, 이미지

- **edt**:
  - 설명, 이미지

- **input**:
  - 설명, 이미지

- **layout**:
  - 설명, 이미지

- **list**:
  - 설명, 이미지

- **popup**:
  - 설명, 이미지

<br/>
<br/>

# Improvements (개선점)
- **재사용 예시**:
  - 다른 css 파일 적용했을 때

- **버전별 적용**:
  - 설명, 이미지

<br/>
<br/>

# 5. Technology Stack (기술 스택)
## 5.1 Language
|  |  |
|-----------------|-----------------|
| HTML5    |<img src="https://github.com/user-attachments/assets/2e122e74-a28b-4ce7-aff6-382959216d31" alt="HTML5" width="100">| 
| CSS3    |   <img src="https://github.com/user-attachments/assets/c531b03d-55a3-40bf-9195-9ff8c4688f13" alt="CSS3" width="100">|
| Javascript    |  <img src="https://github.com/user-attachments/assets/4a7d7074-8c71-48b4-8652-7431477669d1" alt="Javascript" width="100"> | 

<br/>

## 5.2 Frotend
|  |  |  |
|-----------------|-----------------|-----------------|
| Swiper    |  <img src="https://github.com/user-attachments/assets/" alt="Swiper" width="100"> |
| jquery    |  <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white" alt="jquery" width="100"> |

<br/>
<br/>

# Project Structure (프로젝트 구조)
```plaintext
PUB-GUIDE/
├── index.html                           # 메인 HTML 파일
├── README.md                            # 프로젝트 개요 및 사용법
├── assets/                              # 정적 파일 및 라이브러리
│   ├── css/                             # 스타일시트
│   │   ├── swiper-bundle.min.css        # Swiper 라이브러리 CSS
│   │   └── com/                         # 공통 컴포넌트 CSS
│   │       ├── button.css               # 버튼 스타일
│   │       ├── common.css               # 공통 스타일
│   │       ├── default.css              # 기본 스타일
│   │       ├── fonts.css                # 폰트 스타일
│   │       ├── ie.css                   # IE 호환성 스타일
│   │       ├── input.css                # 입력 필드 스타일
│   │       ├── layout.css               # 레이아웃 스타일
│   │       ├── nav.css                  # 네비게이션 스타일
│   │       ├── style.css                # 메인 스타일
│   │       ├── tab.css                  # 탭 스타일
│   │       ├── table.css                # 테이블 스타일
│   │       └── ui-util.css              # UI 유틸 스타일
│   ├── fonts/                           # 폰트 파일
│   ├── images/                          # 이미지 파일
│   │   └── com/                         # 공통 이미지
│   │       ├── ie11/                    # IE11 호환 이미지
│   │       └── svg/                     # SVG 파일
│   └── js/                              # 자바스크립트 파일
│       ├── include.js                   # 포함 파일
│       ├── lib/                         # 외부 라이브러리
│       │   ├── jquery-1.12.4.js         # jQuery 라이브러리
│       │   ├── jquery-ui.min.js         # jQuery UI 라이브러리
│       │   ├── swiper-bundle.min.js     # Swiper 라이브러리
│       │   └── ui_plugin.js             # UI 플러그인
│       └── ui/                          # UI 스크립트
│           ├── ui-util.js               # UI 유틸리티
│           └── com/                     # 공통 UI 스크립트
│               ├── accordion.js         # 아코디언
│               ├── datepicker.js        # 날짜 선택기
│               ├── fake_select.js       # 커스텀 셀렉트
│               ├── finance.js           # 재무 관련 스크립트
│               ├── finance_test.js      # 재무 테스트 스크립트
│               ├── input.js             # 입력 필드 스크립트
│               ├── layout.js            # 레이아웃 스크립트
│               ├── nav.js               # 네비게이션 스크립트
│               ├── popup.js             # 팝업 스크립트
│               ├── popup_1.js           # 팝업 변형
│               ├── popup_new.js         # 새로운 팝업
│               ├── tab.js               # 탭 스크립트
│               ├── table.js             # 테이블 스크립트
│               └── terms.js             # 약관 스크립트
├── guide/                               # 가이드 및 샘플
│   ├── css/                             # 가이드 스타일
│   │   ├── pub-worklist.css             # 작업 리스트 스타일
│   │   └── sample.css                   # 샘플 스타일
│   ├── js/                              # 가이드 자바스크립트
│   │   ├── jquery-1.11.3.min.js         # jQuery 라이브러리
│   │   └── jquery.form.min.js           # jQuery Form 라이브러리
│   └── sample/                          # HTML 샘플 파일
│       ├── alert.html                   # 알림 샘플
│       ├── button.html                  # 버튼 샘플
│       ├── edt.html                     # 에디터 샘플
│       ├── input.html                   # 입력 필드 샘플
│       ├── layout.html                  # 레이아웃 샘플
│       ├── list.html                    # 리스트 샘플
│       ├── popup.html                   # 팝업 샘플
│       ├── process.html                 # 프로세스 샘플
│       ├── request.html                 # 요청 샘플
│       ├── tab.html                     # 탭 샘플
│       ├── table.html                   # 테이블 샘플
│       ├── terms.html                   # 약관 샘플
│       ├── toggle.html                  # 토글 샘플
│       └── write.html                   # 작성 샘플
└── views/                               # 페이지 뷰
    ├── COM/                             # 공통 페이지
    │   ├── COM-BSC-C002.html            # 페이지 템플릿
    │   ├── COM-BSC-C015.html            # 페이지 템플릿
    │   ├── COM-BSC-C01502.html          # 페이지 템플릿
    │   ├── COM-BSC-C021.html            # 페이지 템플릿
    │   ├── COM-BSC-C022.html            # 페이지 템플릿
    │   ├── COM-BSC-C031.html            # 페이지 템플릿
    │   ├── installAnySign.html          # AnySign 설치 페이지
    │   └── MGC-MENU-001P.html           # 메뉴 페이지
    └── COMMON/                          # 공통 컴포넌트
        ├── footer.html                  # 푸터
        └── header.html                  # 헤더
```

<br/>
<br/>

# Coding Convention
## 명명 규칙
* 상수 : 영문 대문자 + 스네이크 케이스
```
const NAME_ROLE;
```
* 변수 & 함수 : 카멜케이스
```
// state
const [isLoading, setIsLoading] = useState(false);
const [isLoggedIn, setIsLoggedIn] = useState(false);
const [errorMessage, setErrorMessage] = useState('');
const [currentUser, setCurrentUser] = useState(null);

// 배열 - 복수형 이름 사용
const datas = [];

// 정규표현식: 'r'로 시작
const = rName = /.*/;

// 이벤트 핸들러: 'on'으로 시작
const onClick = () => {};
const onChange = () => {};

// 반환 값이 불린인 경우: 'is'로 시작
const isLoading = false;

// Fetch함수: method(get, post, put, del)로 시작
const getEnginList = () => {...}
```

<br/>

## 블록 구문
```
// 한 줄짜리 블록일 경우라도 {}를 생략하지 않고, 명확히 줄 바꿈 하여 사용한다
// good
if(true){
  return 'hello'
}

// bad
if(true) return 'hello'
```

<br/>

## 함수
```
함수는 함수 표현식을 사용하며, 화살표 함수를 사용한다.
// Good
const fnName = () => {};

// Bad
function fnName() {};
```

<br/>

## 태그 네이밍
Styled-component태그 생성 시 아래 네이밍 규칙을 준수하여 의미 전달을 명확하게 한다.<br/>
태그명이 길어지더라도 의미 전달의 명확성에 목적을 두어 작성한다.<br/>
전체 영역: Container<br/>
영역의 묶음: {Name}Area<br/>
의미없는 태그: <><br/>
```
<Container>
  <ContentsArea>
    <Contents>...</Contents>
    <Contents>...</Contents>
  </ContentsArea>
</Container>
```

<br/>

## 폴더 네이밍
카멜 케이스를 기본으로 하며, 컴포넌트 폴더일 경우에만 파스칼 케이스로 사용한다.
```
// 카멜 케이스
camelCase
// 파스칼 케이스
PascalCase
```

<br/>

## 파일 네이밍
```
컴포넌트일 경우만 .jsx 확장자를 사용한다. (그 외에는 .js)
customHook을 사용하는 경우 : use + 함수명
```

<br/>
<br/>
