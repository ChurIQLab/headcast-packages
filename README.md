# Пакеты HeadCast

Репозиторий apt программ системы HeadCast для Debian 12 и совместимых систем, amd64 и arm64. Исходного кода здесь нет.

Первая установка: скачайте `.deb` со страницы [выпусков](https://github.com/ChurIQLab/headcast-packages/releases) и выполните:

```
sudo apt install ./epgcast_1.2.1_amd64.deb
```

Пакет сам подключит этот репозиторий. Обновление:

```
sudo apt update && sudo apt install --only-upgrade epgcast
```

Для Windows на странице выпусков лежит `epgcast-windows-amd64.exe`.

Индекс подписан ключом `0086 E6DD 3EF0 FA2C 0F9F  69C2 1FD0 D6FA F5F6 D202`.
