<p align="center">
  <img src="assets/serpent-ai.png" alt="Serpent AI" width="160">
</p>

<h1 align="center">Serpent AI</h1>

<p align="center">
  <b>Расчёты реакторов обычными словами</b> · <b>Reactor calculations in plain words</b>
</p>

<p align="center">
  <b>Быстрее. Проверяемо. Понятно.</b> · <b>Faster. Verifiable. Clear.</b>
</p>

<p align="center">
  <a href="https://github.com/serpent-ai-releases/serpent-ai/releases/latest"><b>⬇️ Скачать последнюю версию · Download the latest release</b></a>
</p>

---

## Русский

**Serpent AI** — программа-оболочка для кода Serpent 2. Вы описываете задачу как коллеге — программа строит модель, проверяет её, запускает расчёт и разбирает результат.

> *Тот же Serpent. Та же физика. Вместо часов — одна фраза.*

### Что умеет

- **Чат вместо входного файла** — «ячейка ВВЭР, обогащение 4.4 %, выгорание до 40» → готовый расчёт
- **Конструктор активной зоны** — ВВЭР-1000, ВВЭР-440, PWR 17×17, MOX, БН-600, расстановка мышью
- **Групповые константы** — 2 / 4 / 8 / 13 / 25 групп, экспорт в Excel, CSV, JSON и таблицы для диффузионных программ
- **Проверка модели до запуска** — предупреждения о физически странной модели, окно проверки
- **Помощник ошибок** — объясняет причину падения и предлагает исправление
- **3D-картограммы, k_eff, выгорание, отчёты** в Word и Excel
- **Локальная нейросеть** (опционально) — читает статьи и чертежи, разбирает выходные файлы
- **Свой ПК или кластер** — SSH / SLURM

**Проверено:** 132 задачи полной верификации — эталоны, все функции через чат, модули, расчёт на кластере. Все пройдены.

### Скачать и установить

1. Откройте раздел **[Releases](https://github.com/serpent-ai-releases/serpent-ai/releases/latest)** и скачайте архив `SerpentAI-1.2.zip`.
2. Распакуйте, запустите `install.bat` (Windows) или `./install.sh` (Linux).
3. Запустите `launch.bat` / `./launch.sh`.

Руководство пользователя — PDF в разделе Releases (русский и английский); оно же входит в архив.

### Требования

- **Python 3.12**
- **Serpent 2** — устанавливается отдельно, лицензия пользователя (VTT / NEA Data Bank)
- Опционально: **Ollama** с моделью Qwen (LLM-функции), **pyvista** (3D на видеокарте)

> **Важно.** Serpent AI — независимая программа. Код Serpent 2, его документация и библиотеки ядерных данных в поставку **не входят**. Проект не связан с VTT и не одобрен VTT.

### Лицензия и контакты

Условия использования — [`LICENSE.txt`](LICENSE.txt) (русский текст имеет приоритет), английский перевод — [`LICENSE_EN.txt`](LICENSE_EN.txt).

- Автор: **Vladimir Ostryakov**
- Почта: **serpentai.ostgroup@gmail.com**
- © 2026 Vladimir Ostryakov. Все права защищены.

---

## English

**Serpent AI** is a front-end for the Serpent 2 code. Describe a task the way you would to a colleague — the program builds the model, validates it, runs the calculation and explains the result.

> *The same Serpent. The same physics. One sentence instead of hours.*

### Features

- **Chat instead of an input file** — "VVER pin cell, enrichment 4.4 %, burnup up to 40" → a ready-to-run case
- **Core designer** — VVER-1000, VVER-440, PWR 17×17, MOX, BN-600, drag-and-drop layout
- **Group constants** — 2 / 4 / 8 / 13 / 25 groups, export to Excel, CSV, JSON and tables for diffusion codes
- **Pre-run validation** — warnings for physically suspicious models, review window before the run
- **Error assistant** — explains why a run failed and suggests a fix
- **3D core maps, k_eff, burnup, Word and Excel reports**
- **Local LLM** (optional) — reads papers and drawings, parses output files
- **Desktop or cluster** — SSH / SLURM

**Verified:** 132 full-verification tasks — reference cases, every feature through the chat, modules, cluster runs. All passed.

### Download and install

1. Open **[Releases](https://github.com/serpent-ai-releases/serpent-ai/releases/latest)** and download `SerpentAI-1.2.zip`.
2. Unpack, run `install.bat` (Windows) or `./install.sh` (Linux).
3. Start with `launch.bat` / `./launch.sh`.

The user manual (Russian and English PDF) is in the Releases section and inside the archive.

### Requirements

- **Python 3.12**
- **Serpent 2** — installed separately, user's own licence (VTT / NEA Data Bank)
- Optional: **Ollama** with a Qwen model (LLM features), **pyvista** (GPU 3D view)

> **Important.** Serpent AI is an independent program. The Serpent 2 code, its documentation and nuclear data libraries are **not** included. The project is not affiliated with, or endorsed by, VTT.

### Licence and contacts

Terms of use — [`LICENSE.txt`](LICENSE.txt) (the Russian text prevails), English translation — [`LICENSE_EN.txt`](LICENSE_EN.txt).

- Author: **Vladimir Ostryakov**
- Email: **serpentai.ostgroup@gmail.com**
- © 2026 Vladimir Ostryakov. All rights reserved.
