# task
mkdir dev # создаст папку dev в текущем каталоге 
touch hello-world.txt # создаст файл hello-world.txt в текущей папке 
cat output.txt посмотреть содержимое файла 
git init - бычная папка превратится в репозиторий
Текущее состояние репозитория можно посмотреть с помощью команды git status
git branch — просматриваем ветки проекта
git branch <название_ветки>: создаём ветку
- чтобы создать ветку, нужно вызвать команду git branch <название_ветки>
- чтобы переключиться на ветку, нужна команда git checkout <название_ветки>
Перед тем как начать слияние, нужно перейти в ветку, куда должны добавиться изменения. Обычно это главная ветка. Перейдите в неё и вызовите команду git merge с именем присоединяемой ветки new_branch в качестве параметра.
