```SQL
CREATE TABLE admins (
  id INT AUTO_INCREMENT PRIMARY KEY,
  login VARCHAR(50) NOT NULL UNIQUE,
  password_hash VARCHAR(255) NOT NULL
);

-- Insert default admin (login: admin, password: 123)
INSERT INTO admins (login, password_hash) VALUES ('admin', '202cb962ac59075b964b07152d234b70');
```
