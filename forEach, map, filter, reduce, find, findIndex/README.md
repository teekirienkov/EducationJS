<h1>Важно</h1>
<h2> Чем map отличается от forEach </h2>

1) map выделяет память и сохраняет значение return. <br>
forEach выбрасывает значение return и всегда возвращает undefined. <br>

2) К map можно привязывать другие методы, .map().reduce() и т.д. <br>
forEach не позволяет этого

<h4>Вывод</h4>
Выбор между map() и forEach() будет зависеть от варианта использования. <br>
Если вы планируете изменять, чередовать или использовать данные, лучше выбирать map(), <br>
поскольку он возвращает новый массив с преобразованными данными. <br>
Но, если вам не понадобится возвращаемый массив, не используйте map(), 
вместо этого используйте forEach() или даже цикл for.
