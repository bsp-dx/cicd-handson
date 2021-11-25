### Maven Deploy 실행
```bash
# Embedded Maven 사용을 위한 실행 권한 부여
chmod 700 ./mvnw
# Nexus 인증 정보 설정
export NEXUS_USERNAME=admin
export NEXUS_PASSWORD=admin123
export NEXUS_DOMAIN=nexus.telekinesis.shop
# Maven Deploy 실행
./mvnw -s .mvn/ci_settings.xml clean deploy -DskipTests -DBUILD_VERSION=1.0.0-SNAPSHOT
```
