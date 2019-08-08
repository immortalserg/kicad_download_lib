# Скрипт для закачки и настройки библиотек для KiCad

## Описание

устанавливает стандартные библиотеки KiCad и пользовательские библиотеки, прописывает пути к библиотекам и переменным

## Установка
установите git, tee и wget

apt install git wget tee

закройте программу KiCad

для установки создайте папку для библиотек

в консоли выполните:

wget https://raw.githubusercontent.com/immortalserg/kicad_download_lib/master/download_kicad_lib

chmod +x download_kicad_lib

./download_kicad_lib

дождитесь окончания работы скрипта

## Библиотеки

- официальные KiCAD
- AB2 Tech
- DiGiKey
- Sparkfun
- Библиотеки УГО по ГОСТ
- Simisto 
- Elessar Cuthalion
- Contextual Electronics
- Anton Donets

## Версии

### 0.1.1 от 08.08.2019

- добавлены библиотеки Anton Donets 
- добавлено в имя файлов бэкапа конфигов дата и время создания бэкапа

### 0.1 
