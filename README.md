# 🚛 Калькулятор стоимости доставки

Калькулятор доставки грузов между городами. Учитывает расстояние, вес, объёмный вес, тип доставки и доп. услуги.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## Демо

**[Открыть калькулятор →](https://Anllane.github.io/delivery-calculator/)**

## Возможности

- 6 городов отправки/получения с реальными расстояниями
- Ползунок веса 1-500 кг
- Габариты груза (ДxШxВ) с расчётом объёмного веса
- 3 типа доставки: обычная, экспресс, грузовая
- Доп. услуги: страховка, упаковка, до двери
- Расчёт по формуле: расстояние + вес + тип + допы
- Показ расстояния, срока и веса
- Полная адаптивность

## Настройка

- Города и расстояния: объект `DISTANCES` в скрипте
- Тарифы: `basePricePerKg` по зонам расстояния
- Типы доставки: множитель `data-mult` у кнопок
- Доп. услуги: `data-price` в `.toggles`

## Лицензия

MIT
