### json-server를 heroku로 배포하기

<br>

1. 레포지토리에 등록 (처음에만)

```
heroku git:remote -a <app-name>
```

2. 배포

```
git add .
git commit -am "hosting a json-server"
git push heroku master
```

<br>

[참고](https://medium.com/cbazil-dev/hosting-your-backend-api-json-server-on-heroku-1a3b9b3d8f82)
