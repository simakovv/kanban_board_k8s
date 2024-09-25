Установка:
git clone https://github.com/simakovv/kanban_board_k8s
cd kanban_board_k8s
kubectl apply -f ./

Удаление:
kubectl delete -f ./

Проверка:
http://nodeIP:30020/

Описание:
Репозиторий содержит манифесты для запуска kanban_board в k8s кластере.
Сервис состоит из БД (postgres), backend (Node.js) и frontend (ngnix).