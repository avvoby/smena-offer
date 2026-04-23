# Пачка лендингов-КП v5.0 — 12 арен

Сгенерировано: 22 апреля 2026.

## 9 холодных лидов (комиссия 8%, таймер 30 дней)

| Код | Арена | Клубы | URL |
|---|---|---|---|
| `dyn_5u2352` | ВТБ Арена | ФК + ХК Динамо Москва | yandexsmena-offer.ru/dyn_5u2352 |
| `spk_7x9m4k` | Лукойл Арена | ФК Спартак Москва | yandexsmena-offer.ru/spk_7x9m4k |
| `spk_h3n8q2` | ДС Мегаспорт | ХК Спартак Москва | yandexsmena-offer.ru/spk_h3n8q2 |
| `cfb_4k7r9p` | ВЭБ Арена | ФК ЦСКА Москва | yandexsmena-offer.ru/cfb_4k7r9p |
| `chk_2y6t8w` | ЦСКА Арена | ХК ЦСКА Москва | yandexsmena-offer.ru/chk_2y6t8w |
| `krd_9u1m5s` | Ozon Арена | ФК Краснодар | yandexsmena-offer.ru/krd_9u1m5s |
| `blt_6d4f7g` | Ростех Арена | ФК Балтика | yandexsmena-offer.ru/blt_6d4f7g |
| `sam_3q8k2v` | Самара Арена | Крылья + Акрон | yandexsmena-offer.ru/sam_3q8k2v |
| `rtr_5n2b9l` | Волгоград Арена | ФК Ротор | yandexsmena-offer.ru/rtr_5n2b9l |

## 3 апгрейда (комиссия 5%, без таймера)

| Код | Арена | Клуб | URL |
|---|---|---|---|
| `znt_8h3c6p` | Газпром Арена | ФК Зенит | yandexsmena-offer.ru/znt_8h3c6p |
| `loc_1w7r4m` | РЖД Арена | ФК Локомотив | yandexsmena-offer.ru/loc_1w7r4m |
| `rst_4k9t2y` | Ростов Арена | ФК Ростов | yandexsmena-offer.ru/rst_4k9t2y |

## Деплой

```bash
cd ~/smena-offer
unzip -o ~/Downloads/smena-landings-v5.zip
vercel --prod
```

Флаг `-o` перезапишет существующую папку `dyn_5u2352` новой версией.

## Ключевые характеристики v5

- Клубный цвет как основной акцент, бежевый #F4EDDC как нейтраль
- Тёмный фон hero универсальный (#0D1525), одинаков для всех
- Голубой Смены живёт только в таблице сравнения
- Комиссия 8% для холодных лидов, 5% для апгрейдов
- Полная адаптивность, два брейкпоинта (960px, 560px)
- Безопасный IntersectionObserver с fallback
