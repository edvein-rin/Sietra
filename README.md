# Sietra
				Документация
Общее:
    Номера типов объектов:
		1.Персонажи и союзники:
			1_1.Воин
				1_1_1.Атака мечём
		2.Враги:
			2_1.Собака
				2_1_1.Атака лапой
		3.Преграды:
			3.Трава
			3_1.Камень
			3_2.Голубая трава(Поле старта)
			3_3.Красная трава(Поле с врагом)
	Обозначения типов таймера:
		"start"- таймер первого хода за игру(выставление персонажей на поле)
		"player"- таймер хода персонажа
		"enemy"- таймер хода врага
	Типы остановления таймера:
		0.Стандартный
		1.Остановка таймера "start"
		2.Остановка таймера "player"
		3.Остановка таймера "enemy"
	Типы проверки блоков:
		"block" - проверка на блок
		"player" - проверка на игрока
		"enemy" - проверка на врага
P.S. Передавать все данные в виде строки,кроме обыкновенных цифер
