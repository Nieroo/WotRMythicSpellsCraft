# Крафт мифических заклинаний «Pathfinder: Wrath of the Righteous»

Из мифических заклинаний [Pathfinder: Wrath of the Righteous](https://store.steampowered.com/app/1184370/Pathfinder_Wrath_of_the_Righteous__Enhanced_Edition/) по умолчанию нельзя создавать свитки и зелья. Данный мод для OMM (Owlcat Modifications Manager) даёт возможность создавать свитки из всех мифических заклинаний до 9-го круга включительно и зелья из мифических заклинаний до 6-го круга включительно, имеющих цель (target) "существо или существа (target or targets)", но не имеющих дальность (range) "на себя (personal)". Дополнительное ограничение для зелий связано с правилами ролевой системы Pathfinder, описанные для черты [Brew Potion](https://aonprd.com/FeatDisplay.aspx?ItemName=Brew%20Potion). Также данный мод не позволяет создавать зелья для мифических заклинаний, у которых нет никакого положительного эффекта для самого пьющего.

Мод поддерживает любую локализацию игры. Мод вносит зависимость в сейв и если при помощи данного мода созданы свиток или зелье и они не уничтожены, то загрузить такой сейв без данного мода не получится.

## Установка (для Windows)

1. Со страницы релизов скачайте архив с последней версией мода.
2. Перейдите в папку `%localappdata%low\Owlcat Games\Pathfinder Wrath Of The Righteous` (далее — папка игры).
3. Распакуйте из архива папку `Modifications` в папку игры.
4. Если в папке игры нет файла `OwlcatModificationManagerSettings.json`, то извлеките его в папку игры из архива.
5. Если в папке игры уже есть файл `OwlcatModificationManagerSettings.json`, то отредактируйте его: найдите массив `EnabledModifications` (или создайте на верхнем уровне, если его нет) и добавьте в него значение `Nieroo_WotRMythicSpellsCraft`.
6. Если мод установлен правильно, то в игре при нажатии `Ctrl+M` в окне OMM можно увидеть название мода

## Список изменений

Ознакомиться со списком внесённых изменений можно в файле [CHANGELOG.md](https://github.com/Nieroo/WotRMythicSpellsCraft/blob/main/CHANGELOG.md).
