# Темная тема для grub2

## Описание 

Стандартная тема из дистритива Alt regular. Сменил фон на черный (оставил при этом надпись "Sisyphus" и поменял цвета для контраста на тёмном фоне). Выглядит приемлимо и приятно глазу! 
Приятного использования сообществу Alt Linux. 

## Установка

1) Для установки склонируейте репозиторий
```
git clone https://altlinux.space/pbarovsky/dark-sisyphus.git
```

2) Далее переместите тему в папку `boot/grub`
```
su -
mv /путь/к/папке/dark-sisyphus /boot/grub/themes/
```

3) Открываем `grub.cfg`
```
nano /etc/sysconfig/grub2
```

4) Редактируем строку `GRUB_THEME`
```
GRUB_THEME="/boot/grub/themes/dark-sisyphus/theme.txt"
```

5) После этого пересобираем grub
```
grub-mkconfig -o /boot/grub/grub.cfg
```

6) Перезагружаем систему




