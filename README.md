УКРАЇНСЬКИЙ КАТОЛИЦЬКИЙ УНІВЕРСИТЕТ
ФАКУЛЬТЕТ ПРИКЛАДНИХ НАУК
Комп’ютерні науки / ІТ та Бізнес-Аналітика
  
 
Задача 2-SAT
 
                                    	          	 	Автори:
                                                             	Шевченко Іван
                                                             	Богун Максим
                                                             	Московець Артем
                                                             	Козловський Андреа
                                                             	Васильків Дмитро 
13 Грудня 2021


1.   Вступ.
Реалізація проєкту проходила у декілька етапів.
Спочатку, потрібно було розв’язати задачу 2-SAT. Завдяки виключним знанням Івана, із цим етап ми справились за декілька годин. Нам дуже пригодились знання логіки предикатів та теорії графів. 
Опісля, розв’язок задачі потрібно було запрограмувати. Завдяки плідній співпраці та рівномірному розподілу завдань, із цим завданням ми впорались за два вечори.
Третій і останній етап реалізації проєкту - робота над презентацією. Завдяки викоруванню анімаційного рушію “Manim”, розробленого американським професором Грантом Сандерсоном,  команді вдалось розробити анімацію, що влучно та просто демонструє роботу розробленого алгоритму.
 
 
 
 
1.   Псевдокод.
Алгоритм роботи коду : 
Зчитування файлу  =>  запис даних => запис тверджень з допомогою створених методів => створення графа імплікацій з допомогою створених методів => (5)виконання depth-first search, розбиття на компоненти зв’язності => виведення розмальовування графу в txt-файл або повернення повідомлення про помилку, якщо в одній компоненті зв’язності є взаємовиключні твердження .
Приведемо псевдокод для  частини програми 5 :
time=0
If timeout of current node is None :
	Add -1 as current node timeout 
	Append current node to stack
If last stack item == current node :
	current node timeout =time
	time+=1
		delete last stack item

 
 



2.   Висновки.
Отже, наша команда виконала розв’язок проблеми 2-SAT. Під час виконання цього проекту, ми поглибили свої знання з дискретної математики, а саме познайомилися із алгоритмом побудови графа імплікації та розділом графа на компоненти сильної зв’язності за допомогою пошуку вглиб(DFS). Також ми набралися досвіду роботи в команді та ефективній колаборації, ми використовували онлайн-ресурс Miro, для дистанційної роботи над алгоритмом вирішення проблеми. Ще ми познайомилися із анімаційним рушієм “Manim” для створення візуалізації коду. Ми надіємось, що всі набуті знання пригодяться нам для подальшого навчання.

 
 
 

