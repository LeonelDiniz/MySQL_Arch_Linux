## MySQL_Arch_Linux
Instalando e Configurando o MariaDB/MySQL no Arch Linux e distro baseadas

## Vamos lá!

Mesmo se você pedir para instalar o MySQL irá vir o MariaDB em algumas distro como Arch Linux e baseadas.

Primeiro de tudo você tem que está como **ROOT**

Instalando

``# pacman -S mariadb``

Agora vamos incializar os arquivos do MySQL

``# mysql_install_db --user=mysql --basedir=/usr --datadir=/var/lib/mysql`` 

Startando o serviço MySQL

``# systemctl start mysqld``

Configurando o MySQL para inicializar toda vez que a máquina iniciar

``# systemctl enable mysqld``

Configurando MySQL

``# systemctl start mysqld``

Nessa etapa irá perguntar qual a senha do root, como é a primeira vez que instalamos o banco, você pode apenas dá **ENTER**

> Set root password? Y
Defina sua senha:

No meu caso aceitei todos os termos: **Y**

#Para entrar no MariaDB:

``$ mysql -u root -p``





