# Банки — Сегментация пользователей по потреблению

## Описание проекта
Мы работаем в региональном банке "Метанпром". Необходимо проанализировать клиентов регионального банка и сегментировать пользователей по количеству потребляемых продуктов, обращая особое внимание на отток.

### Описание данных
Путь к файлу: https://code.s3.yandex.net/datasets/bank_scrooge.csv

Датасет содержит данные о клиентах банка «Метанпром». Банк располагается в
Ярославле и областных городах: Ростов Великий и Рыбинск.

Колонки:

- USERID — идентификатор пользователя,
- score — баллы кредитного скоринга,
- city — город,
- gender — пол,
- age — возраст,
- equity — количество баллов собственности
- balance — баланс на счёте,
- products — количество продуктов, которыми пользуется клиент,
- credit_card — есть ли кредитная карта,
- last_activity — активный клиент,
- EST_SALARY — оценочный доход клиента,
- сhurn — признак оттока.

По итогам исследования подготовьте презентацию. Для создания презентации
используйте любой удобный инструмент, но отправить презентацию
нужно обязательно в формате pdf.

### Декомпозиция (Шаги по выполению проекта)

#### Откроем файл и изучим общую информацию
- откроем файл и сохраним в переменную
- изучим общую информацию датафрейма

#### Проведём предобработку данных
- проверим природу пропусков в данных если таковы имеются
- приведём наименование столбцов к единому "змеиному" стилю
- проверим наш датафрейм на наличие явных и неявных дубликатов. При их наличии посмотрим, что это за дубликаты и решим удалять их или же оставить
- изменим тип данных в столбцах при необходимости
- сделаем кодирование признаков

#### Исследовательский анализ данных
- исследование распределений признаков
- исследование распределений признаков в разрезе оттока клиентов банка
- корреляционный анализ

#### Проверка гипотез
- сформулируем статистические гипотезы
- выберем и обоснуем статистические критерии
- проверим гипотезы и интерпретируем результаты
    
#### Промежуточный итог
Написание промежуточных итогов по изучению исследовательского анализа и проверки гипотез

#### Сегментация на основе выделенных показателей
- сегментируем клиентов банка на основе исследовательского анализа данных
- рассчитаем для каждого сегмента:
    - размер сегмента
    - долю оттока
    - описательные характеристики клиентов

#### Выводы и рекомендации
- предоставим выводы и рекомендации в формате презентации

## Материалы:
Презентация: https://disk.yandex.ru/i/cS3293bSaw_FSQ
