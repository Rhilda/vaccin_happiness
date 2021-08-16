# vaccin_happiness

Тестовое задание.

Хотим исследовать зависимость скорости вакцинации от рейтинга "счастья".

В данный момент в проекте есть: 
- Код загружающий csv в hive и создающий следующие таблицы (класс DataLoader) : 
    - happiness_2019
    - country_vaccinations
    - country_vaccinations_by_manufacturer
- Демонстрационная витрина total_vaccinations_by_manufacturer. В ней посчитано общее количество вакцинаций по производителям.

В рамках задания необходимо форкнуть репозиторий и разработать код, который объединит два рейтинга и построит следующие витрины:

- Процент вакцинированных в стране (people_fully_vaccinated_per_hundred) вместе с местом в рейтинге (Overall_rank), отсортировать по месту
- Процент вакцинированных в стране (people_fully_vaccinated_per_hundred) вместе с ВВП (GDP_per_capita), отсортировать по ВВП
- Процент вакцинированных в стране (people_fully_vaccinated_per_hundred) вместе с продолжительностью жизни, (Healthy_life_expectancy) отсортировать по продолжительности жизни
- Процент вакцинированных в стране (people_fully_vaccinated_per_hundred) вместе с Freedom_to_make_life_choices, отсортировать по Freedom_to_make_life_choices
- Процент вакцинированных в стране (people_fully_vaccinated_per_hundred) вместе с Perceptions_of_corruption, отсортировать по Perceptions_of_corruption

Так же в данных возможны ошибки, надо построить 2 витрины с ошибками объединения отчетов.
- Таблица со странами, по которым есть рейтинг счастья, но нет данных по вакцинации
- Таблица со странами, по которым есть данные по вакцинации, но нет рейтинга счастья.

