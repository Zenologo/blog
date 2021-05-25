## 新建折扣码表

### 表名称: discount_code

| Field            | Type         | Null | Key | Default           | Extra                                         |
|------------------|--------------|------|-----|-------------------|-----------------------------------------------|
| id               | int unsigned | NO   | PRI | NULL              | auto_increment                                |
| code             | varchar(32)  | NO   |     | NULL              |                                               |
| site_id          | int          | NO   |     | NULL              |                                               |
| member_level_id  | int unsigned | NO   |     | NULL              |                                               |
| discount_percent | int          | YES  |     | NULL              |                                               |
| discount_amount  | int          | YES  |     | NULL              |                                               |
| is_active        | int          | NO   |     | NULL              |                                               |
| created_date     | timestamp    | YES  |     | CURRENT_TIMESTAMP | DEFAULT_GENERATED                             |
| modified_date    | timestamp    | YES  |     | CURRENT_TIMESTAMP | DEFAULT_GENERATED on update CURRENT_TIMESTAMP |

