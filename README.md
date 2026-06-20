# Искра — Экосистема расширений для OpenCart 4

[![PHP](https://img.shields.io/badge/PHP-8.1%2B-blue)](https://php.net)
[![OpenCart](https://img.shields.io/badge/OpenCart-4.1%2B-green)](https://opencart.com)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Site](https://img.shields.io/badge/Site-iskra--ecommerce.github.io-purple)](https://iskra-ecommerce.github.io)

**Iskra** — open-source экосистема расширений для OpenCart 4. Логирование, миграции, бэкапы, проверка целостности и 5 языков (RU UK KK BE RO) из коробки. MIT License, бесплатно.

🔗 **Сайт:** https://iskra-ecommerce.github.io  
🐙 **Организация:** https://github.com/iskra-ecommerce

---

## Как всё началось

Представьте: три ночи, остыл кофе, клиент звонит — «сайт упал, база сломалась, бэкапа нет». Разработчик сидит, смотрит в экран и думает: «Почему это никто не сделал нормально?»

Так родилась **Искра**. Не модуль, не плагин — а экосистема. Три расширения, которые живут друг с другом, как соседи в старом дворе: кто-то держит лестницу, кто-то — ведро, кто-то — краску. Вместе красят забор, по отдельности — бесполезны.

## Расширения

### Iskra Core — фундамент

**Что делает:** логи, миграции БД, бэкапы, проверка целостности, поддержка кириллицы (utf8mb4).

**Для кого:** для разработчиков, которые устали ночевать у сервера.

**Особенности:**
- 📋 **Дневник капитана** — логи с уровнями DEBUG → CRITICAL, фильтрами, автоочисткой
- 🗄️ **Миграции с rollback** — версионирование БД, как грузчики с планом квартиры
- 💾 **Бэкапы** — автоматические SQL-дампы, restore из админки одной кнопкой
- 🔍 **Проверка целостности** — доктор перед операцией: таблицы проверены, можно лезть
- 🌐 **Кириллица** — RU, UK, KK, BE, RO работают без кракозябр

[GitHub →](https://github.com/iskra-ecommerce/iskra_core) | [Релизы ↓](https://github.com/iskra-ecommerce/iskra_core/releases)

### Iskra Language Pack — 5 языков

**Что делает:** единый языковой пакет с 5 нативными переводами для админки и витрины.

**Языки:** Русский, Українська, Қазақша, Беларуская, Română.

**Особенности:** не машинный перевод — живой текст. Установка за 2 клика через Extension Installer.

[GitHub →](https://github.com/iskra-ecommerce/iskra_language_pack) | [Релизы ↓](https://github.com/iskra-ecommerce/iskra_language_pack/releases)

### Iskra Account — регистрация

**Что делает:** современная регистрация с мультиязычным интерфейсом.

**Особенности:**
- Валидация полей в реальном времени
- Маски телефонов (+7, +380, +373, +40 и др.)
- Индикатор сложности пароля
- Интеграция с Language Pack (5 языков)

[GitHub →](https://github.com/iskra-ecommerce/iskra_account) | [Релизы ↓](https://github.com/iskra-ecommerce/iskra_account/releases)

## Установка

```
1. Скачайте .ocmod.zip из GitHub Releases
2. System → Extensions → Extension Installer → Upload
3. Extensions → Modules → Install → Enable
4. Идите спать — оно работает
```

**Совместимость:** OpenCart 4.1+, PHP 8.1+

## Для кого это

- Для разработчиков, которые устали изобретать велосипед
- Для владельцев магазинов в СНГ, которым нужна кириллица
- Для тех, кто не хочет платить $50 за модуль бэкапов
- Для тех, кто хочет спать ночью, зная, что у сервера есть дневник

## Ключевые слова

opencart 4, opencart extension, opencart module, opencart русский, opencart украинский, opencart казахский, opencart белорусский, opencart румынский, opencart кириллица, opencart логирование, opencart бэкап, opencart миграция, iskra, ecommerce, cms, mit license, free opencart extension

## Лицензия

MIT License. Звёзды приветствуются. Баг-репорты — ещё больше. PR — как письма из путешествия: читаем с удовольствием.