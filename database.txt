CREATE DATABASE `dbtuts` ;
CREATE TABLE `dbtuts`.`users` (
`user_id` INT( 10 ) NOT NULL AUTO_INCREMENT PRIMARY KEY ,
`first_name` VARCHAR( 25 ) NOT NULL ,
`last_name` VARCHAR( 25 ) NOT NULL ,
`user_city` VARCHAR( 45 ) NOT NULL
) ENGINE = InnoDB;