## Добавить пользователя
> $ sudo adduser username

## Добавить пользователя в группу wheel
> $ sudo usermod -aG wheel username

## Просмотр групп к которым пользователь относится
> $ sudo groups username

## Установить пароль для пользователя 
> $ sudo passwd username

## Добавить пользователя с возможностью правами администратор
> $ sudo usermod -aG wheel username

## Удалить пользователя без удаления файлов профиля
> $ sudo userdel username

## Удалить пользователя c удалением файлов профиля
> $ sudo userdel -r username

## Узнать дату и время
> $ date

## Узнать временную зону
> timedatectl

## Установить временную зону
> timedatectl set-timezone Europe/Moscow

## Применить разрешение безопасности только для папок и подпапок
``` sudo find /full/path/to/folder/ -type d -exec chmod 0755 {} \; ```

## Применить разрешение безопасности только для файлов и файлов в подпапках
``` sudo find /full/path/to/folder/ -type f -exec chmod 0644 {} \; ```