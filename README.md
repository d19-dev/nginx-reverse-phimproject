# nginx-reverse-phimproject

Конфиги должны располагаться в директории /etc/nginx/sites-enabled либо в /etc/nginx/sites-available/ с символическими ссылками в sites-enabled.
Для проксирования нового приложения в директории /incl расположен шаблон с подробными комментариями. 

## v26112020
- Изменен порт бэкенда с 443 на 8080 в bitrix.app.phimproject.ru

## v16112020
- Добавлен конфиг для cloud.phimproject.ru
- Изменено правило переадресации для bitrix.app.phimproject.ru
- mail.phimproject.ru перенесён в архив
