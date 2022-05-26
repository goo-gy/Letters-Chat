# Letters-Chat
Letter Chatting Server


# letters-graphQL

## env 설정

```
SECRET_KEY=[]
API_URL=[]
DB_HOST=[]
DB_user=[]
DB_password=[]
```

- JWT SECRET KEY 설정
- API URL 설정
- DB 정보 설정

--- 

## 개발환경 Init

``` shell
npm run env:init
```

- MySQL
  설치 및 Database 생성
- Kafka
  - zookeeper
  - 


## DB Scheme 생성

- Docker 설치 후

```shell
npm run db:migrate
```


### migration 추가
``` shell
npx babel-node migration.js add migration [migration name]
```