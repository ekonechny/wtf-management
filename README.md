# OKR, 4LS, OMG: Справочник WTF-практик технического менеджера 🤯📊
*Когда аббревиатур больше, чем времени на проект...*

Добро пожаловать в **справочник WTF-практик технического менеджера**.  
Здесь собраны методы, фреймворки и техники, которыми пользуются технические менеджеры, архитекторы и тимлиды.

## 1. Архитектура и дизайн систем
### 🏗 Визуализация и моделирование
- [**C4M** – C4 Model](https://c4model.com/) — Модель архитектурного проектирования, состоящая из четырех уровней (Контекст, Контейнер, Компонент, Код). Помогает визуализировать сложные системы и их взаимосвязи.
- [**UML** – Unified Modeling Language](https://www.uml.org/) — Унифицированный язык моделирования, используемый для описания структурных и поведенческих аспектов системы. Поддерживает различные диаграммы, такие как диаграммы классов, последовательностей и состояний.
- [**DFD** – Data Flow Diagram](https://www.visual-paradigm.com/guide/data-flow-diagram/what-is-data-flow-diagram/) — Диаграмма потоков данных, которая помогает анализировать, как данные перемещаются в системе, определяя входные и выходные точки.
- [**4+1** – 4+1 View Model](https://www.ibm.com/docs/en/rational-soft-arch/9.7?topic=views-41-view-model) — Архитектурная модель, описывающая систему с пяти точек зрения: логическая, процессная, физическая, разработческая и сценарии использования.
- [**R&W** – Rozanski & Woods Viewpoints](https://www.viewpoints-and-perspectives.info/) — Методология представления архитектуры через точки зрения, включая эксплуатацию, безопасность и производительность.
- [**ERD** – Entity Relationship Diagram](https://www.lucidchart.com/pages/entity-relationship-diagram) — Диаграмма сущность-связь, используется для моделирования данных и их отношений в базе данных.
- [**SADT** – Structured Analysis and Design Technique](https://www.visual-paradigm.com/guide/data-flow-diagram/structured-analysis-and-design-technique/) — Методика структурного анализа и проектирования, используется для описания процессов и их взаимодействий в системе.
- [**BPML** – Business Process Modeling Language](https://en.wikipedia.org/wiki/Business_Process_Modeling_Language) — Язык моделирования бизнес-процессов, который позволяет описывать бизнес-логику и потоки работ.
- [**BPMN** – Business Process Model and Notation](https://www.bpmn.org/) — Графический стандарт для моделирования бизнес-процессов, используемый для описания рабочих потоков с четкой семантикой.

### 📝 Документирование решений и процессов
- [**ADR** – Architecture Decision Record](https://adr.github.io/) — Структурированный формат записи архитектурных решений, фиксирующий их причины и последствия.
- [**Arc42**](https://arc42.org/) – Шаблон архитектурной документации, позволяющий структурировано описывать архитектуру системы.
- [**RFC**](https://datatracker.ietf.org/) – Request for Comments — метод формализации и обсуждения технических решений.
- [**TAM**](https://pubs.opengroup.org/togaf-standard/architecture-models/) – Technical Architecture Model — методология проектирования архитектуры организации.
- [**SAD**](https://www.sei.cmu.edu/research-capabilities/software-architecture/) – Software Architecture Document — Документ, содержащий описание архитектуры системы и ее компонентов.
- [**LDJ**](https://ajsmart.com/ldj) – Lightning Decision Jam — методика фасилитации для быстрого принятия архитектурных решений.
- [**TAR** – Technical Architecture Review](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=4965) – Метод оценки архитектуры для выявления слабых мест и потенциальных улучшений.

### 🏗 Фреймворки для обсуждения архитектурных решений
- [**TDDM** – Top-Down Decision Making](https://www.researchgate.net/publication/260853898_Top-down_and_bottom-up_decision_processes_in_arrival_time_decisions) — Метод принятия решений сверху вниз, обеспечивающий стратегическое управление архитектурой.
- [**BFD** – Big Freaking Diagram](https://www.complexdiagrams.com/) — Концепция визуализации архитектуры больших систем.
- [**DDD** – Domain-Driven Design](https://martinfowler.com/bliki/DomainDrivenDesign.html) — Методология проектирования ПО, ориентированная на бизнес-домен.
- [**FEA**](https://www.enterprise-architecture.info/EA_Feasibility.htm) – Future Enterprise Architecture — Метод управления архитектурой предприятия с акцентом на будущее развитие.
- [**ESA**](https://www.gartner.com/en/information-technology/glossary/enterprise-solution-architecture) – Enterprise Solution Architecture — Подход к построению корпоративных решений на основе архитектурных принципов.
- [**SABSA**](https://sabsa.org/) – Security Architecture Framework — Методология проектирования архитектуры безопасности.

---

## 2. Разработка и качество кода
- [**Pair Programming**](https://www.agilealliance.org/glossary/pairing/) – Метод совместного программирования, при котором два разработчика работают за одним компьютером: один пишет код, другой рецензирует в реальном времени. Улучшает качество кода, способствует передаче знаний и снижает количество багов
- [**Swarming**](https://www.scrum.org/resources/blog/what-swarming-agile) – Техника, при которой вся команда концентрируется на одной задаче до ее завершения. Используется для решения сложных или срочных задач, когда требуется совместное усилие.
- [**Mob Programming**](https://mobprogramming.org/) – Развитие Pair Programming: вся команда разрабатывает код совместно, используя один компьютер. Каждый участник вносит вклад, чередуясь за клавиатурой.
- [**ZBP**](https://www.agilealliance.org/glossary/zero-bug-policy/) –  Стратегия, при которой команда не откладывает исправление багов на потом, а устраняет их сразу после обнаружения. Позволяет избежать накопления технического долга.

---

## 3. Командные процессы и Agile-практики
### 📌 Управление бэклогом и User Stories
- [**USM**](https://www.jpattonassociates.com/user-story-mapping/) – Метод визуального представления пользовательских историй в виде карты, отражающей путь пользователя. Позволяет приоритизировать работу над фичами, улучшает понимание требований.
- [**USH**](https://www.agilealliance.org/glossary/user-story-hamburger/) – Метод детализации пользовательских историй, представляющий их в виде "гамбургера" с разными уровнями детализации. Помогает команде детально разобрать сценарии использования.
- [**SPIDR**](https://www.scrum.org/resources/blog/spidr-refinement-pattern) – Фреймворк для разделения сложных историй на более мелкие, чтобы они соответствовали INVEST-принципам. Используется для эффективной декомпозиции.
- [**INVEST**](https://xp123.com/articles/invest-in-good-stories-and-smart-tasks/) – Принципы хорошей пользовательской истории: независимая, обсуждаемая, ценная, оцениваемая, небольшая, тестируемая.

### 🏆 Приоритизация задач и фич
- [**MoSCoW**](https://www.agilebusiness.org/page/ProjectFramework_MoSCoW) – Метод приоритизации задач на основе 4 категорий: Must, Should, Could, Won’t. Помогает определить, какие фичи обязательны, а какие могут быть отложены.
- [**WSJF**](https://scaledagileframework.com/wsjf/) – Метод взвешенной приоритизации задач, основанный на стоимости задержки и усилиях на реализацию. Используется в SAFe.
- **[ICE](https://www.productplan.com/glossary/ice-scoring-model/)/[RICE](https://www.intercom.com/blog/rice-simple-prioritization-for-product-managers/)** – Два похожих метода приоритизации задач по критериям воздействия (Impact), уверенности (Confidence), затрат (Effort). В RICE добавлен параметр Reach (охват).
- [**Kano Model**](https://foldingburritos.com/kano-model/) – Метод оценки функций продукта на основе их влияния на удовлетворенность пользователей. Разделяет фичи на базовые, желательные и восхищающие.

### 🔄 Agile-практики
- [**Three Amigos**](https://www.agilealliance.org/glossary/three-amigos/) – Встреча аналитика, разработчика и тестировщика для уточнения требований перед началом разработки. Позволяет избежать недоразумений и улучшает качество спецификаций.
- [**Big Room Planning**](https://www.scaledagileframework.com/pi-planning/) – Масштабное командное планирование, когда все участники продукта (разработчики, тестировщики, аналитики, стейкхолдеры) собираются в одном месте для согласования приоритетов.
- [**Sprint Review**](https://www.scrum.org/resources/sprint-review) – Обзор результатов спринта с демонстрацией выполненной работы заказчикам и обсуждением обратной связи.
- [**Flow Metrics**](https://kanbanize.com/lean-management/value-stream/flow-metrics) – Метод измерения эффективности потока задач в разработке. Позволяет выявлять узкие места и оптимизировать процессы.
- [**Slack Time**](https://www.agilealliance.org/glossary/slack-time/) – Практика выделения буферного времени между задачами, чтобы разработчики могли заниматься обучением, рефакторингом или исследовательской работой.

---

## 4. People Management и развитие сотрудников
- [**1-to-1**](https://www.manager-tools.com/) – Индивидуальные встречи
- [**SBI**](https://www.mindtools.com/pages/article/situation-behavior-impact.htm) – Модель обратной связи, включающая три элемента: Situation (ситуация), Behavior (поведение), Impact (влияние). Позволяет давать объективную и конструктивную обратную связь.
- [**GROW**](https://www.mindtools.com/pages/article/newLDR_89.htm) – Коучинговая модель, которая помогает сотрудникам достигать целей через структуру: Goal (цель), Reality (текущая ситуация), Options (возможности), Will (действия).
- [**STAR**](https://www.interviewgold.com/advice/star-technique/) – Метод интервьюирования, позволяющий оценить кандидата через рассказ о реальных кейсах по схеме: Situation (ситуация), Task (задача), Action (действия), Result (результат).
- [**SPARK**](https://www.gallup.com/cliftonstrengths/en/253715/strengths-coaching.aspx) – Подход к коучингу и развитию сотрудников, ориентированный на Strengths (сильные стороны), Possibilities (возможности), Aspirations (стремления), Results (результаты), Key actions (ключевые шаги).
- [PIP (Performance Improvement Plan)](https://www.shrm.org/resourcesandtools/tools-and-samples/hr-qa/pages/performanceimprovementplans.aspx) – План улучшения производительности, который создается для сотрудника, если его работа не соответствует ожиданиям. Он включает конкретные цели, сроки и шаги, необходимые для улучшения результатов.
- [**IDP**](https://www.ccl.org/articles/leading-effectively-articles/individual-development-plan-templates-tools/) – Индивидуальный план развития сотрудника, включающий цели, навыки для развития и шаги для их достижения.
- [**TMA**](https://www.tma-method.com/en/)  – Метод оценки талантов, основанный на анализе способностей, мотивации и поведенческих паттернов сотрудников.
- [**MBTI**](https://www.myersbriggs.org/) – Метод типирования личности, разделяющий людей на 16 психологических типов на основе предпочтений в мышлении и поведении.
- [**DISC**](https://www.discprofile.com/what-is-disc/) – Система оценки поведенческих стилей сотрудников по четырем категориям: Dominance (доминирование), Influence (влияние), Steadiness (устойчивость), Conscientiousness (сознательность). Используется для улучшения коммуникации и формирования команд.

---

## 5. Стратегическое управление и метрики
### 🎯 Постановка целей и стратегическое планирование
- [**OKR**](https://www.whatmatters.com/) – Метод постановки целей, основанный на четких измеримых результатах. Используется в компаниях для согласования стратегических целей с повседневными задачами команд. Позволяет быстро адаптироваться к изменениям и фокусироваться на достижении ключевых показателей.
- [**SMART**](https://www.mindtools.com/pages/article/smart-goals.htm) – Фреймворк формулировки целей, где каждая цель должна быть: Specific (конкретная), Measurable (измеримая), Achievable (достижимая), Relevant (релевантная), Time-bound (ограниченная во времени). Позволяет четко определить желаемый результат.
- [**OGSM**](https://onstrategyhq.com/resources/what-is-ogsm/) – Метод стратегического планирования, разделяющий процесс на цели (Objectives), измеримые показатели (Goals), стратегии (Strategies) и метрики (Measures).
- [**Big Room Planning (BRP)**](https://www.scaledagileframework.com/pi-planning/) – Масштабное командное планирование, когда все команды, работающие над одним продуктом, синхронизируют цели и задачи. Используется в SAFe и крупных организациях.

### 📊 Метрики и аналитика
- [**Balanced Scorecard (BSC)**](https://balancedscorecard.org/) – Метод управления эффективностью организации, включающий четыре перспективы: финансовая, клиентская, внутренние бизнес-процессы, обучение и развитие. Позволяет следить за стратегическим развитием компании.
- [**SWOT**](https://www.mindtools.com/pages/article/newTMC_05.htm) – Анализ стратегии, выявляющий сильные и слабые стороны компании, а также внешние возможности и угрозы. Используется для стратегического планирования и конкурентного анализа.
- [**TOWS**](https://corporatefinanceinstitute.com/resources/strategy/tows-matrix-guide/) – Инструмент стратегического анализа, расширяющий SWOT за счет объединения внутренних факторов (сильных и слабых сторон) с внешними (возможностями и угрозами). Позволяет выявить конкретные стратегии.
- [**STEP**](https://pestleanalysis.com/step-analysis/) –  Анализ среды, влияющей на бизнес. Помогает понять макроэкономические тренды и адаптировать стратегию компании.
- [**CSF**](https://www.mindtools.com/pages/article/newPPM_82.htm) – Метод выявления критических факторов успеха организации. Позволяет определить, какие элементы стратегии являются ключевыми для достижения целей.
- [**KPI**](https://www.klipfolio.com/resources/articles/what-is-a-key-performance-indicator) – Ключевые показатели эффективности, используемые для оценки работы сотрудников, отделов и всей компании. Позволяет измерять успех и выявлять проблемные зоны.

---

## 6. Принятие решений
### 📌 Фреймворки и техники для брейншторма
- [**LDJ**](https://www.designpilot.info/techniken/tool-368-lightning-decision-jam-ldj/) – Lightning Decision Jam
- [**SCAMPER**](https://www.mindtools.com/pages/article/newCT_02.htm) – Substitute, Combine, Adapt, Modify, Put to Another Use, Eliminate, Reverse
- [**Brainwriting**](https://www.sessionlab.com/methods/brainwriting) – Тихий брейншторм
- [**6-3-5**](https://www.creativehuddle.co.uk/brainwriting-635) – 6 участников, 3 идеи, 5 итераций
- [**Event Storming**](https://www.eventstorming.com/) – Визуальное моделирование событий

### 🏗 Принятие решений и анализ альтернатив
- [**Decision Matrix (DM)**](https://www.mindtools.com/pages/article/newTED_03.htm) – Матрица решений
- [**RACI**](https://www.projectmanager.com/blog/raci-chart-definition) – Responsible, Accountable, Consulted, Informed – Responsible, Accountable, Consulted, Informed
- [**DACI**](https://www.atlassian.com/team-playbook/plays/daci) – Driver, Approver, Contributor, Informed
- [**FMEA**](https://asq.org/quality-resources/fmea) – Failure Modes and Effects Analysis
- [**OODA**](https://www.artofmanliness.com/skills/manly-know-how/ooda-loop/)  – Observe, Orient, Decide, Act
- [**PDCA**](https://www.mindtools.com/pages/article/newPPM_89.htm) – Plan, Do, Check, Act
- [**ICE**](https://www.productplan.com/glossary/ice-scoring-model/) / [**RICE**](https://www.intercom.com/blog/rice-simple-prioritization-for-product-managers/) – Приоритизация
- [**DPH Framework**](https://www.linkedin.com/pulse/how-use-dph-framework-structured-decision-making-marcus-purvis/) – LinkedIn DPH

---

## 7. Ретроспективы
- [**4LS**](https://retromat.org/en/?id=74) – Loved, Learned, Lacked, Longed for
- [**Mad Sad Glad**](https://retromat.org/en/?id=19) – Анализ эмоций команды
- [**Sailboat**](https://www.funretrospectives.com/sailboat/) – Визуальная ретроспектива
- [**Hot Air Balloon**](https://www.funretrospectives.com/hot-air-balloon/) – Еще одна метафорическая техника ретро
- [**Start, Stop, Continue**](https://www.atlassian.com/team-playbook/plays/start-stop-continue) – Простая и эффективная техника ретро
