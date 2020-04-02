# Получение всех тегов
Метод: `GET`

URL: `/api/tags/get`

## Возвращаемый JSON:
| Параметр | Описание |
| ------------ | ------------ |
| status | Статус (`ok`) |
| tags | Массив [объектов тегов](/{{route}}/{{version}}/objects/tag "Объект тега") |
| count | Количество тегов в массиве |