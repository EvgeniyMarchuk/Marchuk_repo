Чтобы создать ключ: ssh-keygen -t ed25519 -C "имя.фамилия@phystech.edu"

Чтобы добавить ключ в ssh-агента: eval "$(ssh-agent -s)"

Добавить ключ в ssh-агента: ssh-add ~/.ssh/id_ed25519

Узнать ключ: cat ~/.ssh/id_ed25519.pub

Проверка, что ключ успешно установлен на гитхабе: ssh -T git@github.com

