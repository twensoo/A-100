А-100 «Премьер» — российский самолёт дальнего радиолокационного обнаружения и управления. Самолёт может обнаруживать и сопровождать до 300 воздушных, морских и наземных целей, а также управлять беспилотниками. В качестве воздушного командного пункта А-100 обеспечивает устойчивую связь с различными группировками войск. Самолёт получает информацию не только со своего радара, но и от космических спутников. Многофункциональный авиационный комплекс радиолокационного дозора и наведения (МАК РЛДН).
Ранее поставки в ВВС России планировалось начать в 2016 году; самолёты начнут поступать в ВКС России в 2024 году

Данный инструмент производить быстрый поиск учетных записей и некоторых метаданных по имени пользователя



#### Установка

```shell
git clone https://github.com/twensoo/A-100.git
cd A-100
pip install -r requirements.txt
```

#### Для запуска поиска

```shell
python3 a100.py -u {username}
python a100.py -u {username}
```

#### Результаты поиска сохраняются в папку result в json файл
#### Для вывода результатов
```shell
python3 a100.py -f username.json
python a100.py -f username.json
```

#### Параметры программы
| **Опция**    | **Значение** | **Выполнение**                 |
| :--------    |:------------ | :----------------------------- |
| -u           | username     | Имя пользователя               |
| --list-sites | list         | Список всех сайтов             |
| -f           | file         | Чтение файла результатов       |
| --proxy      | proxy        | Прокси для отправки запросов   |
| --show-all   | showAll      | Показать все результаты        |
| --csv        | csv          | Экспорт результатов в файл CSV |

