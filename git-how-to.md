    1)открыть терминал
    2)проверка на существующие ключи: ls ~/.ssh 
    3)генерация ключа: ssh-keygen -t ed25519(формат ключа) -C "khvoshninsky123@gmail.com(почта)"
    4)eval "$(ssh-agent -s)"
    5)ssh-add ~/.ssh/id_ed25519
    6)добавить ключ на сайт через настройки, ssh
    7)git clone (дальше ssh с github репозитория)
././123
проверить статус репозитория: git status
подготовить новый файл для комита: git add git-how-to.md
проверить статус репозитория: git status
сделать комит: git commit -m “initial commit”
отправить изменения на сервер: git push
