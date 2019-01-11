# Базовые структуры
## Связный список
### Изменение списка:
- добавить элемент по индексу add_at(index, value)
- добавить в конец append (value)
- удалить элемент remove_at(index)
- забрать элемент pop()

### Поиск по списку:
- первое вхождение search_first(value)
- все вхождения search_all(value) возвращает массив индексов

### Получение данных:
- значение элемента по индексу element_at(index)
- получение всего списка в виде массива as_array()

## Стек
Использует для хранения данных связный список
- добавить элемент push(value)
- забрать элемент pop()
- получить последний элемент peek()

## Очередь
Использует для хранения данных связный список 
- добавить элемент в очередь enqueue(value)
- добавить элемент в начало очереди enqueue_first(value)
- забрать элемент из очередь dequeue()
- забрать элемент с конца очереди dequeue_last()
- получить последний элемент peek()

## Приоритетная очередь
Использует для хранения данных связный список 
- добавить элемент в очередь в конец группы по приоритету enqueue(value, priority)
- добавить элемент в очереди в начало группы по приоритету enqueue_first(value, priority)
- забрать элемент из очередь dequeue()
- забрать элемент с конца очереди dequeue_last()
- получить последний элемент peek()
