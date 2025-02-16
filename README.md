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
// git push
git push -u origin main
```
