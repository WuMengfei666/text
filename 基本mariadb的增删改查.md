1������һ�����ݿ�   create database wumengfei;

2��ʹ�����ݿ�   use wumengfei;

3���鿴���ݿ�   show databases;

4������һ�����   MariaDB [wumengfei]> create table ww(
    -> name varchar(10),
    -> sex varchar(3));
Query OK, 0 rows affected (0.15 sec)

5���ڱ�������Ԫ��   insert into www value("a","A");

6���鿴���Ԫ��   select * from www;

7��ɾ�����Ԫ��   delete from www where name="a";

8�����ı��Ԫ��   update www set name="b" where sex="nan";

9�����ݱ���һ�����ԣ�����ģ���������һ�����ԣ�ǰ��ģ�   
    select sex from www where name="y";

10��ɾ�����   drop database wumengfei;

11���鿴���ݿ�   show databases;

