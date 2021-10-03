# Процесс моделирования начального проектирования на основе предметной области

Этот процесс дает вам пошаговое руководство по изучению и практическому применению каждого аспекта проектирования на основе предметной области (DDD) - от ориентации на бизнес-модель организации до кодирования модели предметной области.

Использование этого процесса поможет вам выполнить каждый из основных этапов разработки программной системы с использованием DDD-мышления, чтобы вы могли сосредоточиться на своих бизнес-задачах и не быть перегруженными одновременным изучением DDD.

После того, как вы пройдете несколько итераций процесса, у вас будет основополагающая теория DDD и практический опыт, чтобы углубиться в DDD. Тогда вы сможете адаптировать и улучшить процесс в соответствии с вашими потребностями в любом контексте. В реальном проекте вы часто будете прыгать туда-сюда между этими шагами.

> Этот процесс предназначен для начинающих. Это не линейная последовательность шагов, которую вы должны стандартизировать в качестве наилучшей практики. Предметно-ориентированное проектирование - это эволюционный процесс проектирования, который требует непрерывной итерации по всем аспектам знаний и проектирования.

![Процесс моделирования DDD-стартера](resources/ddd-starter-modelling-process.jpg )

__навигация:__

* [Когда следует использовать процесс моделирования DDD-стартера?](#когда-использовать-процесс-моделирования-ddd-стартера)
* [Запуск нового проекта] (#запуск нового проекта)
* [Начало миграции на новое поле] (#начало миграции на новое поле)
* [Начало основной программы работы] (#начало основной программы работы)
* [Исследуйте Свой домен в поисках новых возможностей для обучения] (#исследуйте свой домен в поисках новых возможностей для обучения)
* [Оценить текущее состояние Вашего проекта] (#оценить текущее состояние вашего проекта)
* [Практика или изучение DDD] (#практика или изучение ddd)
* [Как адаптировать процесс?](#как-адаптировать-процесс)
* [Начать с совместного моделирования] (#начать с совместного моделирования)
* [Начните с оценки ИТ-ландшафта] (#начните с оценки ИТ-ландшафта)
* [Код до подтверждения границ архитектуры и команды] (#код до подтверждения границ архитектуры и команды)
* [Повторите шаги 2 (Обнаружение) - 6 (Организация) Перед переходом к 7 (Определение)] (#повторите шаги-2-обнаружение---6- организуйте-перед-переходом-к-7-определению)
* [Организуйте команды Перед проектированием контекстов] (#организуйте-команды-перед-проектированием-контекстов)
* [Определение и кодирование смешивания] (#определение и кодирование смешивания)
* [Процесс](#процесс)
* [Понять](#понять)
* [Открыть](#открыть)
* [Разложить](#разложить)
* [Подключиться](#подключиться)
* [Разработать стратегию] (#разработать стратегию)
* [Организовать](#организовать)
* [Определить](#определить)
* [Код](#код)
* [Участники](#участники)
* [Вклады и отзывы] (#вклады и отзывы)

## Когда следует использовать процесс моделирования DDD-стартера?

Если вы новичок в DDD или просто не знаете, с чего начать, этот процесс может снизить вашу когнитивную нагрузку. Он проведет вас через следующие сценарии и, возможно, другие:

### Запуск Нового проекта

В начале нового проекта количество вещей, о которых вам нужно подумать, может быть огромным. Одна или две итерации этого процесса могут помочь вам заложить основы.

### Начало миграции на новое поле

Прежде чем приступить к модернизации вашей устаревшей системы, несколько итераций этого процесса могут помочь вам получить важную информацию, необходимую для создания видения вашей целевой архитектуры.

### Начало основной программы работы

Когда запуск новой инициативы предполагает значительные инвестиции во многих командах, важно выполнить 8 этапов процесса. Этот процесс может провести вас через первые несколько итераций.

### Исследуйте Свой Домен в поисках новых возможностей для обучения

Разработка программного обеспечения - это процесс обучения. Вы можете применить процесс моделирования DDD Starter в любое время, чтобы раскрыть новые идеи, определить новые возможности или просто поделиться знаниями с командой.

### Оцените текущее состояние Вашего проекта

Этот процесс может стать основой для оценки того, насколько хорошо ваша текущая система соответствует предметной области и бизнес-модели.

### Реорганизация команд

Слабо связанная архитектура позволяет командам работать параллельно, не блокируясь. Слабосвязанная архитектура также должна быть согласована со связью в домене. Этот процесс поможет вам разработать архитектуру программного обеспечения и структуру команды, соответствующую вашему домену.

### Практика или изучение DDD

Этот процесс идеально подходит, когда вы новичок в DDD и хотите попрактиковаться или хотите научить других различным аспектам моделирования предметной области. Важно сообщить, что этот линейный процесс не является реалистичным процессом. Это всего лишь отправная точка для снижения когнитивной нагрузки, пока вы не будете уверены в DDD.

## Как адаптировать процесс?

Этот процесс можно настроить многими способами. В реальном проекте вы будете переключаться между всеми 8 шагами на основе новых знаний, которые вы получаете или должны получить.

Ниже приведены несколько причин для принятия решения о том, когда следует изменить порядок или переключиться между этапами.

### Начните с совместного моделирования

Если вы хотите, чтобы вся ваша команда немедленно начала сотрудничать, моделирование области, с которой они знакомы, может быть более удобным, чем разговор о бизнес-моделях и стратегии, которые им менее удобны.

### Начните с оценки ИТ-ландшафта

Прежде чем переходить к бизнес-видению и углубляться в предметную область, возможно, было бы лучше сначала визуализировать существующую архитектуру. Начните с шага 5 и составьте свой стратегический портфель, чтобы увидеть, с какими основными ограничениями вы столкнетесь.

### Код Перед подтверждением Архитектуры и границ команды

В некоторых проектах имеет смысл начать с написания кода раньше. Возможно, вам нужно предоставить MVP или домен настолько сложен, что необходимо создать модель в коде, прежде чем вы сможете рассмотреть архитектуру.

### Повторите шаги 2 (Обнаружение) - 6 (Организация), прежде чем перейти к 7 (Определение)

Прежде чем вы погрузитесь в определение отдельных ограниченных контекстов, может быть полезно несколько раз смоделировать домен и поискать различные способы разбиения вашей системы на поддомены и группы.

### Организуйте Команды Перед Проектированием Контекстов

Для многих проектов существуют организационные ограничения, которые мы должны учитывать. Если это так, вам следует рассмотреть возможность определения возможных командных структур, прежде чем разрабатывать архитектуры, которые вы никогда не сможете реализовать.

### Определение и кодирование смешивания

Шаги 7 (Определение) и 8 (код) могут выполняться одновременно. Это может произойти, когда вы кодируете ограниченный контекст, и идеи, которые вы получаете при написании кода, заставляют вас изменить высокоуровневый дизайн.

## Процесс

Процесс моделирования состоит из 8 этапов, которые представлены ниже.

Хорошим докладом, в котором дается обзор процесса в контексте типичных этапов проектирования социотехнических архитектур, является ["Социотехническая архитектура: совместное проектирование технической и организационной архитектуры для максимального воздействия"](https://www.youtube.com/watch?v=ekMPm78KFj0&feature=youtu.be&t=1820) [Эдуардо да Силва] (@emgsilva). Эдуардо группирует действия процесса и его 8 этапов в [четыре отдельных phases](https://speakerdeck.com/emgsilva/intro-to-sociotechnical-architecture-co-designing-technical-and-organizational-architecture-to-maximize-impact?slide=31) , а именно:
1. Выровняйте и поймите
2. Стратегическая архитектура
3. Стратегия и Организационный дизайн
4. Тактическая архитектура.


### Понять

Согласуйте наше внимание с бизнес-моделью организации, потребностями ее пользователей и ее краткосрочными, среднесрочными и долгосрочными целями.

Каждое решение, которое мы принимаем в отношении архитектуры, кода или организации, имеет последствия для бизнеса и пользователей. Для наиболее эффективного проектирования, создания и развития программных систем наши решения должны обеспечивать оптимальное воздействие на бизнес, которое может быть достигнуто только в том случае, если мы будем соответствовать бизнес-целям, а также поддерживать текущие и потенциальные будущие потребности пользователей.

Плохо спроектированная архитектура и/или границы могут оказать негативное влияние или даже сделать невозможным достижение этих целей.

В качестве отправной точки мы рекомендуем [Холст бизнес-модели](https://www.strategyzer.com/canvas/business-model-canvas ) для бизнес-перспективы [Сопоставление пользовательских историй](https://www.jpattonassociates.com/user-story-mapping /) для понимания точки зрения пользователя.

![Холст бизнес-модели] (ресурсы/бизнес-модель-холст.png)

#### Инструменты

- [Картирование воздействия](https://www.impactmapping.org /)
- [Холст бизнес-модели](https://www.strategyzer.com/canvas/business-model-canvas )
- [Холст стратегии продукта](https://melissaperri.com/blog/2016/07/14/what-is-good-product-strategy )
- [Отображение Уордли](https://learnwardleymapping.com /)
- [Сопоставление пользовательских историй](https://www.jpattonassociates.com/user-story-mapping /)

#### Кого привлекать

- Люди, которые разрабатывают, создают, тестируют программное обеспечение
- Люди, обладающие знаниями в предметной области
- Люди, которые понимают продукт и бизнес-стратегию
- Реальные конечные пользователи, а не только их представители в вашей организации

### Откройте для себя

Откройте для себя домен визуально и совместно.

Это самый важный аспект DDD. Вы не можете пропустить открытие. Если вся ваша команда не достигнет хорошего понимания предметной области, все программные решения будут ошибочными.

Распространение знаний о предметной области среди всей команды создаст общее понимание. Это позволяет разработчикам создавать программную систему, соответствующую предметной области, которая может быть более гибкой для учета будущих изменений в бизнесе.

Обеспечение распространения знаний о предметной области по всей команде позволяет ее членам вносить свой вклад в идеи по улучшению продукта.

> #### Discovery is Continuous
>
> Teams who are successful with DDD are practicing discovery techniques on a frequent basis. There is always more to learn about the domain.
>
> When first attempting discovery, a facilitator who is experienced with techniques like EventStorming can help a team to see the true benefits of discovery beyond a superficial level.
>
> We strongly encourage you to check out [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools).

As a starting point, we recommend [EventStorming](https://www.eventstorming.com/).

![EventStorming](resources/event_storming.jpeg)

#### Tools

- [Domain Storytelling](https://domainstorytelling.org/)
- [Example Mapping](https://cucumber.io/blog/bdd/example-mapping-introduction/)
- [EventStorming](https://www.eventstorming.com/)
- [User Journey Mapping](https://boagworld.com/audio/customer-journey-mapping/)
- [User Story Mapping](https://www.jpattonassociates.com/user-story-mapping/)

#### Who to Involve

- People who design, build, test software
- People who have domain knowledge
- People who understand product and business strategy
- People who understand the customers' needs and problems
- Real end users

### Decompose

Decompose the domain into sub-domains - loosely-coupled parts of the domain.

We decompose a large problem domain into sub-domains for a few key reasons:

- reduced cognitive load, so that we can reason about parts of the domain independently,
- give development teams autonomy, so that they can work on separate parts of the solution,
- identifying loose-coupling and high-cohesion in the domain which carries over to our software architecture and team structure.

As a starting point, we recommend carving up your event storm into sub-domains and [Context Maps](https://speakerdeck.com/mploed/visualizing-sociotechnical-architectures-with-context-maps).

![Sub-domains on an EventStorm](resources/event_storm_sub_domains.png)*Credit: Alberto Brandolini*

#### Tools

- [Business Capability Modelling](https://www.slideshare.net/trondhr/from-capabilities-to-services-modelling-for-businessit-alignment-v2)
- [Design Heuristics](https://www.dddheuristics.com/)
- [EventStorming with sub-domains](https://www.eventstorming.com/)
- [Independent Service Heuristics](https://github.com/TeamTopologies/Independent-Service-Heuristics)
- [Visualising Sociotechnical Architecture with Context Maps](https://speakerdeck.com/mploed/visualizing-sociotechnical-architectures-with-context-maps)

#### Who to Involve

- People who design, build, test software
- People who have domain knowledge

### Connect

Connect the sub-domains into a loosely-coupled architecture which fulfills end-to-end business use-cases.

It is imperative to not only decompose a large domain into parts but to also carefully design the interactions between those parts to minimise unwanted coupling and complexity. It is necessary to challenge the initial design by applying concrete use-cases to uncover hidden complexity.

As a starting point, we recommend [Domain Message Flow Modelling](https://github.com/ddd-crew/domain-message-flow-modelling).

![Domain Message Flow Modelling](resources/domain-message-flow.jpg)

#### Tools

- [Business Process Model and Notation](https://en.wikipedia.org/wiki/Business_Process_Model_and_Notation)
- [Domain Message Flow Modelling](https://github.com/ddd-crew/domain-message-flow-modelling)
- [Process Modelling EventStorming](https://www.eventstorming.com/)
- [Sequence Diagrams](https://en.wikipedia.org/wiki/Sequence_diagram)

#### Who to Involve

- People who design, build, test software
- People who have domain knowledge

### Strategize

Strategically map out your sub-domains to identify core domains: the parts of the domain which have the greatest potential for business differentiation or strategic significance.

Time and resources are limited, so understanding which parts of the domain to focus on is critical to delivering optimal business impact.

By analysing what your core domains are, you will have a better idea of how much quality and rigour is required to build each part of your system, and you'll be able to make highly-educated build vs buy vs outsource decisions.

As a starting point, we recommend [Core Domain Charts](https://github.com/ddd-crew/core-domain-charts).

![Core Domain Charts](resources/core-domain-chart.jpg)

#### Tools/Resources

- [Core Domain Charts](https://github.com/ddd-crew/core-domain-charts)
- [Purpose Alignment Model](https://www.informit.com/articles/article.aspx?p=1384195&seqNum=2)
- [Wardley Mapping](https://learnwardleymapping.com/)
- [Revisiting the Basics of Domain-Driven Design](https://vladikk.com/2018/01/26/revisiting-the-basics-of-ddd/)

#### Who to Involve

- People who understand product and business strategy
- People who design, build, test software
- People who have domain knowledge

### Organise

Organise autonomous teams that are optimised for fast flow and aligned with context boundaries.

Teams need to be organised to have autonomy, clear goals and sense of purpose. In order to do that we need to take into account organisational constraints, so that teams organise themselves for fast flow. 

> #### Team Self-organisation
>
> Organisation is not something that is done to teams, rather teams should be involved in the process of defining their boundaries, interactions, and responsibilities.
>
> Some companies like Red Gate Software empower and trust their teams to [fully organise themselves](https://medium.com/ingeniouslysimple/how-redgate-ran-its-first-team-self-selection-process-4bfac721ae2).

We can optimise how people collaborate with each other if we align teams with context boundaries. In order to right-size the teams we need to take into account available talent, cognitive load, communication overhead, and bus factor. 

As a starting point, we recommend visualising sociotechnical architecture with the [Context Maps](https://speakerdeck.com/mploed/visualizing-sociotechnical-architectures-with-context-maps). A brief overview of the most important patterns can be found under the [context-mapping](https://github.com/ddd-crew/context-mapping) GitHub Project.

![Context Map](resources/context-map-cheat-sheet.png)*Credit: Michael Plöd*

#### Tools

- [Dynamic Reteaming](https://leanpub.com/dynamicreteaming) 
- [Pioneers, Settlers & Town Planners](http://wardleypedia.org/mediawiki/index.php/Pioneers_settlers_town_planners)
- [Team Topologies](https://teamtopologies.com/)
- [Visualising Sociotechnical Architecture with Context Maps](https://speakerdeck.com/mploed/visualizing-sociotechnical-architectures-with-context-maps)

#### Who to Involve

- People who design, build, test software
- People who have domain knowledge
- People who understand the product and business strategy

### Define

Define the roles and responsibilities of each [bounded context](https://martinfowler.com/bliki/BoundedContext.html).

Before committing to a design, make explicit decisions about the choices which can have a significant impact on the overall design. Have these conversations early while it is still easy to change your mind and explore alternative models.

Design collaboratively and visually, and start to consider the technical limitations so that you can uncover constraints or opportunities.

As a starting point, we recommend the [Bounded Context Canvas](https://github.com/ddd-crew/bounded-context-canvas).

![Bounded Context Canvas](resources/bounded-context-canvas-v4.jpeg)

#### Tools

- [Bounded Context Canvas](https://github.com/ddd-crew/bounded-context-canvas)
- [C4 System Context Diagram](https://c4model.com/#SystemContextDiagram)
- [Quality Storming](https://speakerdeck.com/mploed/quality-storming)

#### Who to Involve

- People who design, build, test software
- People who have domain knowledge
- People who are responsible for the product

### Code

Code the domain model.

Aligning the code to the domain makes it easier to change the code when the domain changes. By collaboratively modelling the problem space with experts, the developers have a chance to learn about the domain and minimise misunderstandings. 

As a starting point, we recommend the [Aggregate Design Canvas](https://github.com/ddd-crew/aggregate-design-canvas).

![Aggregate Design Canvas](resources/aggregate-design-canvas-v1.jpg)

#### Tools

- [Aggregate Design Canvas](https://github.com/ddd-crew/aggregate-design-canvas)
- [C4 Component Diagrams](https://c4model.com/#ComponentDiagram)
- [Design-Level EventStorming](https://www.eventstorming.com/)
- [Event Modeling](https://eventmodeling.org/posts/what-is-event-modeling/)
- [Hexagonal Architecture](https://en.wikipedia.org/wiki/Hexagonal_architecture_(software))
- [Mob Programming](https://mobprogramming.org/)
- [Model Exploration Whirlpool](https://domainlanguage.com/ddd/whirlpool/)
- [Onion Architecture](https://jeffreypalermo.com/2008/07/the-onion-architecture-part-1/)
- [Unified Modelling Language](https://en.wikipedia.org/wiki/Unified_Modeling_Language)

#### Who to Involve

- People who design, build, test software

## Contributors

Thanks to all [existing and future contributors](https://github.com/ddd-crew/ddd-starter-modelling-process/graphs/contributors) and to the following individuals who have all contributed to the DDD Starter Modelling Process:

- [Ciaran McNulty](https://github.com/ciaranmcnulty)
- [Eduardo da Silva](https://github.com/emgsilva)
- [Gien Verschatse](https://twitter.com/selketjah)
- [James Morcom](https://twitter.com/morcs)
- [Maxime Sanglan-Charlier](https://twitter.com/__MaxS__)

## Contributions and Feedback

The Domain-Driven Design Starter Modelling Process is freely available for you to use. In addition, your feedback and ideas are welcome to improve the technique or to create alternative versions.

If you have questions you can ping us or open an [Issue](https://github.com/ddd-crew/ddd-starter-modelling-process/issues/new/choose).

Feel free to also send us a pull request with your examples or experience reports.

[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
