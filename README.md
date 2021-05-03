<h1>Отчет по лобораторной 03</h1>
</br>gmail почта - sgolenkov2002@gmail.com </br>
telegram - @Xacker_ducker

<h2>Ход выполнения лабораторной работы:</h2>

[репозиторий lab03](https://github.com/Alex1505Gold/lab03)</br>
На скриншотах выполненные команды и результат их выполнения
![screen01](./screens/screen01.png)</br>
![screen02](./screens/screen02.png)</br>
![screen03](./screens/screen03.png)</br>
![screen01](./screens/screen04.png)</br>
![screen02](./screens/screen05.png)</br>
![screen03](./screens/screen06.png)</br>
![screen01](./screens/screen07.png)</br>
![screen02](./screens/screen08.png)</br>
![screen03](./screens/screen09.png)</br>
![screen01](./screens/screen10.png)</br>
![screen02](./screens/screen11.png)</br>
![screen03](./screens/screen12.png)</br>

<h2>Ход выполнения домашней работы:</h2>

При помощи следующих команд была создана новая директория, склонирован репозиторий и проинициализирован новый репозиторий</br>
```
mkdir timp_lab03
cd timp_lab03
git clone https://github.com/tp-labs/lab03.git .
rm -rf CMakeLists.txt
rm -rf preview.png
rm -rf LICENSE
rm -rf README.md
git remote remove origin
git remote add origin https://github.com/Alex1505Gold/timp_lab03.git
```

В папке formatter_lib был создан файл CMakeLists.txt и открыт через nano для редактирования
```
cd formatter_lib<
touch CMakeLists.txt
nano CMakeLists.txt `
```
</br>
В файл было записано следующее</br>
![screen01](./screens/hw_01.png)</br>
Затем была создана папка _ build, в которую был собран проект</br>
```
mkdir _build
cd _build
cmake ..
cmake --build . `
```
</br>
Аналогичные действия были проведены с папкой formatter_ex_lib, однако в файл CMakeLists.txt было записано:</br>
![screen01](./screens/hw_02.png)</br>
Аналогичные действия были проведены с папкой hello_world_application, однако в файл CMakeLists.txt было записано:</br>
![screen01](./screens/hw_03.png)</br>
Аналогичные действия были проведены с папкой solver_application, однако в файл CMakeLists.txt было записано:</br>
![screen01](./screens/hw_04.png)</br>
После все было залито на гитхаб</br>
```
git add .
git commit -m "Complete task"
git push origin master
```
