# Темы для Grub

oldBIOS-dark сделана на основе темы [oldBIOS](https://github.com/Blaysht/grub_bios_theme)

## Установка

1) Для установки склонируейте репозиторий
```
https://github.com/pbarovsky/grub2-themes.git
```

2) Далее переместите тему в папку `boot/grub`
```
su -
mv /путь/к/папке/oldBIOS-dark /boot/grub/themes/
```

3) Открываем `grub.cfg`
```
nano /etc/sysconfig/grub2
```

4) Редактируем строку `GRUB_THEME`
```
GRUB_THEME="/boot/grub/themes/oldBIOS-dark/theme.txt"
```

5) После этого пересобираем grub
```
grub-mkconfig -o /boot/grub/grub.cfg
```

6) Перезагружаем систему




