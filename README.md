> 250423 사용 가능 확인


## 설치하기

실행 : `docker compose up -d`
종료 : `docker compose down`

## 페이지 접근

http://localhost:6875

## 개발 경로 및 사용법

`/bookstack_app_data/www`

경로를 수정하면 됩니다.

공식 문서 : https://www.bookstackapp.com/docs/

유튜브 : https://www.youtube.com/watch?v=Tf74_2iphz0


### 왜 라라벨 코드가 안보이나요?

저도 라라벨 코어로 했으면 좋겠다는 많은 끌림이 있다보니 코어를 다운받아봤습니다.
일부러 쪼개놓고 이 폴더에서 커스터한 부분만 추가해라.
라는 느낌으로 사용하게끔 하는 것 같아요.

이렇게 했을 때 장점은 관리 포인트 영역이 확실히 준다는 부분은 있을 것 같습니다. 뭐 그렇다고 해서 라우트 설정같은 것들이 안먹히지는 않으니 자유롭게 사용하면 될 것 같습니다.


## 비밀번호 설정


```angular2html
admin@admin.com
password
```


## DB 접근 방법

```angular2html
id : bookstack
pw : password
```

자세한 정보는 docker-compose.yml 에 있습니다


## 업데이트 방법
https://hub.docker.com/r/linuxserver/bookstack
