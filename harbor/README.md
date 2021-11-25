### Docker 원격 형상 로그인
```bash
# docker login 원격주소
docker login harbor.telekinesis.shop
```

### Docker 이미지 목록 조회
```bash
docker images
```

### Docker 이미지 빌드
```bash
# docker build -t 태그명(원격 형상 주소 포함) Context
docker build -t harbor.telekinesis.shop/sample-spring/demo:1.0 .
```

### Docker 이미지 원격 형상 반영
```bash
# docker push 태그명(원격 형상 주소 포함)
docker push harbor.telekinesis.shop/sample-spring/demo:1.0 .
```

### Docker 이미지 업데이트
```bash
# docker pull 태그명(원격 형상 주소 포함)
docker pull harbor.telekinesis.shop/sample-spring/demo:1.0
```

### Docker 이미지 삭제
```bash
# docker images 목록에서 조회한 해당 이미지 ID
docker rmi 이미지ID
```
