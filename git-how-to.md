    1)открыть терминал
    2)проверка на существующие ключи: ls ~/.ssh 
    3)генерация ключа: ssh-keygen -t ed25519(формат ключа) -C "khvoshniasnkii.ra@phystech.edu(почта)"
    4)eval "$(ssh-agent -s)"
    5)ssh-add ~/.ssh/id_ed25519
    6)добавить ключ на сайт через настройки, ssh
    7)git clone (дальше ssh с github репозитория)
