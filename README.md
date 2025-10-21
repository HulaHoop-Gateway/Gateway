# Gateway

# db 생성 
CREATE DATABASE com_test_db;
GRANT ALL PRIVILEGES ON com_test_db.* TO ''@'%';
SHOW GRANTS FOR ''@'%';
USE com_test_db;


# table 생성
CREATE TABLE user (
    id BIGINT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100)
);


# 초기데이터
INSERT INTO user (name) VALUES ('Alice');
INSERT INTO user (name) VALUES ('Bob');
INSERT INTO user (name) VALUES ('Charlie');
INSERT INTO user (name) VALUES ('Diana');
INSERT INTO user (name) VALUES ('Ethan');
INSERT INTO user (name) VALUES ('Fiona');
INSERT INTO user (name) VALUES ('George');
INSERT INTO user (name) VALUES ('Hannah');
INSERT INTO user (name) VALUES ('Ian');
INSERT INTO user (name) VALUES ('Julia');
INSERT INTO user (name) VALUES ('Kevin');
INSERT INTO user (name) VALUES ('Luna');
INSERT INTO user (name) VALUES ('Max');
INSERT INTO user (name) VALUES ('Nina');
INSERT INTO user (name) VALUES ('Oscar');
INSERT INTO user (name) VALUES ('Paula');
INSERT INTO user (name) VALUES ('Quentin');
INSERT INTO user (name) VALUES ('Rachel');
INSERT INTO user (name) VALUES ('Sam');
INSERT INTO user (name) VALUES ('Tina');

