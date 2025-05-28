# API для получения рекомендаций по конкретному велосипеду

## Реализован GET запрос (/recommendations/) для формирования рекомендаций

### Args:
    - bike_id: id велосипеда
    - db: Сессия базы данных

### Returns:
    - Список объектов таблицы BikeModel

### Response example (bike_id=15094):
```json
[
  {
    "id": 15084,
    "name": "Avalanche 1.0 (2013)",
    "slug": "avalanche-1-0-2013",
    "img_url": "bikes/2025/03/29/avalanche-1-0-2013.png",
    "mark_id": 3473,
    "star": 0,
    "star_count": 0
  },
  {
    "id": 15107,
    "name": "Stomper 24 (2009)",
    "slug": "stomper-24-2009",
    "img_url": "bikes/2025/03/29/stomper-24-2009.png",
    "mark_id": 3473,
    "star": 0,
    "star_count": 0
  },
  {
    "id": 15078,
    "name": "Aggressor (2009)",
    "slug": "aggressor-2009",
    "img_url": "bikes/2025/03/29/aggressor-2009.png",
    "mark_id": 3473,
    "star": 4,
    "star_count": 2
  }
]
```