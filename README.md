<h1 style="text-align:center">mml-7</h1>
<h2>Классификация текстов с использованием Наивного Байесовского Классификатора</h2>
Учебный проект.<br/>
Задача: реализация классификации спам-сообщений.<br/>
Проект включает пять заданий.<br/>
<h3>Первое задание</h3>
Прочитать данные, провести первичное знакомство с данныи.
<h3>Второе задание</h3>
Предобработка данных и перевод их в векторный вид. В ходе работы все символы, относящиеся к пробельным, были заменены пробелами, удалены пробелы из начала и конца строки, а также строки, оказавшиеся пустыми или состоящими из одних пробелов, были заменены на пустые. Все строки, имеющие пропущенные значения, были удалены. После этого данные были приведены к векторному виду.
<h3>Третье задание</h3>
Были определены необходимые признаки и целевая переменная. Произведено деление на тренировочную и тестовую выбрки.
<h3>Четвертое задание</h3>
Для обучения модели подходят следующие две вариации наивного байесовского классификатора: MultinomialNB и ComplementNB. Как и ожидалось, чуть лучшие результаты показал ComplementNB. Он и был использован для обучения модели.
<h3>Пятое задание</h3>
Было изучено влияние параметра &alpha; на качество модели. Результат зависел от использоанной метрики, но в целом можно говорить о достаточно слабом влиянии параметра на качество модели.
<h3>Вывод</h3>
Все задачи были решены, построенная модель показала высокий уроень качества классификации электронной почты.
