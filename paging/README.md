# Frame Swapping Algorithms

Программа работает в операционной системе, которая осуществляет замещение кадров
основной памяти страницами во вторичной памяти. При обращении к странице, которая отсутствует
в основной памяти, происходит замещение страницы по заданному алгоритму.
Количество кадров в основной памяти, выделенных программе, равно 6.
Кадры в основной памяти в начале работы программы не инициализированны.
Количество страниц в виртуальной памяти процесса равно 20.
Программа осуществляет обращения к страницам в следующем порядке:
[17, 12, 9, 14, 8, 5, 1, 19, 17, 16, 15, 5, 9, 18, 9, 4, 5, 4, 9, 12, 15, 5, 9, 14, 10, 
6, 13, 1, 7, 12, 16, 12, 13, 19, 10, 16, 13, 16, 1, 19, 10, 9, 7, 19, 7, 4, 17, 9, 2]
Рассмотреть стратегии замещения - Оптимальную, LRU, FIFO (Столлингс, гл.8.2). Для каждого алгоритма:
- нарисовать состояние кадров основной памяти во время обращения программы;
- определить количество операций по замене страниц;
- сравнить количество замен по сравнению с оптимальным.
Как изменится количество замен страниц, если увеличить количество кадров в 2 раза?
А если уменьшить количество кадров в 2 раза?
Сколько должно кадров в памяти, чтобы оптимальный алгоритм давал 5% страничных сбоев?