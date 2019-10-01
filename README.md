# OpenWrt Firmware Selector Wizard

The wizard utilises the changes proposed [here](https://github.com/openwrt/openwrt/pull/2192).  
Along with this, the feature to build custom images utilises [Attended Sysupgrade Server](https://github.com/aparcar/attendedsysupgrade-server)

## Features

* Easily search devices
* Option to download Vanilla images
* Option to download custom images

## Setting up 

You can set it up easily:
1. Clone the repository
2. Use [yarn](https://yarnpkg.com/en/) to install package dependencies  
``` yarn install ``` 
3. Use the following command to start a dev server:  
``` yarn start ```

## Deployment

In order to deploy the web app, follow the following steps:

* For gh-pages:  
    1. ``` yarn deploy ```
    2. Enable Github Pages setting to use gh-pages branch.


* Elsewhere:  
    1. Build the app using:   
    ``` yarn build ```
    2. Host the files from `/build` directory.
Мастер выбора прошивки OpenWrt
Мастер использует изменения, предложенные здесь.
Наряду с этим, функция для создания пользовательских образов использует Attended Sysupgrade Server.

черты
Легко искать устройства
Возможность скачать изображения ванили
Возможность загрузки пользовательских изображений
Настройка
Вы можете легко настроить его:

Клонировать хранилище
Используйте пряжу для установки зависимостей пакетов
пряжа установить
Используйте следующую команду для запуска сервера dev:
начало пряжи
развертывание
Чтобы развернуть веб-приложение, выполните следующие действия:

Для GH-страниц:

развертывание пряжи
Включите настройку Github Pages, чтобы использовать ветку gh-pages.
В другом месте:

Создайте приложение, используя:
сборка пряжи
Разместите файлы из каталога / build.
