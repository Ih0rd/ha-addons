# OmniRoute Home Assistant Add-on

Обёртка над [OmniRoute](https://github.com/diegosouzapw/OmniRoute) — бесплатный AI-гейтвей,
160+ провайдеров, один endpoint.

## Установка

1. Settings → Add-ons → Add-on Store → ⋮ (правый верх) → Repositories
2. Вставить URL этого репозитория → Add
3. Найти "OmniRoute" в списке → Install → Start
4. Открыть веб-интерфейс кнопкой "OPEN WEB UI" (порт 20128)

## Настройка

Все настройки (провайдеры, ключи, комбо, компрессия) делаются внутри
веб-дашборда OmniRoute после запуска — отдельный options/schema в аддоне не нужен.

## Данные

Persist через `/data` (монтируется Supervisor автоматически), симлинк
`/app/data -> /data` внутри контейнера сохраняет SQLite-базу между обновлениями.
