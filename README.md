# TIL
Today I Learned 작성

2022.03.18(금)
- Spring 부트 기본 개념 학습
 + Controller를 통한 View 호출 with Model attribute
- Intellij 'spring-boot-devtools' 라이브러리 추가
-> 1. 의존성(Dependency) 추가
[gradle project]
dependencies {
	developmentOnly 'org.springframework.boot:spring-boot-devtools'
}

2. IntelliJ(인텔리제이) Spring Boot DevTools 사용을 위한 설정

 - Compiler 세팅
1. 상단 File > Settings 메뉴 혹은 단축키 Ctrl + Alt + S를 눌러서 세팅 메뉴로 이동합니다.
2. Build, Exeution, Deployment > Compiler > Build project autiomaically 체크

 - Advanced 세팅
1. Advanced Settings > Allow auto-make to start even if developed application is currently running 체크
