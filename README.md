# TIL

2023.05.24 Nginx 설정을 잘하자

Nginx 설정 변경
-  그동안 web server을 실행했을 때 css 적용이 안되던 것은 /etc/nginx/nginx.conf 의 기본 user 설정이 ubuntu가 아닌 다른 것이었다.
-  아마 nginx 설정의 location과 시스템의 user 설정이 달라서 생긴 문제가 아닌가 싶다.
-  그래도 이제 css 변경하면 그대로 먹힌다. 이상한 점은 local에서는 static에 있는 사진 불러오기가 안되는데 prod에서는 static에 있는 사진이 불러와진다.
-  이것에 대한 이유는 모르겠다.
-  또 python manage.py runserver를 통해 prod 서버를 실행 했었는데 그것 없이 nginx 설정을 끝낸 것만으로도 서버가 운영 되는 것을 알게 되었다. nginx 서버에 대한 이해가 많이 부족했고, 아직도 많이 부족하다. runserver가 개발 단계에서만 실행 한다는 것을 이해하였다. 그동안 runserver 명령어가 nginx 서버 명령어 포함해서 같이 되는건지 알았지... 대충 읽고 넘어간게 문제였다.
-  앞으로 남은 것은 css 수정과 발표 자료를 만드는 것이고, 발표가 마무리되는대로 추가 기능과 문서 작성을 진행할 것이다.
-  이상.
