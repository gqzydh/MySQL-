# MySQL 入门



- ### Mysql 登录、退出###

- ### 修改Mysql提示符

- ### Mysql常用命令

- ### Mysql语句规则

- ### 数据库操作###

  ​

Mysql 登录、退出

- `mysql -uroot -proot -P3306 -h127.0.0.1`


- mysql > `exit`
- mysql > `quit`
- mysql > `\q`



- ### Mysql常用命令

  - CREATE  DATABASE  数据库名字    // 新建数据库

  - show DATABASES;    //查看所有数据库

  - `USE test`;  进入test数据库

  - `SELECT DATABASE();`   显示当前用户打开的数据库

  -  创建数据表

    - ```mysql
      CREATE TABLE[IF NOT EXISTS] table_name(
      	cloumn_name data_type.
        ....
      )
      ```

  - 查看数据库中所有的数据表列表

    - ```mysql
      SHOW TABLES FROM mysql;
      ```

  - 查看数据表结构

    - ```mysql
      SHOW COLUMNS FROM tb1;  //tb1 数据表
      ```

  -  向数据表写入记录

    ```mysql
    INSERT[INTO] tb1_name[(col_name,...)] VALUES(val,...)
    ```

  - 数据表记录查找

    ```mysql
    SELECT expr,...FROM tb1_name
    ```

    ​