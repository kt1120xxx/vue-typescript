# app

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


### 環境立ち上げ手順
```
cd /workspace/dev/vue-type
docker-compose up -d
docker-compose exec app bash
cd app
yarn serve
http://localhost:8080
```

### 開発終了手順
```
exit
docker-compose stop
```