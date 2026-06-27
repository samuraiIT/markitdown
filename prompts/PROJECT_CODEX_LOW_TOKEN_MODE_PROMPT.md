# Project Codex Low-Token Mode Prompt

Используй этот prompt, когда работа идёт внутри `projects/markitdown/`.

- Базовый режим наследуется от root `prompts/CODEX_LOW_TOKEN_MODE_PROMPT.md`.
- Сначала читай `AGENTS.md`, `README.md` и только затем точечно открывай docs, scripts или package metadata.
- Для поиска используй `rg --files` и `rg -n`; `rg -uu` включай только если задача явно требует ignored paths.
- Держи чтение узким: конвертер, CLI и docs, без лишнего обхода vendor или build-артефактов.
