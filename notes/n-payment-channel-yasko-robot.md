---
id: n-payment-channel-yasko-robot
title: Новый платёжный канал — Telegram bot @yasko_robot (для тёплых продаж)
tags: [funnel, payment, infrastructure]
sources: [src-20260513-vlad-tg-sales-message]
confidence: H
created: 2026-05-13
supersedes: []
superseded_by: null
---

# Новый платёжный канал — Telegram bot @yasko_robot (для тёплых продаж)

В Telegram продающем посте все CTA-ссылки оплаты идут через **@yasko_robot**, не через прямые WayForPay-кнопки:

- $647 → https://t.me/yasko_robot?start=pay_88697b36-3
- $997 → https://t.me/yasko_robot?start=pay_a8f59095-4
- $2500 → https://t.me/yasko_robot?start=pay_f223e555-5

На лендинге https://new.aimarketolog.site/ — прямые WayForPay-кнопки.

**Это два параллельных платёжных канала:**
- **Холодный** (лендинг + WayForPay): для новых пользователей, регистрация → оплата прямой ссылкой
- **Тёплый** (Telegram + @yasko_robot): для уже знающих Влада, через бот = персонализированный flow + удержание пользователя в Telegram-экосистеме

**Преимущества Telegram-бота:**
- Пользователь не уходит из Telegram (где живёт сообщество)
- Бот может up-sell / cross-sell после оплаты
- Сбор UTM-данных и контактов без отдельной формы
- Удобство для аудитории, привыкшей платить через TG

**Импликация:**
- В Telegram-постах используем @yasko_robot
- На лендинге — WayForPay (для холодных)
- В письмах в email-цепочке — выбор обоих
- Метрика конверсии измеряется **раздельно** по каналам

## Links

- supports: [n-funnel-7-stages-webinar]
- refines: []
- contradicts: []
- generalizes: []
