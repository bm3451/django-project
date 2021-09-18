# django-project
CCCR django project
1.프로젝트 개요

python-django를 배워 간단한 웹페이지를 제작
가상머신(centos8)을 3대 사용하여 환경구현
가상머신 1 : Database-server
가상머신 2 :  djnago-server(AppServer)
가상머신3  :  Apache(Web server)

2. 프로젝트 진행환경

[기술스택]
os
-centos 8

Server-side
 -python 3.8.10
 -Django 3.2.3
 -Mysql 5.7

Client-side
-Bootstrap

[버전/소스 관리]
-Git / Github



3.프로젝트 구조



4. 배포 인프라 구조
             request                                     WISGI                                   ORM(Django-kernel)
client   ------>    Apache  --    Django    --      Mysql]
           ←----  (192.168.221.147)     (192.168.221.146)      (192.168.221.145)
		response



5. 동작화면

[메인페이지]

-> 질문 리스트 전체를 보여준다.



[로그인]
-> 로그인을 하지않으면 질문을 작성할 수 없다.
->로그인에 성공하면 상단(네비게이션바)에 로그인표시가 로그아웃으로 변경된다.




[회원가입]


->계정이 없다면 회원가입 진행








[새 질문 등록]


-> 메인페이지의 질문등록하기 버튼을 누르면 새 질문을 등록할 수 있는 페이지로 넘어간다.
질문을 등록하고 저장하기 버튼을 누르면 메인 질문리스트에 업로드된다.

[검색 기능]



-> 상단에 있는 검색창에 해당키워드를 입력하면, 그 키워드가 들어간 질문리스트를 검색해준다.

6.공부한 내용들

centos 가상환경을 각각만든 후에 ssh 연결하는 방법을 알게되었다.
mysql과 django를 연결하는 방법을 공부하게되었다.
Django에서 view,model,url을 사용하여 연결하는 방법을 공부하게되었다.

