# Поиск пользователей
Метод: `GET`

URL: `/api/users/search`
## Входящие параметры:
| Параметр | Описание |
| ------------ | ------------ |
| user | ID пользователя ВКонтакте |
| from_age | Возраст "от" |
| to_age | Возраст "до" (не больше возраста "от") |
| distance | Максимальное расстояние до пользователя (в км) |
| sex | Пол пользователя <br><br> Значения: <br> 0 - Иннопланетянин <br> 1 - Мужчина <br> 2 - Женщина |

## Возвращаемый JSON:
| Параметр | Описание |
| ------------ | ------------ |
| status | Статус (`ok`, `error`) |
| users | Массив [объектов пользователей](/{{route}}/{{version}}/objects/user "Объект пользователя") |
| count | Количество пользователей в массиве |
