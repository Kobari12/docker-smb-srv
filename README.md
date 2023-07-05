# 使い方

```console
$ git clone https://github.com/Kobari12/docker-smb-srv.git
$ cd docker-smb-srv
```

```console
$ vi .env

USERNAME=*****
PASSWORD=*****
```

or


```console
$ echo "
USERNAME=*****
PASSWORD=*****
" >> .env
```

```console
$ docker-compose up --build -d
```
