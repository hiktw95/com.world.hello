com.world.hello
===============

session = jsp
DB = mysql
로그인기능=AJAX
mybatis=db connection
깃허브=간트차트+svn


1.DB_NAME = ProfileList

1-1.table name
-UserList
owner		varchar (외래키)
user_id 		 pk(auto increment)
user_lastname 	varchar
user_firstname varchar
user_phone 	char
user_mail 		varchar
user_birth 	date
user_age 		integer
user_note 	text
user_photo 	url
user_group 	varchar (외래키)

-OwnerList
owner	varchar(pk)
password		varchar

-GroupList
Group_name varchar (pk)
Group_contents= varchar
Group_member= integer


db 구축/로그인화면(login.jsp) / 회원가입 			          	태완
서버 구축(톰켓)(maven사용)/주소록선택화면 (select.jsp)		광현
프로필 화면(profile.jsp)						                     선민
