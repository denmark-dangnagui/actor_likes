# actor_likes
데이터베이스안에 있는 배우들을 좋아요를 눌러 순위를 높이고 혹은 삭제할 수 있는 사이트를 구성해봤습니다.

python3 app.py

-pymongo, flask, render_template,request 등의 기능을 사용하여 데이터를 받아오고 보내주는
서버를 구성하였습니다.

index.html

-두개의 POST요청을 통해 하나는 db에 저장할 수 있는 ajax콜을 만들었고 하나는 db에서 삭제할 수 있는 콜을
만들었습니다. 또한 GET요청을 통해 클라이언트 화면상에 db에 있는 배우들을 나타내는 콜을 만들었습니다.
