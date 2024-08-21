## Анализ граничных значений
По данным из задания минимальный возраст оформления паспорта 0 лет, 115 лет максимальный возраст. На основе этих данных можно провести анализ нижней и верхней границы:

*Анализ по нижней границе*:

| Значение      | Ожидаемый результат |
| ------------- | ------------- |
| -1            | значение не принято, ответ: ошибка |
| 0             | значение принято, ответ: нельзя оформить |
| 1             | значение принято, ответ: нельзя оформить |

*Анализ по верхней границе*:
| Значение      | Ожидаемый результат |
| ------------- | ------------- |
| 114           |  значение принято, ответ: нельзя оформить|
| 115           | значение принято, ответ: нельзя оформить |
| 116           | значение не принято, ответ: ошибка |

Так же получение и замена паспорта имеет возрастные границы по законодательству РФ:
получение паспорта в 14 лет, первая замена паспорта  от 20 лет до 45 лет, вторая заменя паспорта в 45 лет - бессрочно.

*Получение паспорта в 14 лет*:
| Значение      | Ожидаемый результат |
| ------------- | ------------- |
| 13            | значение принято, ответ: нельзя оформить |
| 14            | значение принято, ответ: можно оформить |
| 15            | значение принято, ответ: можно оформить |

*Замена паспорта в 20 лет*:
| Значение      | Ожидаемый результат |
| ------------- | ------------- |
| 19            | значение принято, ответ: нельзя оформить |
| 20            | значение принято, ответ: можно оформить |
| 21            | значение принято, ответ: можно оформить |

*Замена паспорта в 45 лет*:
| Значение      | Ожидаемый результат |
| ------------- | ------------- |
| 44           | значение принято, ответ: нельзя оформить |
| 45           | значение принято, ответ: можно оформить |
| 46           | значение принято, ответ: можно оформить |

## Разбиение данных по классам эквивалентности:

*Возраст от 0 до 14 лет (значения от 0 до 13 включительно)*
| Входное знаяение      | Ожидаемый результат |
| ------------- | ------------- |
| 9             | значение принято, ответ: нельзя оформить |

*Возраст от 14 до 20 лет (значения от 14  до 19 включительно)*
| Входное знаяение      | Ожидаемый результат |
| ------------- | ------------- |
| 15            | значение принято, ответ: можно оформить |

*Возраст от 20 до 45 лет (значения от 20 до 44 включительно)*
| Входное знаяение      | Ожидаемый результат |
| ------------- | ------------- |
| 35            | значение принято, ответ: можно оформить |

*Возраст от 45 до 115 (значение от 45 до 115 включительно)*
| Входное знаяение      | Ожидаемый результат |
| ------------- | ------------- |
| 70            | значение принято, ответ: можно оформить |

*Значение вне диапазона (меньше 0 и больше 115)*
| Входные знаяени      | Ожидаемый результат |
| ------------- | ------------- |
| -3            | значение не принято, ответ: ошибка |
| 118           | значение не принято, ответ: ошибка |


