-- Adicione esse script no seu SQL para alterar a senha de acordo com a conexão do banco

sudo mysql
ALTER USER 'root'@'localhost' IDENTIFIED BY 'AL04Sql';
FLUSH PRIVILEGES;
