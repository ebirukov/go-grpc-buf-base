# Базовый каркас для генерации grpc сервисов

Для сборки нужно [установить](https://taskfile.dev/installation/) утилиту [task](https://github.com/go-task/task)

Либо просто в корне проекта:

```shell
go install github.com/go-task/task/v3/cmd/task@latest
```

Для генерации использует проект [buf](https://github.com/bufbuild/buf)

Сборочный [taskfile](Taskfile.yaml) локально (для обхода блокировки доступа к https://buf.build/ из россии)  
 устанавливает через go install бинарник buf и protoc генераторы 
