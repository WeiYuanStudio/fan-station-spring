# Fan Station

一站解决收集自己喜欢的东西，做的更类似网址导航吧

## DataBase

### Target Table

| id | name       | type                | intro              | parent_target_id |
|----|------------|---------------------|--------------------|------------------|
| 1  | 望月しいな | Illustrator         |                    |                  |
| 2  | 77haru     | Illustrator_project | by motiduki_shiina | 1                |
| 3  | 宮瀬まひろ | Illustrator         |                    |                  |

### Link Table

| id | target_id | link_type | location            |
|----|-----------|-----------|---------------------|
| 1  | 1         | twitter   | https://twitter.com |

### Link Type Table

| id | link_type | name    | icon                |
|----|-----------|---------|---------------------|
| 1  | 1         | twitter | https://twitter.com |

### User Table

| id | name    | password |
|----|---------|----------|
| 1  | WeiYuan | 0000     |
