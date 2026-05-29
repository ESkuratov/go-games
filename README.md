# go-games

Партии го (ГО, 围棋) для изучения и разбора.

## Формат файлов

SGF-файлы в формате Obsidian Goban Plugin:

```
---
tags:
  - goban
goban-sgf-plugin: 1.3.3
---

## Партия: [Название]

[Комментарий к партии]

```sgf
FF[4]GM[1]SZ[19]RU[Japanese]CA[UTF-8]AP[Obsidian Goban SGF Plugin:1.3.3]
...
```
```

## Структура

- `games/` — партии с комментариями
- `problems/` — задачи (tsumego)
- `famous/` — знаковые партии

## О авторе

Разбор партий для 13 кю. Источники: Go4Go, GoMagic, GoGameWorld.
