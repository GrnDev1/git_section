# git pull origin master
- Скачивает (1) удаленную ветку с удаленного репозитория (обновляет ветку origin/master)
- Сливает (2) удаленную ветку с локальной веткой (производит актуализацию вашей локальной ветки)
- То же самое для любой другой ветки (git pull origin название_ветки)

## Порядок действий
- Команда git fetch "скачивает" (1) удаленные ветки с репозитория, но не производит актуализацию ваших локальных веток (не делает слияния удаленной ветки с локальной)
- Как и обычно, слияние (2) может быть fast-forward или не fast-forward