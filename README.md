## Dashboard 프로젝트

### 초기 세팅

- master branch를 main branch로 변환

```zsh
git branch -M main
```

- 원격 주소를 추가한다.

```zsh
git remote add origin https://github.com/chris-fe-study/mihyun-dashboard.git
git remote -v
```

- 프로젝트 기본 환경 push

```zsh
// changes -> staged changes
git add .
// staged changes -> commit message
git commit -m "message"
// commit log 확인
git log
// git push
git push -u origin main
```

### develop 작업 전

- 원격 주소에 있는 브랜치 동기화

```
git fetch origin
```

- 원격에 있는 develop 브랜치에서 로컬 develop 브랜치를 분리

```zsh
git checkout -b develop origin/develop
```

- develop 브랜치에서 feature 브랜치를 분리해서 시작한다.

```
git checkout -b feature/{#이슈번호}-{작업명}-{작업자}
```
