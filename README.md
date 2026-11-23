# AI and Human Messenger — страница чата

Репозиторий: `dperegudov61/AI-Human-Messenger`
Адрес: **https://dperegudov61.github.io/AI-Human-Messenger/**

Это постоянный адрес страницы чата. Сейчас здесь стоит заглушка: она сразу уводит на
страницу входа `https://dperegudov61.github.io/accounts/`, сохраняя подсказки
`?r=tunnel` и `?u=<адрес сервера>`.

Следующий шаг — сам чат: он будет загружаться прямо из этого репозитория (постоянная
ссылка), а всё содержимое получать через туннель с домашнего ПК.

| файл | что это |
|---|---|
| `index.html` | страница чата (пока — перенаправление на вход) |
| `404.html` | её копия: Pages отдаёт её на любой неизвестный путь (кладёт `publish_door.ps1`) |
| `.nojekyll` | отключает обработку Jekyll |

Публикация: правим `messenger\` в проекте → `.\publish_door.ps1` → через полминуты
страница обновится.

Где что теперь:

| что | где |
|---|---|
| домашняя страница | https://dperegudov61.github.io/ |
| вход и регистрация | https://dperegudov61.github.io/accounts/ |
| список мостов (status.json) | https://dperegudov61.github.io/status.json (репозиторий `dperegudov61.github.io`) |
| страница чата | этот репозиторий |
