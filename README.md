# Arnold investment Observatory

## О проекте / токене

Arnold investment (ARNI) — токен сети TON. В метаданных проект заявляет получение TON за удержание ARNI и указывает происхождение из sTONks. Официальный сайт описывает распределение TON держателям и дефляционный механизм. Эти заявления проекта не являются независимой проверкой выплат или доходности.

Контракт: `EQAZzZzhBdrPwxFVQHWlMHbDY_eOk3LeUPr07VWdX4B0193M`; decimals: 9.

Источники, проверка 2026-11-24:

- https://tonapi.io/v2/jettons/EQAZzZzhBdrPwxFVQHWlMHbDY_eOk3LeUPr07VWdX4B0193M
- https://arnold-arni.site/
- https://t.me/arnoldton
- https://t.me/TonArnold

Изображение пользователя используется в баннере и вместо флагов по прямому указанию. Логотип из метаданных сохранён отдельно.

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
Данные собраны из публичных API; статус и охват каждого раздела сохранены в data/snapshot.json. История догружается постепенно, неполные интервалы отмечены.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
GitHub Actions: резервное расписание 7,37 * * * * (UTC), запуск по изменениям и вручную. Интервал номинально 30 минут; GitHub может задерживать запуски. Подключение к общему Cloudflare runner отдельно не подтверждено.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.

## Проверка и публикация

Контракт и пул сопоставлены с TonAPI, кандидат пула найден через GeckoTerminal.
Внешние шрифты, скрипты и изображения для отрисовки не требуются.
Браузерная проверка: настольный экран 1363 px и мобильные области 390/360 px; горизонтального переполнения нет. Проверены RU/EN, TON/USD, раскрытие холдеров 10 → 20.
TON Storage / Resistance Tools: публикация ещё не выполнена. Плановый запуск Actions пока не наблюдался.

Нулевой адрес классифицируется отдельно и не участвует в рейтинге обычных держателей. Источник: https://tonapi.io/v2/accounts/0:0000000000000000000000000000000000000000000000000000000000000000
