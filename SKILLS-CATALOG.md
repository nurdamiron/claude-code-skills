<div align="center">

# 🗂 Каталог скиллов для Claude по нишам

**Только живые репозитории.** Каждая ссылка проверена через GitHub API · ⭐ — реальное число звёзд на дату проверки.

`Проверено: 2026-05-31` · `~30 репо` · `12 ниш`

</div>

---

## Как это ставить

Команды у авторов разные — всегда сверяйся с README конкретного репо. Три основных способа:

```bash
# 1) Через официальный marketplace Claude Code
/plugin marketplace add <owner>/<repo>
/plugin install <plugin-name>

# 2) Через менеджер npx skills (vercel-labs/skills)
npx skills add https://github.com/<owner>/<repo>

# 3) Вручную — скопировать папку скилла
git clone https://github.com/<owner>/<repo>
cp -r <repo>/<skill> ~/.claude/skills/
```

> **Claude Code** (терминал) — основной формат этих репо.
> **Claude.ai** (чат, платный) — заархивируй папку `skill/` в `.zip` и загрузи через **Settings → Capabilities → Skills**.

---

## ⭐ С чего начать (если лень выбирать)

| Хочу… | Ставлю | ⭐ |
|---|---|---|
| 📈 продвигать продукт / контент | [`coreyhaines31/marketingskills`](https://github.com/coreyhaines31/marketingskills) | ~31k |
| 💻 дисциплинировать Клода в коде | [`obra/superpowers`](https://github.com/obra/superpowers) | ~214k |
| 🔌 подключить Клода к своим приложениям | [Rube](https://rube.app) (Slack/GitHub/Notion/Gmail) | ~29k |
| 🔎 SEO-аудит прямо сейчас | [этот репо → `/seo audit`](SKILL.md) | — |

---

## 🎯 Маркетинг / контент / SMM / SEO

| Репо | ⭐ | Что внутри |
|---|:--:|---|
| [`coreyhaines31/marketingskills`](https://github.com/coreyhaines31/marketingskills) | ~31k | Топовый маркетинг-пак: CRO, копирайтинг, SEO, аналитика, email, growth (50+ скиллов) |
| [`AgriciDaniel/claude-seo`](https://github.com/AgriciDaniel/claude-seo) | ~7.6k | SEO-воркфлоу: 25 сабскиллов + 18 сабагентов — технический SEO, hreflang, sitemap, schema, programmatic |
| [`jonathimer/devmarketing-skills`](https://github.com/jonathimer/devmarketing-skills) | ~80 | Маркетинг для разработчиков: HN, Reddit, технические туториалы, docs-as-marketing |
| [`boraoztunc/skills`](https://github.com/boraoztunc/skills) | ~73 | Копирайтинг (фреймворки Огилви), реклама, SEO, дизайн, контент-план |

---

## 🎨 Дизайн / UI

| Репо | ⭐ | Что внутри |
|---|:--:|---|
| [`Leonxlnx/taste-skill`](https://github.com/Leonxlnx/taste-skill) | ~30k | Анти-«слоп» дизайн: стилевые варианты + генерация рефов, регуляторы плотности/анимации |
| [`Owl-Listener/designer-skills`](https://github.com/Owl-Listener/designer-skills) | ~1.4k | 63 скилла на весь дизайн-цикл — от ресёрча до хендоффа разработчику |
| [`vercel-labs/web-interface-guidelines`](https://github.com/vercel-labs/web-interface-guidelines) | ~650 | Гайдлайны Vercel по UI как скилл: аудит интерфейса по 100+ правилам |

---

## 🎬 Видео / медиа

| Репо | ⭐ | Что внутри |
|---|:--:|---|
| [`remotion-dev/skills`](https://github.com/remotion-dev/skills) | ~3.4k | Программное видео на React (Remotion). Официальный |

---

## 🛠 Разработка / workflow

| Репо | ⭐ | Что внутри |
|---|:--:|---|
| [`obra/superpowers`](https://github.com/obra/superpowers) | ~214k | Флагман экосистемы: брейншторм → план → исполнение по TDD, дебаг |
| [`vercel-labs/agent-skills`](https://github.com/vercel-labs/agent-skills) | ~27k | Официальные скиллы Vercel: React / Next.js best practices, аудит UI, React Native, деплой |
| [`Jeffallan/claude-skills`](https://github.com/Jeffallan/claude-skills) | ~9.5k | 66 скиллов для фуллстека: языки, фреймворки, тесты, DevOps, API |

---

## 🧭 Поведение агента (guardrails)

| Репо | ⭐ | Что внутри |
|---|:--:|---|
| [`multica-ai/andrej-karpathy-skills`](https://github.com/multica-ai/andrej-karpathy-skills) | ~163k | Правила против типичных косяков ИИ-кодинга (один `CLAUDE.md`). Мёржится с твоим CLAUDE.md |

---

## 🔒 Безопасность

| Репо | ⭐ | Что внутри |
|---|:--:|---|
| [`briiirussell/cybersecurity-skills`](https://github.com/briiirussell/cybersecurity-skills) | ~217 | Кибербез для AI-агентов (Claude Code, Cursor, Codex) |
| [`BehiSecc/awesome-claude-skills`](https://github.com/BehiSecc/awesome-claude-skills) | ~9k | Список с упором на security: OWASP, Trail of Bits, редакция PII, env-secrets |

---

## 💰 Финансы / моделирование

| Репо | ⭐ | Что внутри |
|---|:--:|---|
| [`anthropics/financial-services-plugins`](https://github.com/anthropics/financial-services-plugins) | ~29k | Официальный пак Anthropic: DCF, LBO, 3-statement, comps, M&A, equity research, коннекторы данных |
| [`jeremylongshore/excel-analyst-pro`](https://github.com/jeremylongshore/excel-analyst-pro) | ~32 | DCF, LBO, variance-отчёты и пивоты в Excel на обычном языке (через Excel MCP) |

---

## 📊 Office / данные / документы

| Репо | ⭐ | Что внутри |
|---|:--:|---|
| [`anthropics/claude-cookbooks`](https://github.com/anthropics/claude-cookbooks) | ~45k | Официальные рецепты Anthropic: финмодели, дашборды, цепочка CSV → Excel → PPT → PDF, создание своих скиллов |
| [`tfriedel/claude-office-skills`](https://github.com/tfriedel/claude-office-skills) | ~700 | Создание и правка PPTX / DOCX / XLSX / PDF: формулы, redlining, заполнение форм |

---

## 🔬 Наука / ресёрч / письмо

| Репо | ⭐ | Что внутри |
|---|:--:|---|
| [`Imbad0202/academic-research-skills`](https://github.com/Imbad0202/academic-research-skills) | ~25k | Академический пайплайн: research → write → review → revise → finalize, под ICLR / NeurIPS / Nature |
| [`aspi6246/Claude-Code-Skills-for-Academics`](https://github.com/aspi6246/Claude-Code-Skills-for-Academics) | ~125 | Скиллы под академическую работу: литобзор, статьи, рецензирование |

---

## 🔌 Подключение приложений (MCP / Workspace)

| Инструмент | ⭐ | Что делает | Установка |
|---|:--:|---|---|
| **Rube** ([rube.app](https://rube.app), by [Composio](https://github.com/ComposioHQ/composio)) | ~29k | Коннектор к 500+ приложениям (Slack, GitHub, Notion, Gmail) одной авторизацией | Claude Desktop / Code → Settings → Connectors → `https://rube.app/mcp` |
| [`googleworkspace/cli`](https://github.com/googleworkspace/cli) | ~27k | Полный доступ к Gmail / Drive / Calendar / Sheets через встроенный MCP | `npx skills add https://github.com/googleworkspace/cli` |

---

## 📦 Большие мульти-категорийные библиотеки

| Репо | ⭐ | Что внутри |
|---|:--:|---|
| [`sickn33/antigravity-awesome-skills`](https://github.com/sickn33/antigravity-awesome-skills) | ~39k | 1400+ скиллов с CLI-установщиком и готовыми бандлами по ролям |
| [`alirezarezvani/claude-skills`](https://github.com/alirezarezvani/claude-skills) | ~17k | 337 скиллов: инженерия, маркетинг, продукт, compliance, C-level, ресёрч |

---

## 📚 Мета-каталоги и инструменты (где искать ещё)

| Источник | ⭐ | Что внутри |
|---|:--:|---|
| [`anthropics/skills`](https://github.com/anthropics/skills) | ~145k | Официальный репо Anthropic — эталон и примеры |
| [`ComposioHQ/awesome-claude-skills`](https://github.com/ComposioHQ/awesome-claude-skills) | ~63k | Список с разбивкой по задачам (контент, ресёрч, Twitter и др.) |
| [`hesreallyhim/awesome-claude-code`](https://github.com/hesreallyhim/awesome-claude-code) | ~45k | Скиллы, хуки, slash-команды, оркестраторы, плагины |
| [`VoltAgent/awesome-agent-skills`](https://github.com/VoltAgent/awesome-agent-skills) | ~24k | 1000+ скиллов от Anthropic, Vercel, Stripe, Cloudflare и комьюнити |
| [`vercel-labs/skills`](https://github.com/vercel-labs/skills) | ~21k | Менеджер `npx skills` + meta-скилл `find-skills` (находит и ставит другие скиллы) |
| [`travisvn/awesome-claude-skills`](https://github.com/travisvn/awesome-claude-skills) | ~13k | Кураторский список с таймлайном и гайдами |
| [skills.sh](https://skills.sh) | 🌐 | Лидерборд скиллов по числу установок — самый близкий к объективному «топу» источник |

---

## ⚠️ Прежде чем ставить — прочти

- **Звёзды и состав репо меняются** — числа приблизительные на дату проверки в шапке.
- **Форки-клоны.** У популярных репо бывают копии с тем же описанием (например у `coreyhaines31/marketingskills` — `ayrshare/marketingskills`, `syntax-syndicate/marketing-skills`). Ставь **оригинал**.
- **Скилл = чужой код, который исполняет твой Claude.** Перед установкой открой `SKILL.md` и доверяй проверенным авторам. В security-списках периодически вычищают фишинговые ссылки — слепо доверять каталогу нельзя.
- **Агрегаторы** (`antigravity-awesome-skills` 1400+, `alirezarezvani` 337) собирают чужие скиллы — качество отдельных компонентов внутри не гарантируется.

---

<div align="center">

← Назад в [README](README.md) · 🔎 встроенный SEO-агент: [`SKILL.md`](SKILL.md)

</div>
