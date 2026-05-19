---
id: contr-004
between: [src-20260513-aimarketolog-site-new, src-20260513-vlad-tg-sales-message]
status: resolved (два канала продаж, не конфликт)
resolution_date: 2026-05-13
created: 2026-05-13
---

# Contradiction 004 — WayForPay (лендинг) vs @yasko_robot (Telegram-пост)

## Конфликт

| Источник | Канал оплаты |
|---|---|
| **Лендинг** (src-20260513-aimarketolog-site-new) | Прямые WayForPay-кнопки + спецбронь $25 |
| **Telegram-пост** (src-20260513-vlad-tg-sales-message) | Все ссылки через `@yasko_robot` (Telegram bot) |

## Анализ

**Это НЕ настоящее противоречие** — это **сегментация воронок по аудитории**:
- Холодный канал (лендинг + WayForPay) для новых лидов
- Тёплый канал (Telegram + bot) для уже знающих Влада

См. подробно `notes/n-two-funnels-cold-vs-warm.md`.

## Resolution

**Зафиксировано как стратегическое решение, не баг:**
- WayForPay-кнопки остаются на лендинге для cold-traffic
- @yasko_robot — основной канал для warm-traffic в Telegram
- Оба канала ведут в одну CRM/бухгалтерию (предположительно — нужно подтвердить с командой)

**Метрика разделения:**
- UTM-маркировка по каналу
- Раздельный учёт конверсий

## Impact на claims

Создаётся новый claim **c-0011** (см. file): «AI-Маркетолог Потока 2 использует двухканальную воронку — холодный (WayForPay лендинг) + тёплый (Telegram @yasko_robot)».

## Impact на syntheses

- **syn-funnel-strategy** — добавить параграф про два канала на следующей итерации.
