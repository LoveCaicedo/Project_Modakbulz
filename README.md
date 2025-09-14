![header](https://capsule-render.vercel.app/api?type=rounded&color=F5ECD5&height=300&section=header&text=🏕️%20모닥불즈%20(Modakbulz)&fontSize=70)

# 📌 프로젝트 소개

나에게 딱 맞는 캠핑장이나 글램핑장을 쉽고 빠르게!

모닥불즈는 실제 이용자들의 생생한 후기를 통해 안심하고 캠핑장을 선택할 수 있도록 돕는 게시판 서비스입니다. 캠핑과 글램핑을 통해 자연을 즐기고, 친구 및 가족과의 소중한 순간을 만들 수 있도록 최고의 경험을 제공합니다.

# 🌟 주요 기능

1. 회원 관리
로그인/회원가입: 간편하게 가입하고 로그인하여 모든 서비스를 이용하세요.

마이페이지: 내 정보를 수정하고, 내가 쓴 글이나 찜한 캠핑장을 확인할 수 있습니다.

2. 정보 조회
캠핑장 & 글램핑장 정보: 전국의 다양한 캠핑장과 글램핑장 정보를 한눈에 찾아보세요.

실시간 날씨 및 길찾기: 여행 계획에 필수적인 실시간 날씨와 길찾기 정보를 제공합니다.

주변 편의시설: 캠핑장 주변의 편의시설 정보를 확인하여 더욱 편리한 여행을 계획하세요.

3. 게시글 관리
리뷰 게시판: 실제 방문객들의 생생한 후기를 공유하고, 방문 전 꿀팁을 얻어보세요.

커뮤니티 게시판: 자유롭게 소통하며 캠핑에 대한 이야기를 나눌 수 있는 공간입니다.

문의하기: 서비스 이용 중 궁금한 점이나 불편한 점을 언제든지 문의할 수 있습니다.

# 💻 사용된 기술 스택

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-%23005C0F.svg?style=for-the-badge&logo=Thymeleaf&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/elasticsearch-%230377CC.svg?style=for-the-badge&logo=elasticsearch&logoColor=white)
![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## 📂 프로젝트 구조
```
├── main
│   ├── java
│   │   └── modackbulz
│   │       └── app
│   │           └── Application
│   │               ├── common          // 공통 기능 (설정, 파일 저장 등)
│   │               ├── config          // Spring Security, 인증 등 설정
│   │               ├── domain          // 각 도메인별 비즈니스 로직
│   │               │   ├── autocomplete  // 자동완성
│   │               │   ├── camping       // 캠핑장 정보
│   │               │   ├── community     // 커뮤니티 게시판
│   │               │   ├── faq           // 문의하기
│   │               │   ├── keyword       // 키워드
│   │               │   ├── member        // 회원
│   │               │   ├── popular       // 인기 검색어
│   │               │   ├── review        // 리뷰
│   │               │   └── scrap         // 찜하기
│   │               ├── entity          // 데이터베이스 테이블과 매핑되는 객체
│   │               ├── global          // 전역적으로 사용되는 기능 (스케줄러, 서비스 등)
│   │               └── web             // 웹 요청을 처리하는 컨트롤러
│   │                   └── form          // 폼 데이터 처리
│   └── resources
│       ├── elasticsearch   // Elasticsearch 인덱스 설정
│       ├── static          // 정적 파일 (CSS, JS, 이미지 등)
│       └── templates       // HTML 템플릿 파일
└── test                    // 테스트 코드
```
