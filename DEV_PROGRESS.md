# DEV_PROGRESS — accomplish

> Живой чек-лист автономного цикла разработки. Обновляется каждый проход.
> Проект: Electron + React AI-ассистент (pnpm monorepo: apps/web, apps/desktop, packages/agent-core).

## ✅ Done
- 2026-11-11: Заведён трекинг-чек-лист, ветка разработки `ccr-e9692c67-uk3jai`.

## ⏳ Remaining (roadmap)
- [ ] Прогнать полную верификацию: `pnpm lint && pnpm format:check && pnpm -F @accomplish/web test && pnpm -F @accomplish/desktop test && pnpm -F @accomplish_ai/agent-core test`.
- [ ] Поднять покрытие тестами agent-core (MCP-инструменты, storage/migrations).
- [ ] Разобрать открытые TODO/FIXME в коде.
- [ ] Проверить IPC-цепочку handlers ↔ preload ↔ web на рассинхрон типов.
- [ ] Обновить docs/architecture.md под текущую структуру.

## 🧭 Decisions made
- Работаем строго по CLAUDE.md проекта (ESM .js-импорты в agent-core, воркспейс-скоуп тестов).

## ⚠️ Flagged for review — проверь
- (пока нет)
