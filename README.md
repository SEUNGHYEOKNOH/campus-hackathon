# campus-hackathon

설치 시 해야할 것

파일 - 설정 - 빌드,실행,배포 - 빌드 도구 - gradle - gradle JVM : jdk17(JAVA 17버전으로 맞추기)
build.gradle 확인하고 설치

front,backend branch에 맞게 pull 하고 검토 후 main애 pull requests 하기

resources/application의 datasource 에 있는 DB 주소(스키마), username, password 자신들의 환경과 동일하게 변경.
해당 DB에 맞춰서 test용 테이블 / 로그인, 로그아웃을 위한 유저 테이블 / 리프레시 토큰 저장을 위한 테이블 변경.
mvc 로직 확인 가능하도록 기능별로 폴더를 나눠서 controller, dao, service, vo 모두 따로따로 작성
mybatis 사용은 resources/mybatis/mapper에 xml을 작성하여 DAO와 연결.
주석/기능 작성 잊지 말고 넣어서 헷갈리지 않게 만들기.
