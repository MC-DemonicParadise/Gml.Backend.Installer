# Описание репозитория

Этот репозиторий содержит скрипты для установки, обновления и удаления Gml.Backend. Скрипты упрощают процесс управления серверной частью Gml, обеспечивая легкость и удобство выполнения необходимых операций. 

## Установка на русском

Для установки Gml.Backend выполните следующие команды в удобной для вас директории (для работы скрипта необходим `curl`, [инструкция по установке curl](https://losst.pro/ustanovka-curl-v-ubuntu)):

```sh
curl -O https://raw.githubusercontent.com/GamerVII-NET/Gml.Backend.Installer/master/gml-installer-rus.sh
chmod +x ./gml-installer-rus.sh
./gml-installer-rus.sh
```

## Обновление

Для обновления Gml.Backend выполните следующую команду в директории, где находятся файлы `docker-compose.yml` и `.env`:

```sh
curl -s https://raw.githubusercontent.com/MC-DemonicParadise/Gml.Backend.Installer/master/gml-updater-rus.sh | sh
```

## Удаление

Для удаления Gml.Backend выполните следующую команду в директории, где находятся файлы `docker-compose.yml` и `.env`:

```sh
curl -s https://raw.githubusercontent.com/GamerVII-NET/Gml.Backend.Installer/master/gml-deleter-rus.sh | sh
```

## Преимущества

- **Простота установки**: Установка Gml.Backend осуществляется в несколько команд.
- **Удобное обновление**: Легкое обновление сервера с помощью одной команды.
- **Быстрое удаление**: Возможность удаления всей серверной части также в одну команду.
- **Автоматизация**: Скрипты обеспечивают автоматизацию рутинных задач по управлению серверной частью.

Этот репозиторий предназначен для тех, кто хочет упростить управление своим сервером Gml.Backend, минимизируя ручные операции и возможные ошибки.
