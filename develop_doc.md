# Документация разработчика

## Текст программы

### Наименование программы

Image Info Extractor — это приложение для извлечения и отображения метаданных изображений из выбранной пользователем папки с использованием библиотеки Qt на языке C++.

### Область применения

Программа предназначена для извлечения информации о изображениях, таких как размер, разрешение, глубина цвета и тип сжатия. Она может быть использована в учебных целях, а также для демонстрации работы с метаданными изображений.

## Назначение программы

Реализация и визуализация следующих функций:

- Извлечение метаданных изображений из файлов в выбранной директории.
- Отображение информации о каждом изображении в табличном формате.
- Предоставление графического интерфейса пользователя (GUI) для взаимодействия с изображениями.

## Функциональные возможности

- Выбор папки для загрузки изображений.
- Извлечение и отображение информации о каждом изображении, включая:
1. Имя файла

2. Размер (пиксели)

3. Разрешение (dpi)

4. Глубина цвета

5. Тип сжатия

## Описание программы

### Структура программы

**ImageInfoExtractor**: главный класс приложения, наследующийся от QWidget.

### Методы инициализации:

__init__: инициализация приложения, установка заголовка, размеров окна и создание виджетов.

### Методы обработки событий:

- **chooseDirectory**: открытие диалогового окна для выбора папки.
- **loadImages**: извлечение и отображение информации о изображениях из выбранной директории.
  
Используемые библиотеки и модули

- **Qt**: библиотека для создания графического интерфейса пользователя.
- **QFileDialog**: для выбора папки с изображениями.
- **QTableWidget**: для отображения информации в табличном формате.
- **QImage и QFileInfo**: для работы с изображениями и получения их метаданных.
  
## Логические структуры данных

### Переменные класса:

**self.table**: таблица для отображения информации об изображениях.

### Виджеты интерфейса:

- Кнопка (QPushButton) для выбора папки.
- Таблица (QTableWidget) для отображения информации о загруженных изображениях.

## Взаимодействие с пользователем

- Пользователь нажимает кнопку **"Выбрать папку"** для выбора директории с изображениями.
- После выбора папки программа загружает изображения и отображает их метаданные в таблице.

## Инструкция по установке и запуску

### Требования к системе

- Компилятор C++ (например, g++, MSVC).
- Установленная библиотека Qt 5.x или выше.

## Установка

- Установите Qt и необходимые инструменты для разработки.
- Скомпилируйте проект, используя CMake или qmake.

## Запуск программы

- Сохраните код программы в файл main.cpp, mainwindow.h и mainwindow.cpp.
- Скомпилируйте и запустите приложение:

```bash
./ImageInfoExtractor
```

## Инструкция пользователя

- Запустите приложение.
- Нажмите кнопку "Выбрать папку" и выберите директорию с изображениями.
- Просмотрите информацию об изображениях в таблице.
  
## Требования к техническим характеристикам

- **Процессор**: с тактовой частотой не менее 1 ГГц.
- **Оперативная память**: не менее 512 МБ.
- **Дисплей**: с разрешением не менее 1024x768 пикселей.
  
## Обработка ошибок

Программа предусматривает обработку ошибок при выборе папки и загрузке изображений. Если возникает ошибка, пользователь уведомляется через интерфейс.

## Дополнительные сведения

### Поддержка форматов изображений

Программа поддерживает следующие форматы изображений:

- JPEG
- PNG
- GIF
- BMP
- TIFF
- PCX
  
## Сопровождение и развитие

Код программы хорошо структурирован и снабжен комментариями, что облегчает его поддержку и развитие. Для добавления новых функций можно расширять класс ImageInfoExtractor, добавляя соответствующие методы и элементы управления.

## Ссылки на используемые стандарты

При разработке документации учтены требования следующих стандартов:

- **ГОСТ 19.101-77** — Виды программ и программных документов.
- **ГОСТ 19.402-78** — Описание программы.
- **ГОСТ 19.501-78** — Формуляр. Требования к содержанию и оформлению.
- **ГОСТ 19.505-79** — Руководство оператора.
  
## Заключение

Данная программа предоставляет удобный инструмент для извлечения информации об изображениях. Структура кода и документация соответствуют стандартам, что облегчает дальнейшее сопровождение и развитие приложения.
