# MySQL_Note
MySQL 기능 정리

## Type 
'''
문자열 : Varchar
'''
'''
정수형 : INT
'''


## DataBase

계정 내의 DB 출력 
'''
Show databases;
'''

특정 _DataBase_로 이동
'''
Use _DataBase_
'''






## table

DB -> Tables에 행렬 만들기. (id, title, description, created, author, profile, primary 로 구성) 
'''
create table _table_(
   id int NOT Null Auto_increment , 
   title varchar(100) not null ,
   description Text Null,
   created datetime not null,
   author varchar(30) NUll, 
   profile varchar(100) null,
   primary key(id));
'''


DB -> tables -> _table_ 에 행열 만들어서 값 추가 
'''
INSERT INTO _table이름_ (title, description, created_시간, author, profile) values('Mysql', '데이터 입력', Now(), 'heonsoo', 'Hello, World !' )
'''

특정 DB내의 tables 출력
'''
Show tables;
'''

Table의 정보 조회 ( field, Type, Null 등 ) 
'''
Desc _table_
'''


특정 table(__table__) 값 모두 출력 
'''
select*from _table_
'''

