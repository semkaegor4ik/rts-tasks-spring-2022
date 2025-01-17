# Task 1

Измерение осциллографом было проведено на платах ***Arduino Uno*** и ***Arduino M0***

--------------------------------------------------------------------------

Результаты измерений на плате ***Arduino Uno***: 

* Пин 3 - 325 мс

* Пин 5 - 62 мс

* Пин 6 - 6200 мкс - данные осциллографа показали 6200 мкс, джиттер 500

* Пин 9 - 620 мкс - данные осциллографа показали 620 мкс, но линия расслаивается, дергается и имеется большой хвост, при удалении других элементов массива джиттер уменьшается до 20

* Пин 10 - 62 мкс - данные осциллографа показали 88 мкс, джиттер 8, при удалении всех остальных элементов массива 64 мксб джиттер 4

--------------------------------------------------------------------------

Результаты измерений на плате ***Arduino M0***: 

* Пин 3 - 325 мс

* Пин 5 - 62 мс

* Пин 6 - 6200 мкс

* Пин 9 - 620 мкс - данные осциллографа показали 620 мкс, джиттер 5

* Пин 10 - 62 мкс - данные осциллографа показали 62 мкс, джиттер 4

--------------------------------------------------------------------------

Исходя из результатов, которые были получены при замерах на платах ***Arduino Uno*** и ***Arduino M0***, можно сделать вывод, что при достаточно высоких частотах результаты при замере осциллографом несколько отличались от истинных частот. 

Поскольку замеры были произведены на платах различной мощности, по результатам исследования можно отметить, что осциллограф показывает более точные значения, если программа была запущена на более мощной плате. Из этого следует, что задание более высоких частот имеет смысл, если в наличие есть плата соответствующей мощности.