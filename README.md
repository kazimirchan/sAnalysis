# sAnalysis
----- Женино быдлокодище -----
- текущая (тестовая) версия синт и семант анализатора хранятся в ветке test;
- каждый создает отдельную ветку от ветки test под свою задачу и НИ В КОЕМ СЛУЧАЕ НЕ КОММИТИТ в test и master;
- закоментите строку 65 в main.java и прога будет работать так как вам надо;
- используется IDE IntelliJ IDEA;

Обязательно к изучению:
- main.java - здесь мы парсим файл, который на вход подала Юля. Затем создаем синтаксическое дерево, наполянем его данными. Если синтаксический и семантический анализы удались, то производим оптимизацию и генерацию кода;
- tree.java - Андрюшенькино дерево. Модернизировано мной для большего удобства. Честно, это даже на дерево не похоже (но создавать другое дерево лень). И как по нему идти я мало преставляю. Это просто цепочка данных, которая нигде не разветвляется.

-----На заметку-----

Генерация и Оптимизация кода могут писаться параллельно. Для них на вход подается дерево.
Сергей изменяет дерево (можно перезаписать и тд и тп), а Саша - печатает дерево (не важно какое: мое или Сережи) в виде красивого кода в выходном файле.
