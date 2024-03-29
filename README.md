# Курс лекций "Архитектура и ПО высокопроизводительных систем"

Создан декабрь 2018.

Прочитан для магистров первого и второго года механико-математического факультета филиала МГУ им. М.В. Ломоносова в городе Ташкенте.

* осень/2018
* осень/2020

Кафедра МаТИС.

[Использованная литература](https://github.com/favorart/arch_course/blob/main/bibliography.md)

[Задачи для самостоятельной работы](https://github.com/favorart/arch_course/blob/main/exercises.md)

[Вопросы для проведения аттестации](https://github.com/favorart/arch_course/blob/main/questions.md)

[Список воспроизведения с лекциями](https://www.youtube.com/playlist?list=PL75Bl18xnIiEsjMlWD4a2Wi-nKyoAOOOE)


## Лекция 1. Ограничения роста производительности процессоров
Содержание:
* Производительность процессора
* Ограничения роста тактовой частоты процессоров
* Системы на кристалле
* Методы снижения потребления питания
* Адиабатические элементы
* Обратимые вычисления
* Синхронная и асинхронная логики
* Само-синхронные схемы
* Специальные радиационно-стойкие элементы

Видео-лекция:
[![Watch the video](https://img.youtube.com/vi/B4Utcw965xk/maxresdefault.jpg)](https://youtu.be/B4Utcw965xk)

[Лекция 1. Ограничения роста производительности процессоров.pdf](https://github.com/favorart/arch_course/files/13999312/Lektsia_-_Ogranichenia_rosta_proizvodietlnosti_protsessora.pdf)


## Лекция 2. Архитектура процессора
Содержание:
* AIR - Architecture Implementation Realization
* Гарвардская и Стэндфордская Архитектуры
* Классификация процессоров: доспуп, шины, суперскалярность…
* Характеристики производительности процессоров
* CISC
* RISC
* VLIW & EPIC

Видео-лекция:
[![Watch the video](https://img.youtube.com/vi/ZkJMn5R6AYI/maxresdefault.jpg)](https://youtu.be/ZkJMn5R6AYI)

[Лекция 2. Архитектура процессора.pdf](https://github.com/favorart/arch_course/files/13999314/Lektsia_-_Arkhitektura_protsessora.pdf)


## Лекция 3. Архитектура процессора x86_64
Содержание:
* Архитектура высокопроизводительной системы, главные компоненты
* Архитектуры x86: P6, NetBurst, Core
* Регистры процессора
* Прерывания процессора
* Конвейер в процессоре:
* предсказание переходов, спекулятивное исполнение, суперскалярность
* Множитель тактовой частоты процессора
* Режимы работы процессора: реальный и защищённый
* Начальная загрузка процессора

Видео-лекция:
[![Watch the video](https://img.youtube.com/vi/PMzj0Hpt6Yg/maxresdefault.jpg)](https://youtu.be/PMzj0Hpt6Yg)

[Лекция 3. Архитектура процессора x86_64.pdf](https://github.com/favorart/arch_course/files/13999322/Lektsia_-_Arkhitektura_protsessora_x86.pdf)


## Лекция 4. Кэш процессора
Содержание:
* Кэш память в процессоре
* Fully associative mapping cache
* Direct mapped cache
* Set associative mapping cache
* Полное время передачи данных в процессор
* Алгоритмы вытеснения
* Производительность кэш памяти
* Многоуровневая кэш память: согласованность – когерентность
* Трансляция адресов кэш памяти
* Micro-operations cache

Видео-лекция:
[![Watch the video](https://img.youtube.com/vi/tByW4BmPHg4/maxresdefault.jpg)](https://youtu.be/tByW4BmPHg4)

[Лекция 4. Кэш процессора.pdf](https://github.com/favorart/arch_course/files/13999324/Lektsia_-_Kesh_protsessora.pdf)


## Лекция 5. Виртуальная память
Содержание:
* Определения
* Иерархия памяти, типы памяти, локальность, трансляция
* Сегментная адресация
* Страничная адресация
* Сегментно-страничная адресация. Виртуальная память

Видео-лекция:
[![Watch the video](https://img.youtube.com/vi/wwcx7ZmBklU/maxresdefault.jpg)](https://youtu.be/wwcx7ZmBklU)

[Лекция 5. Виртуальная память.pdf](https://github.com/favorart/arch_course/files/13999323/Lektsia_-_Virtualnaya_pamyat.pdf)


## Лекция 6. Вызов процедуры
Содержание:
* Память программы на Си/C++
* Работа стэка
* Соглашение о вызовах (calling conventions)
* Системные вызовы
* Бинарный интерфейс приложений (ABI)
* Формат ELF (Executable and Linkable Format)
* Переключение режимов работы процессора (asm)

Видео-лекция:
[![Watch the video](https://img.youtube.com/vi/JAus_CWanR4/maxresdefault.jpg)](https://youtu.be/JAus_CWanR4)

[Лекция 6. Вызов процедуры.pdf](https://github.com/favorart/arch_course/files/13999328/Lektsia_-_Vyzov_protsedury.pdf)


## Лекция 7. Обработка прерываний
Содержание:
* Прерывание: fault, trap, abort
* Аппаратные прерывания: Programmable Interrupt Controller, каскадирование, IVT
* Системные вызовы: исключения, обработчики прерывания, gate
* IDT: регистры, селекторы и дескрипторы
* Стэки прерываний
* Таймеры

Видео-лекция:
[![Watch the video](https://img.youtube.com/vi/_fGrsJmt2u0/maxresdefault.jpg)](https://youtu.be/_fGrsJmt2u0)

[Лекция 7. Обработка прерываний.pdf](https://github.com/favorart/arch_course/files/13999355/Lektsia_-_Obrabotka_preryvaniy.pdf)


## Лекция 8. Операционная система
Содержание:
* Понятие Операционной системы
* Ресурсы
* Многозадачность
* Ядро ОС

Классические задачи синхронизации

* Проблема Санта-Клауса
* Курильщики сигарет
* Спящий парикмахер
* Обедающие философы
* Читатели-писатели
* Производитель-потребитель

Видео-лекция:
[![Watch the video](https://img.youtube.com/vi/Aj5bWIvi5iA/maxresdefault.jpg)](https://youtu.be/Aj5bWIvi5iA)

[Лекция 8. Операционная система.pdf](https://github.com/favorart/arch_course/files/13999357/Lektsia_-_Operatsionnaya_sistema.pdf)


## Лекция 9. Высокопроизводительные системы
Содержание:
* Надёжность
* Типичные архитектуры из обычных дешёвых серверов
* Нагрузка
 *Трудности
* Балансировка

Видео-лекция:
[![Watch the video](https://img.youtube.com/vi/weA3_gPXXbw/maxresdefault.jpg)](https://youtu.be/weA3_gPXXbw)

[Лекция 9. Высокопроизводительные системы.pdf](https://github.com/favorart/arch_course/files/13999362/Lektsia_-_Highload.pdf)


## Лекция 10. Введение в обработку больших данных
Содержание
* История
* Горизонтальное и вертикальное масштабирование
* Облака для вычислений
* Возможности обработки возросших объёмов данных
* Big Data
* Map-Reduce
* Distributed File System (DFS)
* СУБД: RDBMS & noSQL (HBase & Cassandra)
* Map-Reduce BFS: поиск кратчайшего пути

[Аудио с лекции](https://github.com/favorart/arch_course/blob/main/data/10.hadoop-2018.mp3)

[Лекция 10. Введение в обработку больших данных.pdf](https://github.com/favorart/arch_course/files/13999377/Lektsia_-_Vvedenie_v_MapReduce.pdf)

