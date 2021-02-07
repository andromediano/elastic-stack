Running the Elastic Stack on Docker
================================================================================

시작하기
--------------------------------------------------------------------------------

### `data`디렉토리 생성

```sh
mkdir elasticsearch/data
```

### 최초 구동

```sh
docker-compose up --build -d
```

### 구동/중지

```sh
docker-compose start
docker-compose stop
```

### 삭제

```sh
docker-compose down
```
