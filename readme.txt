show databases;
SHOW GLOBAL VARIABLES;
create database online_shopping;

show databases;
use online_shopping;
show tables;
create table shopping(user_id int,
                   first_name varchar(255),
                   email_id varchar(255),
                   phone varchar(255));
show tables;
describe users;
select * from users;
insert into users values(11,
                       'dharshini',
                       'dh123@gmail.com',
                       '12356767890');
select * from users;     
insert into users values("TEN",
                       'dharshini',
                       'dh123@gmail.com',
                       '12356767890');
select * from users;  

insert into users values('11',
                       NULL,
                       'dh123@gmail.com',
                       NULL);
select * from users;   
describe users;                    
-- key - any of the column can contain dupliates

truncate table users;
-- To delete of data in table,not going to drop/deleete entire table or other associate indices
select * from users;

drop table users;
-- Drop the entire table
