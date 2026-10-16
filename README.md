<h1 align="center">Привіт, я Ілля 👋</h1>

<p align="center">
  <i>System administrator turned automation &amp; AI integration engineer.<br>
  I build workflows that run on their own, fail loudly and are tested before production.</i>
</p>

<p align="center">
  Системний адміністратор, який переходить в автоматизацію та інтеграцію ШІ.<br>
  Замінюю ручну IT-рутину процесами, що працюють самі, голосно повідомляють про збої<br>
  і перевірені тестами до того, як потрапляють у продакшн.
</p>

<p align="center">
  <img alt="n8n" src="https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black">
  <img alt="Gemini" src="https://img.shields.io/badge/Google%20Gemini-4285F4?logo=googlegemini&logoColor=white">
  <img alt="Qdrant" src="https://img.shields.io/badge/Qdrant-DC244C">
  <img alt="Active Directory" src="https://img.shields.io/badge/Active%20Directory-0078D4?logo=microsoft&logoColor=white">
</p>

## Що я роблю

- **Автоматизую IT-процеси на стику систем:** Active Directory, Google Workspace, Microsoft 365, Redmine, Hetzner, Cloudflare.
- **Підключаю LLM там, де вони корисні** (розбір «брудного» тексту, аналіз помилок, чат-інтерфейси), а рішення й цифри лишаю детермінованому коду.
- **Ставлюся до автоматизацій як до коду:** тести на заглушках, навмисні поломки (mutation checks), живі прогони на тестових даних і README з чесним розділом «чого тут немає». Пишу разом з AI-асистентами і відповідаю за результат тестами.

## ⭐ Улюблений проєкт: бот, який розгортає сервери

**[CVAT ChatOps](https://github.com/IlyaRumasov/cvat-chatops)** — AI-агент у Google Chat (n8n + Gemini), що розгортає й керує серверами в Hetzner. Просиш сервер людською мовою і за 10–15 хвилин отримуєш готовий CVAT з доступами.

<p>
  <img src="https://raw.githubusercontent.com/IlyaRumasov/cvat-chatops/main/docs/chat-tariff-unavailable.png" width="48%" alt="Бот відмовляє через недоступний тариф і пропонує найближчі з цінами">
  <img src="https://raw.githubusercontent.com/IlyaRumasov/cvat-chatops/main/docs/chat-delete-confirm.png" width="48%" alt="Бот просить підтвердження перед видаленням сервера">
</p>

- 26 дій у чаті: деплой, живлення, снепшоти, зміна тарифу, rebuild, rescue, звіт по витратах, новий сервер зі знімка.
- Безпека за замовчуванням: підтвердження перед небезпечними діями, автоматичний снепшот, захист від видалення.
- Чесні межі: якщо тарифу немає, бот не вгадує. Він показує найближчі доступні з цінами, а обирає людина.

## Вибрані проєкти

| Проєкт | Що робить | Підтвердження |
|---|---|---|
| [**staff-offboarding-automation**](https://github.com/IlyaRumasov/staff-offboarding-automation) | Читає заявки на звільнення в Redmine, знаходить людину в AD, Google Workspace і Microsoft 365, закриває доступи й пише звіт. Якщо збіг неоднозначний, нічого не чіпає. | 67 сценаріїв на заглушках, живий прогін на тестовому співробітнику, повна історія v1 → v2 |
| [**hr-automation-candidate-onboarding**](https://github.com/IlyaRumasov/hr-automation-candidate-onboarding) | Створює акаунти в AD, шле вітальні листи, сповіщає про зміну статусу. Один проаналізований ШІ тікет на збій замість тікета на кожну спробу. | 61 сценарій на заглушках, mutation checks, живі тести знайшли помилку, якої заглушки не бачили |
| [**ai-audio-qa-pipeline-evolution**](https://github.com/IlyaRumasov/ai-audio-qa-pipeline-evolution) | QA датасетів мовлення: сліпа транскрипція, потім порівняння текстів (WER/CER). Синхронний режим і пакетний на Vertex AI. | 48/48 тестів, проаналізовано датасет понад 150 тис. рядків |
| [**telegram-prompt-architect**](https://github.com/IlyaRumasov/telegram-prompt-architect-multimodal-ai-agent) | Telegram-бот: текст або голос на вході, готовий промпт для ChatGPT, Claude чи Gemini на виході. Режими, мови, добові ліміти. | 60 автотестів |
| [**ai-entity-matching-nomenclature**](https://github.com/IlyaRumasov/ai-entity-matching-nomenclature) | LLM розбирає «брудні» назви позицій ERP, а оцінку збігу рахує детермінований код. | На 132 рядках: 7 збігів, усі правильні (попередній підхід лише з LLM: 18, з них 11 хибних) |

## Стек

| | |
|---|---|
| Автоматизація | n8n (self-hosted), Bash, Linux, Docker |
| ШІ | Google Gemini, OpenAI API, Qdrant, Flowise, LangChain |
| Інфраструктура | Active Directory / LDAP, Google Workspace, Microsoft 365 / Entra ID, Hetzner, Cloudflare, Google Cloud |
| Інтеграції | Redmine, Google Chat, MS Teams, Telegram, SendGrid, Lever, Google Sheets |
| Код | Python, JavaScript |

## Шукаю

Ролі в **інтеграції ШІ / інженерії автоматизації** або **сисадміна з реальною автоматизацією**. Базуюсь у Києві.

## 📫 Контакти

- **LinkedIn:** [Illia Rumasov](https://linkedin.com/in/rumasov-illia)
- **Email:** ilyarumasov@gmail.com
