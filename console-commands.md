# Команды консоли для выполнения задания

mkdir git-practice-task
cd git-practice-task
git init
git config user.name "Матвей"
git config user.email "goatyy@vk.com"
echo "Это мой первый файл в Git репозитории" > first-file.txt
git add first-file.txt
git commit -m "Добавлен первый файл с описанием проекта"
git remote add origin https://github.com/rogancon/git-practice-task.git
git branch -M main
git push -u origin main
git checkout -b feature/add-second-file
echo "Это второй файл, созданный в отдельной ветке" > second-file.txt
git add .
git commit -m "Добавлены второй файл и команды консоли"
git push -u origin feature/add-second-file
