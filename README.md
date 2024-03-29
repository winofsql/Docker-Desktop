# [Docker-Desktop](https://docs.docker.com/desktop/install/windows-install/)

![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/a9e46f69-c12a-48ac-b317-3a2e5401fccd)

![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/3aa6aa10-5867-43f8-995b-2aba7a1d5ad7)
```
"C:\Program Files\Docker\Docker\Docker Desktop.exe"
```

### PATH 環境変数
```
C:\Program Files\Docker\Docker\resources\bin
```

![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/2b17df72-b42d-4cd7-92ca-fa4539634476)

### [Xampp に合わせて](https://hub.docker.com/_/php/tags?page=1&name=8.2.12-apach)
![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/bb5a023b-6297-4d45-ad4a-b62a4d1ab878)

![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/7030f225-a2cf-4d20-8d0f-611f941ec28a)
```
docker pull php:8.2.12
```

### MySQL は適当に以下を実行したらインストールされた
```
docker run -e MYSQL_ROOT_PASSWORD=password mysql
```

### 実際のコンテナ時に MYSQL_ROOT_PASSWORD 変数に対して password

![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/d110c937-8ee7-4f26-821f-8d408af371a3)

![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/065e852e-34f9-46d9-9363-0afc7dd522f9)

![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/f934eec3-8c60-49b6-8308-23e2096205a7)

![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/b5c19053-9a0a-4105-91dc-efb11edccdbc)

![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/70e37c54-c4af-4968-8eed-6f7a3cf07cae)

![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/dbb1c702-2f08-477e-943d-acfbebb64206)

### MariaDB の キャラクタセット設定
![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/ba1d640d-3c9e-4eb4-a0fd-0c81251f7520)

※ 設定してからデータベースを作成\
![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/644afa9a-e9fb-4607-b017-d4434758a0b6)
```
character-set-server=utf8mb4
collation-server=utf8mb4_general_ci
```

### [Flask ( 簡易テスト用 )](https://hub.docker.com/r/torbthemagni/flask-actions-web-project/tags)
![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/42d729f7-2424-4a36-bf1c-cfced958fd7a)


### WSL
```
wsl -l -v
```
![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/7368d740-75be-4216-bead-b2cc28444e87)

![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/8e1dc2d7-2cee-44cb-9470-48cc7b22d739)


### VScode 拡張
![image](https://github.com/winofsql/Docker-Desktop/assets/1501327/84961b1f-e2da-400d-b4d2-abfca9997e75)
