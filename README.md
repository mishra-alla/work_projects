## 1. Распознавание таблиц медицинских справок для DonorSearch / OCR for DonorSearch.
**Заказчик:** Сообщество доноров Крови "DonorSearch"
**Проект:** Распознавание таблиц медицинских справок для DonorSearch / OCR for DonorSearch.
**Цель:** Автоматизировать перенос данных с фотографий медицинских справок донора в формат .csv (NLP - задача).
**Задача:** Детектировать табличную часть справки, распознать текст и привести данные к требуемому шаблону.
**Стек:** Python, pandas , cv2, os, re, PIL, numpy, matplotlib, Docker
Работа была выполнена в команде.

## 2. Генератор упражнений по английскому языку - Read books in english ("Red Hat").
**Заказчик:** Школа английского языка Яндекс
**Цель:** Создание приложения, которое автоматически преобразовывает предоставленный текст в разнообразные задания по английскому языку, используя технологии обработки естественного языка (NLP).
На примере сказки Ш.Перро: "Красная шапочка"
**Задача:**
- Создать модель, преобразующее текст в набор упражнений по английскому языку.
Стек: pandas , os, re, spacy, gensim, nltk, pyinflect, sentence_splitter

## 3. Расчет стоимости жилья. 
**Цель:** Построить математическую модель стоимости жилья в зависимости от параметров этого жилья.
**Источник данных:** www.citystar.ru
**Задачи:**
1. Скачать данные с сайта (парсинг);
2. Предобработка и анализ данных, подготовка данных для обучения;
3. Непосредственно обучение (Линейная регрессия,Ridge; CatBoostRegressor, XGBRegressor) методами GridSearchCV и RandomizedSearchCV.
- выбор лучшей модели, тестирование.
4. Предсказываем цены квартиры с помощью нашей модели - проверка работы модели на конкретных данных.
