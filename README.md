# docker-compose-learning-wordpress
docker compose 학습을 위한 git입니다.

1. git bash 터미널을 엽니다.

2. WordPress를 설치할 폴더를 하나 만듭니다.

```console
mkdir wordpress
```

3. 만든 폴더에 들어갑니다.

```console
cd wordpress
```

4. git clone을 진행합니다

```console
git clone https://github.com/Haizena/docker-compose-learning-wordpress.git .
```

5. compose up을 진행합니다.

```console
docker compose up
```

6. mysql의 ready for connection을 확인하면 compose에 설정한 포트번호를 통해 접속합니다.

```console
http://localhost:3000
```
