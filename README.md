# go-grpc-buf-base - базовый каркас для генерации grpc сервисов

Для сборки нужно [установить](https://taskfile.dev/installation/) утилиту [task](https://github.com/go-task/task)

Для генерации использует проект [buf](https://github.com/bufbuild/buf)

Сборочный [taskfile](Taskfile.yaml) устанавливает через go install бинарник buf и protoc генераторы локально (для обхода блокировки доступа к https://buf.build/ из россии)  
