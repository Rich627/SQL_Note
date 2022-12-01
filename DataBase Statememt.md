## 資料庫相關
```SQL
#創資料庫
CREATE DATABASE x;
#刪資料庫
DROP DATABASE x;
```

## 資料表相關
```SQL
#新增table
CREATE TABLE xx(
	col1 type,
	col2 type
);
#刪除table
DROP table xx;
#新增現有table的col
ALTER TABLE x ADD COLUMN col1 type;
#刪除現有tabe的col
ALTER TABLE x DROP COLUMN col
#不能為空限制敘述
CREATE TABLE table_name(
	col1 INT NOT NULL
);
#已存在的table
ALTER TABLE table_name(
	id INT NOT NULL
);
```