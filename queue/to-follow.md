# To-follow queue (BFS)

Внутренняя очередь ссылок, найденных внутри уже обработанных источников. Пополняется автоматически на шаге 7 пайплайна (см. METHODOLOGY.md §4).

Формат:

```
- <URL>
  parent: <source-id>
  anchor: "<anchor text>"
  predicted_relevance: X/5
  depth: N
  status: queued | fetched | rejected
  note: (optional) why it's important
```

## Queue

<!-- пусто -->

## Done

<!-- пусто -->
