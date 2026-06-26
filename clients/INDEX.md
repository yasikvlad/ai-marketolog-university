# Clients · База клиентов AI-Маркетолога

> CRM-досье на активных клиентов/учеников. Отличается от `../cases/` — там истории успеха для соцдоказательства (точка А→Б с результатом), здесь — рабочее досье по живому клиенту (запрос, диагноз, открытые данные, следующие шаги).
>
> Новый клиент → копия `_template-client.md` в свою папку `clients/<slug>/client-<slug>.md`, сырьё переписки/созвонов → `clients/<slug>/raw/`. Добавить строку в таблицу ниже.

## Активные клиенты

| ID | Клиент | Ниша | Пакет / сделка | Статус | Дедлайн | Обновлён |
|----|--------|------|----------------|--------|---------|----------|
| [client-alona-shpartak](alona-shpartak/client-alona-shpartak.md) | Алёна (@alona_shpartak) | Подбор студентов в универы UK | Автоматизация · $750/£600 ×4 | active · онбординг (ждём юнит-экономику) | 2026-09 | 2026-06-26 |

## Поля досье (frontmatter)

`id · person · handle · niche · status · stage · flow · package · deal · deadline · channel · acquired_from · source_transcripts · artifacts · related_cases · tags · created · updated`

`status`: `lead` → `active-client` → `delivered` → `archived`.
