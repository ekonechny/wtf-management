# OKR, 4LS, OMG: Справочник WTF-практик технического менеджера 🤯📊
*Когда аббревиатур больше, чем времени на проект...*

Добро пожаловать в **справочник WTF-практик технического менеджера**.  
Здесь собраны методы, фреймворки и техники, которыми пользуются технические менеджеры, архитекторы и тимлиды.

## 1. Архитектура и дизайн систем
### 🏗 Визуализация и моделирование
- [**C4**](https://c4model.com/) — Модель архитектурного проектирования, состоящая из четырех уровней (Контекст, Контейнер, Компонент, Код). Помогает визуализировать сложные системы и их взаимосвязи.
- [**UML**](https://www.uml.org/) — Унифицированный язык моделирования, используемый для описания структурных и поведенческих аспектов системы. Поддерживает различные диаграммы, такие как диаграммы классов, последовательностей и состояний.
- [**DFD**](https://www.visual-paradigm.com/guide/data-flow-diagram/what-is-data-flow-diagram/) — Диаграмма потоков данных, которая помогает анализировать, как данные перемещаются в системе, определяя входные и выходные точки.
- [**4+1**](https://en.wikipedia.org/wiki/4%2B1_architectural_view_model) – Архитектурная модель, описывающая систему с пяти точек зрения: логическая, процессная, физическая, разработческая и сценарии использования.
- [**R&W**](https://www.viewpoints-and-perspectives.info/) — Методология представления архитектуры через точки зрения, включая эксплуатацию, безопасность и производительность.
- [**ERD**](https://www.lucidchart.com/pages/entity-relationship-diagram) — Диаграмма сущность-связь, используется для моделирования данных и их отношений в базе данных.
- [**SADT**](https://www.visual-paradigm.com/guide/data-flow-diagram/structured-analysis-and-design-technique/) — Методика структурного анализа и проектирования, используется для описания процессов и их взаимодействий в системе.
- [**BPML**](https://en.wikipedia.org/wiki/Business_Process_Modeling_Language) — Язык моделирования бизнес-процессов, который позволяет описывать бизнес-логику и потоки работ.
- [**BPMN**](https://www.bpmn.org/) — Графический стандарт для моделирования бизнес-процессов, используемый для описания рабочих потоков с четкой семантикой.

### 📝 Документирование решений и процессов
- [**ADR** – Architecture Decision Record](https://adr.github.io/) — Структурированный формат записи архитектурных решений, фиксирующий их причины и последствия.
- [**Arc42**](https://arc42.org/) – Шаблон архитектурной документации, позволяющий структурировано описывать архитектуру системы.
- [**RFC**](https://datatracker.ietf.org/) – Request for Comments — метод формализации и обсуждения технических решений.
- [**TAM**](https://pubs.opengroup.org/togaf-standard/architecture-models/) – Technical Architecture Model — методология проектирования архитектуры организации.
- [**SAD**](https://www.sei.cmu.edu/research-capabilities/software-architecture/) – Software Architecture Document — Документ, содержащий описание архитектуры системы и ее компонентов.
- [**LDJ**](https://ajsmart.com/ldj) – Lightning Decision Jam — методика фасилитации для быстрого принятия архитектурных решений.
- [**TAR** – Technical Architecture Review](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=4965) – Метод оценки архитектуры для выявления слабых мест и потенциальных улучшений.
- [**Event Storming**](https://www.eventstorming.com/) – Визуальная фасилитационная техника, используемая для анализа и моделирования сложных бизнес-процессов через события. Участники стикерами отмечают ключевые события в системе, выявляя взаимосвязи и узкие места. Помогает глубже понять бизнес-домен и улучшить архитектуру системы.

### 🏗 Фреймворки для обсуждения архитектурных решений
- [**TDDM** – Top-Down Decision Making](https://www.researchgate.net/publication/260853898_Top-down_and_bottom-up_decision_processes_in_arrival_time_decisions) — Метод принятия решений сверху вниз, обеспечивающий стратегическое управление архитектурой.
- [**BFD** – Big Freaking Diagram](https://www.complexdiagrams.com/) — Концепция визуализации архитектуры больших систем.
- [**DDD** – Domain-Driven Design](https://martinfowler.com/bliki/DomainDrivenDesign.html) — Методология проектирования ПО, ориентированная на бизнес-домен.
- [**FEA**](https://www.enterprise-architecture.info/EA_Feasibility.htm) – Future Enterprise Architecture — Метод управления архитектурой предприятия с акцентом на будущее развитие.
- [**ESA**](https://www.gartner.com/en/information-technology/glossary/enterprise-solution-architecture) – Enterprise Solution Architecture — Подход к построению корпоративных решений на основе архитектурных принципов.
- [**SABSA**](https://sabsa.org/) – Security Architecture Framework — Методология проектирования архитектуры безопасности.

---

## 2. Разработка и качество кода

### 👯 Collaborative programming
- [**Pair Programming**](articles/collaborative-programming.md#pair-debugging) – Метод совместного программирования, при котором два разработчика работают за одним компьютером: один пишет код, другой рецензирует в реальном времени. Улучшает качество кода, способствует передаче знаний и снижает количество багов.
- [**Swarming**](articles/collaborative-programming.md#swarming) – Техника, при которой вся команда концентрируется на одной задаче до ее завершения. Используется для решения сложных или срочных задач, когда требуется совместное усилие.
- [**Mob Programming**](articles/collaborative-programming.md#mob-programming) – Развитие Pair Programming: вся команда разрабатывает код совместно, используя один компьютер. Каждый участник вносит вклад, чередуясь за клавиатурой.
- [**Ping Pong Programming**](articles/collaborative-programming.md#ping-pong-programming) – Вариант Pair Programming, основанный на TDD. Один разработчик пишет тест, а другой реализует минимальный код для его прохождения. Затем роли меняются. Такой подход способствует структурированному процессу разработки и улучшению качества кода.
- [**Code Dojo**](articles/collaborative-programming.md#code-dojo) – Формат коллективного обучения, в котором команда решает программные задачи в структурированном формате. Может проходить в виде индивидуальных упражнений (Kata) или совместной работы (Randori), что способствует развитию навыков и обмену знаниями.
- [**Ensemble Programming**](articles/collaborative-programming.md#ensemble-programming) – Расширенная версия Mob Programming, в которой роли распределяются более гибко, а команда взаимодействует динамично, адаптируясь к текущим задачам. Позволяет вовлекать разработчиков, тестировщиков и аналитиков в процесс, улучшая креативность решений и качество кода.
- [**Pair Debugging**](articles/collaborative-programming.md#pair-debugging) – Методика, при которой два разработчика совместно работают над поиском и устранением багов. Один человек управляет кодом и инструментами отладки, а второй анализирует проблему, предлагает гипотезы и оценивает возможные решения. Роли периодически меняются, что помогает быстрее находить ошибки и улучшает процесс отладки.
- [**Shadowing**](articles/collaborative-programming.md#shadowing) – Метод передачи знаний, при котором менее опытный сотрудник наблюдает за работой более опытного, изучая процессы, инструменты и решения. Может использоваться для онбординга новых сотрудников, обмена опытом и подготовки будущих специалистов.

### Other
- [**ZBP**](https://www.agilealliance.org/glossary/zero-bug-policy/) –  Стратегия, при которой команда не откладывает исправление багов на потом, а устраняет их сразу после обнаружения. Позволяет избежать накопления технического долга.

---

## 3. Командные процессы и Agile-практики

### 📌 Управление бэклогом и User Stories
- [**USM**](articles/user-story.md#usm) – Метод визуального представления пользовательских историй в виде карты, отражающей путь пользователя. Позволяет приоритизировать работу над фичами, улучшает понимание требований.
- [**USH**](articles/user-story.md#ush) – Метод детализации пользовательских историй, представляющий их в виде "гамбургера" с разными уровнями детализации. Помогает команде детально разобрать сценарии использования.
- [**INVEST**](articles/user-story.md#invest) – Принципы хорошей пользовательской истории: независимая, обсуждаемая, ценная, оцениваемая, небольшая, тестируемая.
- [**SPIDR**](articles/user-story.md#spidr) – Фреймворк для разделения сложных историй на более мелкие, чтобы они соответствовали INVEST-принципам. Используется для эффективной декомпозиции.
- [**Feature Slicing**](articles/user-story.md#feature-slicing) – Метод разбиения функциональности на логические части, такие как сценарии использования, шаги процесса, уровни сложности, роли пользователей или типы данных. Позволяет внедрять фичи поэтапно.
- [**Workflow Steps**](articles/user-story.md#workflow-steps) – Разделение пользовательской истории по последовательным шагам процесса. Используется, когда система работает по четкому сценарию, включающему несколько этапов взаимодействия.
- [**Walking Skeleton**](articles/user-story.md#walking-skeleton) – Метод разработки, при котором создается минимально работоспособная версия системы, охватывающая весь жизненный цикл продукта с базовой функциональностью. Позволяет рано протестировать архитектуру.
- [**Three Cs**](articles/user-story.md#three-cs) – Модель работы с пользовательскими историями, включающая карточку (Card), обсуждение (Conversation) и подтверждение (Confirmation). Обеспечивает гибкость в формулировке и реализации требований.

### 🏆 Приоритизация задач и фич
- [**MoSCoW**](https://www.agilebusiness.org/page/ProjectFramework_MoSCoW) – Метод приоритизации задач на основе 4 категорий: Must, Should, Could, Won’t. Помогает определить, какие фичи обязательны, а какие могут быть отложены.
- [**WSJF**](https://scaledagileframework.com/wsjf/) – Метод взвешенной приоритизации задач, основанный на стоимости задержки и усилиях на реализацию. Используется в SAFe.
- **[ICE](https://www.productplan.com/glossary/ice-scoring-model/)/[RICE](https://www.intercom.com/blog/rice-simple-prioritization-for-product-managers/)** – Два похожих метода приоритизации задач по критериям воздействия (Impact), уверенности (Confidence), затрат (Effort). В RICE добавлен параметр Reach (охват).
- [**Kano Model**](https://foldingburritos.com/kano-model/) – Метод оценки функций продукта на основе их влияния на удовлетворенность пользователей. Разделяет фичи на базовые, желательные и восхищающие.

### 🔄 Agile-практики
- [**Three Amigos**](https://www.agilealliance.org/glossary/three-amigos/) – Встреча аналитика, разработчика и тестировщика для уточнения требований перед началом разработки. Позволяет избежать недоразумений и улучшает качество спецификаций.
- [**Big Room Planning**](https://www.scaledagileframework.com/pi-planning/) – Масштабное командное планирование, когда все участники продукта (разработчики, тестировщики, аналитики, стейкхолдеры) собираются в одном месте для согласования приоритетов.
- [**Sprint Review**](https://www.scrum.org/resources/sprint-review) – Обзор результатов спринта с демонстрацией выполненной работы заказчикам и обсуждением обратной связи. [Мой вариант](articles/sprint-review.md) проведения Sprint Review.
- [**Flow Metrics**](https://kanbanize.com/lean-management/value-stream/flow-metrics) – Метод измерения эффективности потока задач в разработке. Позволяет выявлять узкие места и оптимизировать процессы.
- [**Slack Time**](https://www.agilealliance.org/glossary/slack-time/) – Практика выделения буферного времени между задачами, чтобы разработчики могли заниматься обучением, рефакторингом или исследовательской работой.

---

## 4. People Management и развитие сотрудников

### Общее
- [**1-to-1**](https://www.manager-tools.com/) – Индивидуальные встречи
- [**SPARK**](https://www.gallup.com/cliftonstrengths/en/253715/strengths-coaching.aspx) – Подход к коучингу и развитию сотрудников, ориентированный на Strengths (сильные стороны), Possibilities (возможности), Aspirations (стремления), Results (результаты), Key actions (ключевые шаги).
- [**IDP**](https://www.ccl.org/articles/leading-effectively-articles/individual-development-plan-templates-tools/) – Индивидуальный план развития сотрудника, включающий цели, навыки для развития и шаги для их достижения.
- [**TMA**](https://www.tma-method.com/en/)  – Метод оценки талантов, основанный на анализе способностей, мотивации и поведенческих паттернов сотрудников.
- [**MBTI**](https://www.myersbriggs.org/) – Метод типирования личности, разделяющий людей на 16 психологических типов на основе предпочтений в мышлении и поведении.
- [**DISC**](https://www.discprofile.com/what-is-disc/) – Система оценки поведенческих стилей сотрудников по четырем категориям: Dominance (доминирование), Influence (влияние), Steadiness (устойчивость), Conscientiousness (сознательность). Используется для улучшения коммуникации и формирования команд.
- [**PIP**](https://www.shrm.org/resourcesandtools/tools-and-samples/hr-qa/pages/performanceimprovementplans.aspx) – План улучшения производительности, который создается для сотрудника, если его работа не соответствует ожиданиям. Он включает конкретные цели, сроки и шаги, необходимые для улучшения результатов.
- [**TMM**](https://github.com/avito-tech/playbook/blob/master/avito-developer-practice.md#team-maturity-model) - Модель зрелости команд, используемая выравнивания процессов в компании.

### **📌 Фреймворки обратной связи**
- [**SBI**](articles/feedback-model.md#1-sbi-situation-behavior-impact) – Модель обратной связи, включающая три элемента: **Situation** (ситуация), **Behavior** (поведение), **Impact** (влияние). Позволяет давать объективную и конструктивную обратную связь.
- [**SBI-BI**](articles/feedback-model.md#2-sbi-bi-sbi--behavior-improvement) – Расширенная версия SBI, добавляющая **Behavior Improvement** (улучшение поведения), что делает обратную связь не только аналитической, но и направленной на развитие.
- [**BOOST**](articles/feedback-model.md#3-boost-behavior-outcome-objective-suggestion-takeaway) – Фокусируется на **развитии сотрудников**. Включает **Behavior** (поведение), **Outcome** (результат), **Objective** (цель), **Suggestion** (предложение) и **Takeaway** (вывод).
- [**BEER**](articles/feedback-model.md#4-beer-behavior-effect-expectation-result) – Структурированная модель, состоящая из **Behavior** (поведение), **Effect** (эффект), **Expectation** (ожидание), **Result** (результат). Подходит для конструктивной критики.
- [**STAR**](articles/feedback-model.md#5-star-situation-task-action-result) – Используется в интервьюировании и обратной связи. Включает **Situation** (ситуация), **Task** (задача), **Action** (действие), **Result** (результат).
- [**Feedback Sandwich**](articles/feedback-model.md#6-feedback-sandwich-сэндвич-обратной-связи) – Метод «сэндвича»: позитивный комментарий → конструктивная критика → позитивный комментарий. Используется для смягчения негативной обратной связи.
- [**COIN**](articles/feedback-model.md#7-coin-context-observation-impact-next-steps) – Четкая структурированная модель: **Context** (контекст), **Observation** (наблюдение), **Impact** (влияние), **Next steps** (следующие шаги).
- [**GROW Model**](articles/feedback-model.md#8-grow-model-goal-reality-options-will) – Коучинговая модель, включающая **Goal** (цель), **Reality** (реальность), **Options** (варианты), **Will** (действия).
- [**BIFF**](articles/feedback-model.md#9-biff-behavior-impact-feelings-future) – Добавляет эмоциональный аспект: **Behavior** (поведение), **Impact** (влияние), **Feelings** (чувства), **Future** (будущее).
- [**DESC**](articles/feedback-model.md#10-desc-describe-express-specify-consequences) – Используется в конфликтных ситуациях: **Describe** (описание), **Express** (выражение эмоций), **Specify** (уточнение ожиданий), **Consequences** (последствия).
- [**The Stanford Method**](articles/feedback-model.md#11-the-stanford-method) – Гибкая модель, адаптируемая под конкретную ситуацию, с акцентом на **диалог и поиск решений**.
- [**SKS**](articles/feedback-model.md#12-sks-stop-keep-start) – Метод ретроспективы: **Stop** (что прекратить?), **Keep** (что продолжать?), **Start** (что начать?).
- [**SAID**](articles/feedback-model.md#13-said-situation-action-impact-desired-outcome) – Основан на результатах: **Situation** (ситуация), **Action** (действие), **Impact** (влияние), **Desired outcome** (желаемый результат).
- [**CEDAR**](articles/feedback-model.md#14-cedar-context-examples-diagnosis-actions-review) – Глубокий анализ с примерами: **Context** (контекст), **Examples** (примеры), **Diagnosis** (диагностика), **Actions** (действия), **Review** (обзор).
- [**McKinsey Feedback Model**](articles/feedback-model.md#15-mckinsey-feedback-model) – Используется в стратегическом управлении, сочетает **анализ текущей ситуации, рекомендации и оценку эффективности**.
- [**PEP**](articles/feedback-model.md#16-pep-positive-example-plan) – Мотивационная модель: **Positive** (позитив), **Example** (пример), **Plan** (план).
- [**AID**](articles/feedback-model.md#17-aid-action-impact-desired-change) – Четкая структура изменений: **Action** (действие), **Impact** (влияние), **Desired Change** (желаемое изменение).
- [**BEEF**](articles/feedback-model.md#18-beef-behavior-effect-emotion-future) – Добавляет эмоциональную составляющую: **Behavior** (поведение), **Effect** (эффект), **Emotion** (эмоции), **Future** (будущее).

### **🚨 Фреймворки для увольнения**
- [**BPR**](articles/feedback-model.md#1-bpr-brief-positive-respectful) – Быстрое и уважительное увольнение: **Brief** (краткость), **Positive** (подчеркнуть позитив), **Respectful** (проявить уважение).
- [**DARE**](articles/feedback-model.md#2-dare-describe-acknowledge-reaffirm-explain) – Прозрачное увольнение: **Describe** (описание ситуации), **Acknowledge** (признание вклада), **Reaffirm** (подтверждение решения), **Explain** (объяснение дальнейших шагов).
- [**LAST**](articles/feedback-model.md#3-last-listen-acknowledge-solve-thank) – Увольнение с поддержкой: **Listen** (выслушать реакцию), **Acknowledge** (признать чувства), **Solve** (предложить помощь), **Thank** (поблагодарить).
- [**RADAR**](articles/feedback-model.md#4-radar-recognize-assess-decide-act-review) – Подготовка к увольнению: **Recognize** (распознать проблему), **Assess** (оценить альтернативы), **Decide** (принять решение), **Act** (уволить), **Review** (анализ последствий).
- [**CARE**](articles/feedback-model.md#5-care-clarify-acknowledge-respond-exit-strategy) – Минимизация конфликта при увольнении: **Clarify** (четкость формулировки), **Acknowledge** (сочувствие), **Respond** (ответы на вопросы), **Exit Strategy** (план выхода).

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
- [**LDJ**](https://www.designpilot.info/techniken/tool-368-lightning-decision-jam-ldj/) – Фасилитационная техника для быстрого группового принятия решений, основанная на структурированном процессе мозгового штурма. Участники сначала генерируют проблемы, затем голосуют за наиболее важные, предлагают решения и создают конкретный план действий, что помогает избежать долгих обсуждений и быстро находить оптимальные решения.
- [**SCAMPER**](https://www.mindtools.com/pages/article/newCT_02.htm) – Техника креативного мышления и генерации идей, основанная на семи вопросах-модификациях: Substitute (замени), Combine (объедини), Adapt (адаптируй), Modify (измени), Put to another use (используй иначе), Eliminate (исключи), Reverse (изменение порядка). Помогает находить нестандартные решения и улучшать продукты или процессы.
- [**Brainwriting**](https://www.sessionlab.com/methods/brainwriting) – Альтернатива классическому мозговому штурму, при которой участники записывают идеи на бумаге или в цифровом формате, а затем передают их другим для развития. Такой метод снижает давление в группе, позволяет генерировать больше идей и дает возможность каждому высказаться.
- [**6-3-5**](https://www.creativehuddle.co.uk/brainwriting-635) – Метод мозгового штурма, при котором 6 участников записывают 3 идеи за 5 минут, затем передают свои записи следующему участнику, который развивает идеи дальше. Процесс повторяется несколько раундов, что позволяет коллективно генерировать и улучшать решения за короткое время.

### 🏗 Принятие решений и анализ альтернатив
- [**Decision Matrix (DM)**](https://www.mindtools.com/pages/article/newTED_03.htm) – Метод принятия решений, который помогает объективно сравнивать варианты на основе множества критериев. Каждому критерию присваивается вес, после чего оцениваются альтернативы, что упрощает выбор наилучшего варианта.
- [**RACI**](https://www.projectmanager.com/blog/raci-chart-definition) – Матрица распределения ответственности, которая четко определяет, кто отвечает за выполнение задачи (Responsible), кто несет окончательную ответственность (Accountable), кого нужно консультировать (Consulted) и кого информировать (Informed). Помогает устранить неопределенность в ролях и улучшить коммуникацию в команде.
- [**DACI**](https://www.atlassian.com/team-playbook/plays/daci) – Фреймворк принятия решений, который определяет роли участников: Driver (ведущий, координирует процесс), Approver (принимающий решение), Contributor (дающий экспертное мнение) и Informed (информируемый). Помогает ускорить процесс принятия решений и избежать размытости ответственности.
- [**FMEA**](https://asq.org/quality-resources/fmea) – Метод анализа видов и последствий отказов, который помогает выявить потенциальные ошибки в системе, оценить их влияние и разработать меры предотвращения. Используется для повышения надежности процессов и минимизации рисков.
- [**OODA**](https://www.artofmanliness.com/skills/manly-know-how/ooda-loop/) – Цикл принятия решений, разработанный для быстрой адаптации в динамичной среде. Включает этапы: наблюдение (Observe), ориентация (Orient), принятие решения (Decide) и действие (Act), позволяя оперативно реагировать на изменения и опережать конкурентов.
- [**PDCA**](https://www.mindtools.com/pages/article/newPPM_89.htm) – Циклический процесс непрерывного улучшения, включающий этапы: планирование (Plan), выполнение (Do), проверку (Check) и коррекцию (Act). Используется для оптимизации бизнес-процессов, повышения качества и управления изменениями.
- [**ICE**](https://www.productplan.com/glossary/ice-scoring-model/) / [**RICE**](https://www.intercom.com/blog/rice-simple-prioritization-for-product-managers/) – Техники для приоритизации. ICE (Impact, Confidence, Ease) – Метод приоритизации задач, оценивающий их по трем критериям: влияние (Impact), уверенность в результате (Confidence) и простота реализации (Ease). Помогает быстро определить, какие инициативы принесут наибольшую пользу при наименьших затратах. RICE (Reach, Impact, Confidence, Effort) – Улучшенная версия ICE, добавляющая параметр охват аудитории (Reach). Используется в продуктовой разработке и управлении бэклогом для выбора наиболее ценных задач с учетом масштаба влияния.
- [**DPH Framework**](https://www.linkedin.com/pulse/how-use-dph-framework-structured-decision-making-marcus-purvis/) – Метод принятия решений, учитывающий три ключевых аспекта: данные (Data), процессы (Process) и человеческий фактор (Human). Позволяет сбалансированно оценивать ситуацию, принимая во внимание как объективные показатели, так и влияние людей на результаты.
- [**Traction Map**](articles/traction-map.md) – Методика структурированного решения сложных проблем, основанная на анализе первопричин, пошаговом устранении симптомов и итеративном тестировании эффективности решений с постоянной обратной связью.

---

## 7. Ретроспективы
- [**4LS**](https://retromat.org/en/?id=74) – Метод ретроспективы, который помогает команде оценить прошедший спринт через четыре аспекта: что понравилось, чему научились, чего не хватало и что хотелось бы добавить. Используется для выявления позитивных моментов, зон роста и улучшения процессов.
- [**Mad Sad Glad**](https://retromat.org/en/?id=19) – Техника ретроспективы, в которой команда оценивает прошедший спринт через три эмоции: что вызвало раздражение (Mad), что расстроило (Sad) и что порадовало (Glad).
- [**Sailboat**](https://www.funretrospectives.com/sailboat/) – Визуальная техника ретроспективы, где команда представляет проект в виде парусника: ветер символизирует то, что помогает двигаться вперед, якоря – что замедляет, скалы – риски, а остров – цель. Помогает команде выявить факторы успеха, препятствия и потенциальные угрозы.
- [**Hot Air Balloon**](https://www.funretrospectives.com/hot-air-balloon/) – Метафорическая техника ретроспективы, где команда представляет проект в виде воздушного шара: горячий воздух (что нас поднимает), балласт (что нас тормозит) и грозовые тучи (возможные риски). Помогает анализировать мотивацию команды, выявлять препятствия и искать пути улучшения.
- [**Start, Stop, Continue**](https://www.atlassian.com/team-playbook/plays/start-stop-continue) – Простая и эффективная техника ретроспективы, в которой команда определяет, что стоит начать делать (Start), что следует прекратить (Stop) и что уже работает хорошо и нужно продолжать (Continue). Помогает быстро выявить улучшения и зафиксировать успешные практики.
