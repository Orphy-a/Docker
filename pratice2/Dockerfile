# openjdk 17 기본 환경
FROM openjdk:17

# JAR_FILE 변수 정의
ARG JAR_FILE=./*.jar

# JAR 파일 메인 디렉토리에 복사
COPY ${JAR_FILE} app.jar

# 시스템 진입점 정의
ENTRYPOINT ["java", "-jar", "app.jar"]