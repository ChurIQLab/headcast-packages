# Пакеты HeadCast

Репозиторий apt программ системы HeadCast для Debian 12 и совместимых систем, amd64 и arm64. Исходного кода здесь нет.

Первая установка: откройте [последний выпуск](https://github.com/ChurIQLab/headcast-packages/releases/latest), скачайте `.deb` для своей архитектуры (обычно `amd64`) и выполните в папке с файлом:

```
sudo apt install ./epgcast_<версия>_amd64.deb
```

Вместо `<версия>` — номер из имени скачанного файла. Пакет сам подключит этот репозиторий. Обновление:

```
sudo apt update && sudo apt install --only-upgrade epgcast
```

Для Windows в том же выпуске лежит `epgcast-windows-amd64.exe`.

Индекс подписан ключом `0086 E6DD 3EF0 FA2C 0F9F  69C2 1FD0 D6FA F5F6 D202`.
