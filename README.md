# ansible-nginx-php-fpm
Ansible-роль для nginx+php-fpm

Самостоятельно напишите Ansible-роль, настраивающую связку nginx+php-fpm и выдающую при обращении к главной странице веб-сервера информацию о php (содержимое index.php — <?php phpinfo();?>).
Дополните роль из п.3: пусть DocumentRoot будет в директории /opt/nginx/ansible. Используйте handler для перечитывания конфигурации nginx.
