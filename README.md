1. Создаешь репозиторий с файлом README на github
2. Добавляешь Кислова в collaborators(пока по желанию, как я понял)
2. Копируешь ссылку на репозиторий
3. Заходишь в гит
4. Пишешь git clone <ссылку на репозиторий>
5. Заходишь в появившуюся папку в гите (по идее, через команду cd <название папки/название репа, что одно и то же)
6. Добавляешь файл .gitignore, его можно найти в интернете
7. Как создать sln и project я скипку, это в презе есть, соответственно его создаешь
8. Редактируешь файл README, добавляя туда коспект
9. В гит пишешь git add .
10. git commit -m "Добавлено обновление"
11. git push
--------------------------------
Это основная часть по созданию красивого репа, дальше

Идем дальше
На этом моменте лучше проверь github, там все должно выглядеть так, как у тебя в папке. Если все выглядит так же, то продолжаем

0. На всякий пожарный пропиши в гите git pull (Если он написал сообщение что-то типа "все и так заебись", то все хорошо)
1. Создаешься отдельную ветку при помощи команды git checkout -b task1 - ветка с названием task1
2. Заходишь в папку, меняешь КАКУЮ-ТО ОПРЕДЕЛЕННУЮ СТРОЧКУ в папке (галвное не забудь, иначе будешь ебланкой, как мы с Ромой)
3. Пишешь git add .
4. Пишешь git commit -m "Добавлено изменение и тд"
5.Пишешь git push -u origin task1
6.ПОСЛЕ ЭТОГО (тут главное не проебать момент) заходишь на гитхаб, у тебя там красивая табличка типа compare pull request или че-то такое, ты нажимаешь ее, потом еще одну зеленую и еще одну, пока у тебя не загорится фиолетовым
7. ЕСЛИ ЗАГОРЕЛОСЬ, а оно должно, то создаешь новую ветку в гите при помощи git checkou -b mk
8. Заходишь в папку, меняешь ТУ ЖЕ СТРОЧКУ, которую сменила до еще раз (проще всего первую строчку поменять на условные "123" в пункте 2, а сейчам "123" поменять на условные "321")
9. Пишешь git add .
10. Пишешь git commit -m "Добавлено обновление и тд"
11. Пишешь git push -u origin mk
12. Заходишь на гитхаб, видишь то же, что и в пункте 6, поаторяешь пункт 6, НО, вместо фиолетовой таблички у тебя вылезет Merge Conflict