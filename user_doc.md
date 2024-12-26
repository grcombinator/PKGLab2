# Пользовательская документация

## 1. Введение

Программа Image Info Extractor предназначена для извлечения и отображения информации об изображениях из выбранной пользователем папки. Приложение позволяет пользователям просматривать метаданные изображений, такие как размеры, разрешение, глубина цвета и тип сжатия.

## 2. Системные требования

- Операционная система: Windows 7 и выше, macOS, Linux
- Программное обеспечение: C++ с установленной библиотекой Qt 5.x или выше

Аппаратные требования:

- Минимум 1 ГБ ОЗУ
- 100 МБ свободного места на диске
  
## 3. Установка

### 3.1 Установка Qt

- Перейдите на официальный сайт Qt: [qt.io].
- Скачайте и установите последнюю версию Qt с необходимыми компонентами для разработки C++.

### 3.2 Скачивание программы

- Перейдите в репозиторий проекта: Image Info Extractor.
- Скачайте файлы mainwindow.cpp и mainwindow.h или клонируйте репозиторий:
  
```bash
git clone https://github.com/yourusername/imageinfoextractor.git
```

### 3.3 Компиляция программы

- Откройте терминал или командную строку.
- Перейдите в директорию проекта:
  
```bash
cd путь/к/папке/imageinfoextractor
```

- Скомпилируйте проект с помощью qmake или CMake:
  
```bash
qmake
make
```

или

```bash
cmake .
make
```

### 3.4 Запуск программы

После успешной компиляции запустите приложение:

```bash
./ImageInfoExtractor
```

## 4. Использование приложения

### 4.1 Выбор папки

- Запустите приложение.
- Нажмите кнопку "Выбрать папку" для выбора директории с изображениями.
- В открывшемся диалоговом окне выберите нужную папку и нажмите **"OK"**.
  
### 4.2 Просмотр информации об изображениях

После выбора папки приложение автоматически загрузит изображения и отобразит следующую информацию в таблице:

1. Имя файла

2. Размер (пиксели)

3. Разрешение (dpi)

4. Глубина цвета

5. Тип сжатия

## 5. Пример использования

**Пример извлечения информации об изображениях**

- Запустите приложение.
- Нажмите кнопку "Выбрать папку" и выберите папку с изображениями.
- Просмотрите информацию об изображениях в таблице.
  
## 6. Обратная связь

Для вопросов и сообщений о багах: пишите скорее на почту

## Приложения

### Приложение 1. Список реализованных операций

- Извлечение информации о размере изображений
- Извлечение разрешения (dpi)
- Извлечение глубины цвета
- Определение типа сжатия изображений
  
## Лицензия
Данное приложение распространяется на условиях лицензии MIT. Подробнее смотрите файл LICENSE в репозитории. (если файл отсутствует - пользуйтесь случаем)

## Дополнительные материалы

- Репозиторий проекта: grcombinator/PKGLab2
- Обновления документации: Документация обновляется при внесении изменений в приложение. Рекомендуется регулярно проверять актуальность документации в репозитории проекта.