# LiftControl
Управление подъемной платформой тестовое задание
«Управление подъемной платформой»
Реализовать программу управления подъемной платформой в среде Tia Portal  на языке SCL. 
   Для контроля зоны перемещения подъемной платформы установлено несколько параллельно включенных датчиков (напр., ультразвуковых).
Подъемная платформа с помощью кнопок может перемещаться вверх или вниз. Для этого ко входу I1 подключена кнопка «Вверх», 
а ко входу I3 – кнопка «Вниз». Соответствующее конечное положение распознается концевым выключателем. 
Концевой выключатель на входе I2 – для верхнего положения платформы, концевой выключатель 
на входе I4 – для нижнего положения. Если конечное положение достигнуто, то двигаться можно 
только в противоположном направлении. Направление перемещения задается через
кнопки на I1 и I3. С помощью кнопки «Стоп» на I7 платформу можно остановить.
   Ультразвуковые датчики для контроля зоны перемещения платформы подключены к I5. Если датчиками распознается препятствие, 
то платформа останавливается, но ее можно перемещать в ручном режиме, если клавиша направления нажата дольше 2 секунд. 
   Однако, если нажата кнопка аварийного останова на I7, то платформа останавливается немедленно и не может больше перемещаться 
с помощью кнопок направления, пока не отпущена кнопка аварийного останова. 
   Для лучшего распознавания того, что платформа движется, 
активизируется предупредительное сигнальное устройство на Q3. Если платформа движется вверх или вниз, то мигает предупредительный световой сигнал на Q3.
Используемые компоненты:
I1 – кнопка «Вверх» (замыкающий контакт);
I2 – верхний конечный выключатель (замыкающий контакт); 
I3 – кнопка «Вниз» (замыкающий контакт);
I4 – нижний конечный выключатель (замыкающий контакт); 
I5 – датчики (размыкающие контакты);
I6 – кнопка «Стоп» (замыкающий контакт);
I7 – кнопка аварийного останова (замыкающий контакт); 
Q1 – платформа вверх;
Q2 – платформа вниз;
Q3 – предупреждающий световой сигнал.


