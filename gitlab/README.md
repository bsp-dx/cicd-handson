### Git 형상 복제
```bash
# 저장할 디렉토리로 이동하여 실행
git clone https://gitlab.telekinesis.shop/root/sample-spring.git
```

### Git 형상 업데이트
```bash
# Git 로컬 형상 디렉토리로 이동하여 실행
git pull
```

### Git 수정사항 로컬 형상 반영
```bash
# 변경된 사항 Commit 내역에 포함
git add .
# add 한 대상 로컬 형상에 커밋
git commit -m "Commit Message"
```

### Git 로컬 커밋사항 원격 형상 반영
```bash
git push origin 브랜치명
```

### Git 현재 상태 조회
```bash
git status
```
