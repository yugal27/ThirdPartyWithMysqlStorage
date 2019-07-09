# ThirdPartyWithMysqlStorage
boot + mysql


 desc reports_test;
+--------------+-------------+------+-----+-------------------+-----------------------------+
| Field        | Type        | Null | Key | Default           | Extra                       |
+--------------+-------------+------+-----+-------------------+-----------------------------+
| id           | int(11)     | NO   | PRI | NULL              | auto_increment              |
| reportId     | varchar(64) | NO   |     | NULL              |                             |
| actor        | varchar(64) | YES  |     | NULL              |                             |
| report       | longblob    | YES  |     | NULL              |                             |
| lastModified | timestamp   | NO   |     | CURRENT_TIMESTAMP | on update CURRENT_TIMESTAMP |
+--------------+-------------+------+-----+-------------------+-----------------------------+
