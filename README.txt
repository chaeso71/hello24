
[GITHUB YSIT24]

# 로컬 저장소 생성
git init

# 파일 생성(REAME.TXT)
git add readme.txt

# 커밋
git commit -m '[파일생성] README.txt'

# 원격 저장소 연결
git remote add origin https://github.com/chaeso71/hello24.git

# 원격 저장소 연결 확인
git remote -v

# 원격 저장소에 저장
git push -u origin main