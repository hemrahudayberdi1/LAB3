# Пользовательская документация

## 1. Введение

Приложение "Обработка изображений" разработано для выполнения операций над изображениями, таких как контрастирование, эквализация гистограммы, пороговая обработка, морфологические операции, а также для выполнения задач сегментации, таких как обнаружение линий и точек. 

Приложение предоставляет удобный интерфейс для загрузки изображений и применения различных алгоритмов обработки.

## 2. Системные требования

- **Операционная система:** Windows 7 и выше, macOS, Linux
- **Программное обеспечение:** Современный веб-браузер (Chrome, Firefox, Edge)
- **Библиотеки:** OpenCV.js (загружается автоматически)
- **Аппаратные требования:**
  - Минимум 2 ГБ ОЗУ
  - 500 МБ свободного места на диске

## 3. Установка и запуск

1. Скачайте архив с приложением или клонируйте репозиторий проекта:
   git clone https://github.com/hemrahudayberdi1/LAB3
2. Разархивируйте файлы приложения, если скачали архив.
3. Откройте файл `LAB3` в любом современном веб-браузере.
4. Приложение готово к работе.

## 4. Использование приложения

### 4.1 Загрузка изображения

1. Нажмите кнопку "Выбрать файл" на главной странице.
2. Выберите изображение с устройства.
3. Изображение отобразится на холсте.

### 4.2 Применение алгоритмов

На панели управления доступны следующие функции:

#### Основные операции
- **Линейное контрастирование:** Увеличивает контраст изображения.
- **Эквализация гистограммы:** Улучшает детализацию изображения, равномерно распределяя интенсивность.
- **Глобальная пороговая обработка:** Применяет фиксированный порог для выделения объектов.
- **Адаптивная пороговая обработка:** Автоматически определяет порог для каждого участка изображения.

#### Морфологические операции
- **Морфологическая обработка:** Применяет градиент для выделения краев объектов.

#### Сегментация
- **Обнаружение линий (Хафф):** Выделяет прямые линии с использованием преобразования Хаффа.
- **Обнаружение точек (Лаплас):** Находит ключевые точки на изображении с помощью оператора Лапласа.

### 4.3 Регулировка контраста и яркости

1. Используйте ползунок "Контраст", чтобы настроить коэффициент контрастирования.
2. Используйте ползунок "Яркость", чтобы увеличить или уменьшить яркость изображения.

### 4.4 Очистка и повторное использование

- Нажмите "Очистить", чтобы сбросить изображение и удалить все изменения.
- Для работы с новым изображением загрузите файл заново.

## 5. Пример использования

### Пример 1. Обработка изображения с низким контрастом
1. Загрузите изображение.
2. Примените эквализацию гистограммы.
3. Отрегулируйте яркость для улучшения видимости деталей.

### Пример 2. Сегментация прямых линий
1. Загрузите изображение с изображенными линиями.
2. Нажмите "Обнаружение линий (Хафф)".
3. Результат отобразится с выделенными линиями.

## 6. Обратная связь

Для вопросов и предложений:  
- Email: hemrahudayberdiyev4@gmail.com  


# Приложения

## Приложение 1. Функциональность приложения

1. Линейное контрастирование
2. Эквализация гистограммы
3. Глобальная пороговая обработка
4. Адаптивная пороговая обработка
5. Морфологическая обработка
6. Обнаружение линий (Хафф)
7. Обнаружение точек (Лаплас)

## Приложение 2. Технические детали

### Используемые технологии:
- HTML, CSS, JavaScript
- OpenCV.js для обработки изображений
- Canvas API для отображения результатов

## Лицензия

Приложение распространяется на условиях лицензии MIT. Для получения подробной информации ознакомьтесь с файлом LICENSE в репозитории.

## Обновления документации

Документация обновляется с каждым релизом. Последняя версия доступна в репозитории проекта.