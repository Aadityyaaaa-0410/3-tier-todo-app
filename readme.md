todos-db.cujxsdymzfti.us-east-1.rds.amazonaws.com


CREATE DATABASE todos_db;
USE todos_db;

CREATE TABLE todos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    task VARCHAR(255) NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

INSERT INTO todos (task) VALUES ('Sample Todo 1'), ('Sample Todo 2');



mysql -h $DB_HOST -u admin -p, USE todos_db; SELECT * FROM todos;
curl https://<invoke-url>/todos

npm install express mysql2 cors body-parser pm2 -g

