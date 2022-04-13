ssh
Переходим в папку /home (ls -la ищем папку .ssh)
Переходим в папку /ssh (ls -la ищем ключ id_rsa.pub)
Если ключа не было id_rsa.pub не найду


Создать ssh ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
Копируем в терминал
Переходим в папку /ssh (ls -la ищем ключ id_rsa.pub)
Смотрим содержимое cat id_rsa.pub
Копируем все содержимое
github -> settings -> SSH and GPG keys -> new SSH key
