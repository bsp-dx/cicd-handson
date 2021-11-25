### SonarQube 코드 품질 검증 실행
```bash
# SonarQube 인증 정보
export SONAR_TOKEN=SonarQube에서 생성한 토큰
export SONAR_HOST=https://sonarqube.telekinesis.shop
./mvnw clean verify sonar:sonar -Dsonar.qulitygate.wait=true
```
