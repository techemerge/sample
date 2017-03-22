# sample

### Sample User table

    `CREATE TABLE IF NOT EXISTS users (
        id int(10) unsigned NOT NULL AUTO_INCREMENT,
        name varchar(25) NOT NULL,
        email varchar(30) NOT NULL,
        password varchar(32) NOT NULL,
        PRIMARY KEY (id),
        UNIQUE KEY email (email)
    ) ENGINE=InnoDB  DEFAULT CHARSET=utf8`
    
Added few sample files `UserController.php`, `UserModel.php` to get started.
