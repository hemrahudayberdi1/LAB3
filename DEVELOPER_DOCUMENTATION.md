### Документация разработчика

**Текст программы**  
**Наименование программы:**  
ImageProcessingTool — веб-приложение для обработки изображений.


### **Область применения**  
Программа предназначена для обработки загруженных изображений с целью применения различных алгоритмов, включая изменение контраста, яркости, пороговые преобразования, морфологическую обработку и обнаружение линий или точек. Приложение может быть использовано как вспомогательный инструмент в задачах обработки изображений.


### **Назначение программы**  
- Предоставление веб-интерфейса для загрузки изображений.  
- Применение различных методов обработки:  
  - Изменение яркости и контраста.  
  - Линейное контрастирование.  
  - Глобальное и адаптивное пороговые преобразования.  
  - Эквализация гистограммы.  
  - Морфологическая обработка.  
  - Обнаружение линий и точек.  
- Визуализация обработанного изображения.  



### **Функциональные возможности**
- Загрузка изображений (поддержка форматов: JPEG, PNG, BMP, GIF и других).  
- Применение линейного контрастирования.  
- Регулировка яркости и контраста с использованием слайдеров.  
- Эквализация гистограммы для выравнивания распределения яркости.  
- Глобальная и адаптивная пороговая обработка.  
- Обнаружение линий методом Хаффа.  
- Выделение точек с использованием оператора Лапласа.  
- Отображение результатов обработки на канвасе.


### **Описание программы**

#### **Структура программы**

1. **HTML-разметка**  
   - Поля для загрузки изображения.  
   - Кнопки управления обработкой.  
   - Канвас для отображения исходного и обработанного изображения.

2. **CSS**  
   - Стилизация интерфейса (канваса, кнопок, слайдеров).  
   - Расположение элементов для удобного взаимодействия.

3. **JavaScript**  
   - Загрузка изображений и их отображение.  
   - Реализация алгоритмов обработки с использованием OpenCV.js.  
   - Динамическое обновление канваса для визуализации результатов.  

#### **Используемые библиотеки и API**  
- **OpenCV.js** — библиотека для работы с изображениями.  
- **FileReader API** — для чтения данных из загруженных файлов.  


### **Логические структуры данных**

1. **HTML-элементы:**  
   - Поле загрузки файла (`<input type="file">`).  
   - Канвас для исходного и обработанного изображения.  
   - Кнопки для запуска обработки.  

2. **JavaScript:**  
   - Переменная `originalImage` для хранения исходного изображения.  
   - Временные переменные для хранения промежуточных результатов обработки.  


### **Взаимодействие с пользователем**

1. Пользователь загружает изображение через кнопку "Choose File".  
2. Программа отображает изображение на канвасе.  
3. Пользователь выбирает метод обработки и нажимает соответствующую кнопку.  
4. Результат обработки отображается на канвасе.  


### **Инструкция по установке и запуску**

#### **Требования к системе**  
- Современный веб-браузер (Chrome, Firefox, Edge).  
- Подключение к сети интернет для загрузки OpenCV.js.

#### **Установка**  
1. Сохраните HTML-код программы в файл с расширением `.html`.  
2. Убедитесь, что подключена библиотека OpenCV.js через CDN.  

#### **Запуск программы**  
1. Откройте файл `.html` в браузере.  
2. Загрузите изображение и примените выбранный метод обработки.


### **Инструкция пользователя**

1. Нажмите "Choose File" и выберите изображение для обработки.  
2. Используйте кнопки для выполнения операций, например:  
   - "Adjust Brightness/Contrast" — для изменения яркости и контраста.  
   - "Apply Histogram Equalization" — для эквализации гистограммы.  
   - "Detect Lines" — для нахождения линий.  
3. Результат появится на канвасе.  


### **Обработка ошибок**  
- Если изображение не загружено, отображается предупреждение.  
- Для неподдерживаемых форматов выводится сообщение об ошибке.  


### **Дополнительные сведения**

#### **Поддерживаемые форматы изображений**  
JPEG, PNG, BMP, GIF, WebP и другие.  

#### **Примечания к функциональности**  
- Обнаружение линий работает только с изображениями в оттенках серого.  
- Для больших изображений обработка может занять больше времени.

#### **Сопровождение и развитие**  
- Код оптимизирован для добавления новых методов обработки.  
- Возможно расширение функциональности, например, добавление фильтров или работы с видео.


### **Заключение**  
Данное приложение предоставляет удобный инструмент для базовой обработки изображений в веб-среде. Простота интерфейса и широкий спектр функций делают его подходящим для использования как разработчиками, так и конечными пользователями.