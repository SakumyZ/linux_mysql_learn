### 创建账户并且设置登录密码
~~~shell
    mysql -u <usrName> -p 
~~~

### 退出mysql
~~~shell
    exit                    
~~~

### 重置密码
~~~shell
    mysqladmin -u <usrName> -p password "********"   
~~~
--------------------
### 查看所有数据库
~~~sql
    show database                      
~~~

### 切换数据库
~~~sql
    use <databaseName> UTF-8   
~~~

### 查看所有表
~~~sql
    show tables                   
~~~

### 查看表字段
~~~sql
    desc <tableName>                   
~~~

### 显示create database 语句是否能够创建指定的数据库
~~~sql
    show create database  
~~~

### 显示create database 语句是否能够创建指定的数据库            
~~~sql
    show create table <tableName>
~~~
     
### 查看当前用户
~~~sql
    select user()     
~~~
    
### 查看当前数据库     
~~~sql
    select database()                
~~~

------------

### 创建数据库
~~~sql
    create database <databaseName>
~~~ 
### 创建表 
~~~sql
    create table                   
~~~

--------------------
### 向表中插入
~~~sql
    insert into <table_name> values()
~~~

### 删除操作
~~~sql
    delete from <table_name> where <条件>
~~~  
  
### 表的更新
~~~sql
update <table_name> set <column_name> = <表达式> where <条件>
~~~

### 表的查询
~~~sql
    --where表示限定条件
    select <column_name> from <table_name> where <条件>

    --*为通配符，意为所有
    selec * from <table_name>
~~~

### 删除触发器 
~~~sql
~~~
