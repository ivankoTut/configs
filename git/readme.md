### глобальный файл .gitignore

Настройка Git для использования этого файла
```shell
git config --global core.excludesfile ~/.gitignore_global
```

Чтобы убедиться, что всё настроено корректно, выполните команду:
```shell
git config --get core.excludesfile
```