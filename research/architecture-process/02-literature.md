# Литература и статус проверки

## Как читать этот список

Это фоновый каталог кандидатов, а не список обязательного чтения и не результат систематического обзора. После ревью **обязательны только L08 (выбранные разделы), L10 (выбранные разделы) и L30**. Их мотивация и объём — в [плане](05-learning-path.md), проверка — в [заметках](10-core-source-notes.md). Остальные записи используются при конкретном пробеле.

После уточнения темы проверяем, какие основания источники дают для сравнительного выбора альтернатив. Рекомендации по rationale, выявление рисков и улучшение аргументации сами по себе не устанавливают превосходство одного решения над другим. Новое уточнение не увеличивает обязательный набор.

Исходные аннотации непроверенных работ остаются ориентирами, а не конспектами. Новые статусы не распространяются на все материалы автора или метод в целом.

Статусы:

- **B — библиографический кандидат:** работа включена по известной литературе; первоисточник в этой сессии не открыт. Авторство, издание и точные формулировки проверить при чтении.
- **M — метаданные сверены:** библиографические сведения подтверждены каталогом или издателем; полный текст не прочитан. Для книги отдельно указан просмотр оглавления.
- **P — первичный материал просмотрен:** указан конкретный доступный документ. Статус не распространяется на книгу, научную статью или документацию целиком.
- **U — подтверждено пользователем:** только явно названные им сведения, без подразумеваемого чтения.

Для будущих заметок отдельно записывать «метаданные сверены», «аннотация прочитана», «полный текст прочитан» и «метод применён». Не объединять эти статусы в слово «изучено».

## Теория и основания

| ID | Источник | Зачем он нужен | Статус |
| --- | --- | --- | --- |
| L01 | Herbert A. Simon. *The Sciences of the Artificial*. Первое издание, 1969; последующие издания различаются | Проектирование как поиск решений при целях и ограниченной рациональности. Не считать его алгоритмом архитектуры ПО | B |
| L02 | Horst W. J. Rittel, Melvin M. Webber. *Dilemmas in a General Theory of Planning*. Policy Sciences, 1973. [DOI](https://doi.org/10.1007/BF01405730) | Wicked problems: почему формулировка проблемы, цели и оценка результата могут быть спорными. Статья о планировании; перенос на ПО надо обосновать | B |
| L03 | David L. Parnas. *On the Criteria To Be Used in Decomposing Systems into Modules*. Communications of the ACM, 1972. [DOI](https://doi.org/10.1145/361598.361623) | Information hiding и выбор границ вокруг решений, которые могут измениться; важное сравнение с Löwy | B |
| L04 | Dewayne E. Perry, Alexander L. Wolf. *Foundations for the Study of Software Architecture*. ACM SIGSOFT Software Engineering Notes, 1992. [DOI](https://doi.org/10.1145/141874.141884) | Концептуальная постановка архитектуры как предмета исследования | B |

## Описания и качество

| ID | Источник | Зачем он нужен | Статус |
| --- | --- | --- | --- |
| L05 | ISO/IEC/IEEE 42010. *Software, systems and enterprise — Architecture description*, редакция 2022; также важна редакция 2011. [Сайт по стандарту](https://www.iso-architecture.org/42010/) | Участники, concerns, viewpoints и архитектурное описание. Сверять определения по выбранной редакции; стандарт не равен методу синтеза хорошей архитектуры | B |
| L06 | Philippe Kruchten. *Architectural Blueprints — The “4+1” View Model of Software Architecture*. IEEE Software, 1995. [DOI](https://doi.org/10.1109/52.469759) | Почему одного представления недостаточно; связь видов с интересами и сценариями | B |
| L07 | ISO/IEC 25010. *Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE) — Product quality model*, редакция 2023 | Словарь качества продукта. При использовании редакции 2011 не смешивать её структуру с редакцией 2023; модель качества не задаёт все пороги и веса | B |
| L08 | Len Bass, Paul Clements, Rick Kazman. *Software Architecture in Practice*. 4-е издание, 2021. [Издатель](https://www.informit.com/store/software-architecture-in-practice-9780136886099) | Обязательные разделы: гл. 3, 19, 21; §20.3, §22.7 — требования, оценка и rationale. Книга — синтез знаний, не отдельный эксперимент | M: издательские сведения и оглавление; полный текст не прочитан |

## Процесс, оценка и решения

| ID | Источник | Зачем он нужен | Статус |
| --- | --- | --- | --- |
| L09 | Rick Kazman, Jai Asundi, Mark Klein. *Quantifying the Costs and Benefits of Architectural Decisions*. CMU/SEI-2001-TR-009, 2001. [Каталог SEI](https://www.sei.cmu.edu/library/) | CBAM: экономическое сопоставление решений. Проверить работу с неопределённостью оценок затрат и пользы | B |
| L10 | Rick Kazman, Mark Klein, Paul Clements. *ATAM: Method for Architecture Evaluation*. CMU/SEI-2000-TR-004, 2000. [Первоисточник SEI](https://www.sei.cmu.edu/library/atam-method-for-architecture-evaluation/) | Обязательные выбранные разделы: конкретная процедура, требования к rationale и границы engineering judgement. Не приписывать методу доказательство оптимальности | P: просмотрены выбранные разделы официального PDF |
| L11 | Anton Jansen, Jan Bosch. *Software Architecture as a Set of Architectural Design Decisions*. WICSA, 2005 | Архитектура через решения и их rationale; связь с хранением архитектурных знаний | B |
| L12 | Christine Hofmeister, Philippe Kruchten, Robert L. Nord, Henk Obbink, Alexander Ran, Pierre America. *A General Model of Software Architecture Design Derived from Five Industrial Approaches*. Journal of Systems and Software, 2007 | Сравнение промышленных подходов и общая модель анализа, синтеза и оценки; проверить, что именно подтверждено данными | B |
| L13 | Nenad Medvidovic, Richard N. Taylor. *A Classification and Comparison Framework for Software Architecture Description Languages*. IEEE Transactions on Software Engineering, 2000. [DOI](https://doi.org/10.1109/32.825767) | Что дают языки описания архитектуры и по каким осям они различаются | B |
| L18 | Mary Shaw, David Garlan. *Software Architecture: Perspectives on an Emerging Discipline*. 1996 | Исторические основания: стили, абстракции и анализ; изучать с учётом возраста примеров | B |
| L19 | Michael Nygard. *Documenting Architecture Decisions*. 2011; связанный инструмент — Nat Pryce, [adr-tools](https://github.com/npryce/adr-tools) | Практика ADR: контекст, решение и последствия. Прочитан README инструмента, а не оригинальная статья Nygard | P только для README adr-tools; статья B |
| L25 | Humberto Cervantes, Rick Kazman. *Designing Software Architectures: A Practical Approach*. 2016 | Практический вход в Attribute-Driven Design (ADD), от drivers к итерациям проектирования | B |

## Формальные методы

| ID | Источник | Зачем он нужен | Статус |
| --- | --- | --- | --- |
| L14 | Leslie Lamport. *Specifying Systems: The TLA+ Language and Tools for Hardware and Software Engineers*. 2002 | Семантика, safety/liveness, спецификация поведения, проверка модели. Не начинать с обещания доказать весь продукт | B |
| L15 | Chris Newcombe, Tim Rath, Fan Zhang, Bogdan Munteanu, Marc Brooker, Michael Deardeuff. *How Amazon Web Services Uses Formal Methods*. Communications of the ACM, 2015. [DOI](https://doi.org/10.1145/2699417) | Промышленный опыт применения формальных методов. Сильный пример осуществимости; сам по себе не контролируемая оценка эффекта для любых команд | B |
| L16 | [Официальный репозиторий инструментов TLA+](https://github.com/tlaplus/tlaplus), README | Подтверждает наличие CLI, TLC model checker, SANY parser и PlusCal translator. Не подтверждает полноту или полезность конкретной архитектурной модели | P только для README |

## Выбор, организация и качество исследований

| ID | Источник | Зачем он нужен | Статус |
| --- | --- | --- | --- |
| L17 | Ralph L. Keeney, Howard Raiffa. *Decisions with Multiple Objectives: Preferences and Value Tradeoffs*. 1976 | Строгий язык целей, предпочтений и компромиссов; перенос на архитектуру — отдельная работа | B |
| L20 | Melvin E. Conway. *How Do Committees Invent?* Datamation, 1968 | Организация и структура проектируемых систем. Отличать исходное рассуждение от всех позднейших интерпретаций «закона Конвея» | B |
| L21 | Marcelo Cataldo, Patrick A. Wagstrom, James D. Herbsleb, Kathleen M. Carley. *Identification of Coordination Requirements: Implications for the Design of Collaboration and Awareness Tools*. CSCW, 2006 | Эмпирическое исследование координации; отправная точка для литературы о socio-technical congruence. Проверить дизайн исследования и контекст выборки | B |
| L22 | Liliana Dobrica, Eila Niemelä. *A Survey on Software Architecture Analysis Methods*. IEEE Transactions on Software Engineering, 2002. [DOI](https://doi.org/10.1109/TSE.2002.1019479) | Историческое сравнение методов анализа, основание для поиска последующих обзоров; не обзор состояния на 2026 год | B |
| L23 | Barbara Kitchenham, Stuart Charters. *Guidelines for Performing Systematic Literature Reviews in Software Engineering*. EBSE-2007-01, 2007 | Протокол поиска, отбора и оценки исследований. Использовать для перехода от этой карты к воспроизводимому обзору | B |

## Отправная книга пользователя

| ID | Источник | Зачем он нужен | Статус |
| --- | --- | --- | --- |
| L24 | Juval Löwy. *Righting Software: A Method for System and Project Design*. Addison-Wesley, 2019. [Страница издателя — адрес требует проверки](https://www.informit.com/store/righting-software-a-method-for-system-and-project-design-9780136524038) | The Method: проектирование системы и проекта, декомпозиция по изменчивости. Отдельный [план чтения](07-righting-software.md) | U: автор и название; B: издание, содержание и сильные утверждения |

Номер L25 добавлен после уточнения книги, поэтому последовательность тематических таблиц не совпадает с порядком номеров.

## Кандидаты из предоставленного предыдущего чата

Эти ссылки перенесены из [ответа другого чата](sources/previous-chat/01-assistant-modularity-cost.txt). Наличие ссылки в ответе не подтверждает ни чтение источника, ни правильность его пересказа. Библиографические сведения ниже воспроизведены по этому ответу и требуют сверки.

| ID | Запись из чата | Что проверить | Статус |
| --- | --- | --- | --- |
| L26 | Koen Frenken, Stefan Mendritzki. *Optimal modularity: a demonstration of the evolutionary advantage of modular architectures*. Journal of Evolutionary Economics, 2012. [Ссылка из чата](https://link.springer.com/article/10.1007/s00191-011-0240-6) | Допущения модели, смысл оптимальности, тип свидетельств; это кандидат для сравнения моделей, не прямой разбор книги | B, найден в предоставленном ответе |
| L27 | *Defining and measuring microservice granularity — a literature overview*. В чате указан 2021 год. [Ссылка из чата](https://pmc.ncbi.nlm.nih.gov/articles/PMC8444086/) | Авторы и метаданные, фактический состав обзора, трактовка гранулярности; заявленные в чате 29 работ не проверены | B: первоначально сетевой отказ; при ревью HTTP 200 с browser challenge, текст статьи не получен |
| L28 | Omnitech. *Reading Righting Software*. В чате указана дата 23 февраля 2024 года. [Ссылка из чата](https://www.omnitech-inc.com/blog/reading-righting-software/) | Существует ли страница, авторство, дата и конкретные критические тезисы; затронуто ли приложение B или только книга в целом | B, сетевой запрос заблокирован |
| L29 | *The pains and gains of microservices: A Systematic grey literature review*. Journal of Systems and Software, в чате указан 2018 год. [Ссылка из чата](https://www.sciencedirect.com/science/article/pii/S0164121218302139) | Авторы, метаданные, число и тип включённых материалов; заявленные 51 источник не проверены; связь с распределённостью, а не любой модульностью | B, найден в предоставленном ответе |

Пока **не подтверждено**, что есть прямая публичная критика именно графика B-4. Предыдущий ответ сам различает критику подхода и прямую рецензируемую критику модели, но его поисковый протокол не предоставлен. Эти записи не заменяют новый поиск и проверку полных текстов.

## Источники по уточнённой проблеме, найденные при ревью

| ID | Источник | Роль | Статус |
| --- | --- | --- | --- |
| L30 | Klara Borowa, Rodrigo Rebouças de Almeida, Marion Wiese. *Debiasing Architectural Decision-Making: An Experiment With Students and Practitioners*. ICSA, 2025. [DOI](https://doi.org/10.1109/ICSA65012.2025.00029), [авторская версия v1](https://arxiv.org/abs/2502.04011v1) | Обязательный современный эмпирический источник об архитектурной аргументации; измеренные bias-коды не равны качеству готовой системы | P: методика, результаты и ограничения авторской версии; метаданные публикации сверены |
| L31 | Antony Tang, Muhammad Ali Babar, Ian Gorton, Jun Han. *A Survey of Architecture Design Rationale*. Journal of Systems and Software, 2006. [DOI](https://doi.org/10.1016/j.jss.2006.04.029) | Условное расширение: историческая практика rationale; не описание всей индустрии в 2026 году | M: Crossref; полный текст не прочитан |
| L32 | Pim De Jong, Jan Martijn E. M. Van Der Werf, Marlies Van Steenbergen, Floris Bex, Matthieu Brinkhuis. *Evaluating Design Rationale in Architecture*. ICSA-C, 2019. [DOI](https://doi.org/10.1109/ICSA-C.2019.00033) | Условное расширение для оценки rationale после проверки полного текста | M: Crossref; читаемый полный текст не получен |
| L33 | Shunsuke Mori, Kohei Nishio, Taku Inagawa, Hironori Washizaki, Naoyasu Ubayashi. *Toward Evidence-Based Architectural Decision Making Over Fragmented Knowledge*. ICSA-C, 2026. [DOI](https://doi.org/10.1109/ICSA-C68850.2026.00029) | Условный кандидат при вопросе об объединении свидетельств; покупка пока отложена. [Оценка приоритета](10-core-source-notes.md) | M: метаданные и ссылки Crossref; прочитан вторичный Summary из пользовательской копии EurekaMag, первичный текст не получен |

## История проверок 11 октября 2026

Первая таблица описывает первоначальную подготовку, когда научные сайты были недоступны. Текущий результат ревью указан ниже; старый сетевой отказ не означает, что источник по-прежнему недоступен.

| Действие | Результат | Что из него следует |
| --- | --- | --- |
| Доступ к исходному чату ChatGPT | Прокси отказал: CONNECT HTTP 403 | Чат не прочитан; неизвестно, были ли там уже выводы или источники |
| Доступ к общей ссылке chatgpt.com/share/6acbbbcf-bd28-83ec-a138-9d6d91f13011 | CONNECT HTTP 403 | Страница не получена; публичность ссылки не устраняет сетевое ограничение среды |
| Запрос каталога www.sei.cmu.edu/library/ | CONNECT HTTP 403 | Отчёты SEI не открыты; не означает, что их нет или что сайт требует оплату |
| Запрос www.iso-architecture.org/42010/ | CONNECT HTTP 403 | Стандарт и его пояснения не прочитаны |
| Запрос Crossref по software architecture evaluation | CONNECT HTTP 403 | Современный библиографический поиск не выполнен; результатов и количества находок нет |
| Запрос страницы издателя Righting Software | CONNECT HTTP 403 | Издательское описание и оглавление не сверены |
| raw.githubusercontent.com/tlaplus/tlaplus/master/README.md | HTTP 200, текст просмотрен | Подтверждён состав инструментов; README указывает Java 11+ для текущей версии |
| raw.githubusercontent.com/npryce/adr-tools/master/README.md | HTTP 200, текст просмотрен | Подтверждена работа с ADR в Markdown и связями supersedes/superseded |
| Два текстовых вложения предыдущего чата | Получены и полностью прочитаны; копии сохранены | Доступен ход аргументации; утверждения о книге и внешних работах не стали проверенными первоисточниками |
| Запрос pmc.ncbi.nlm.nih.gov/articles/PMC8444086/ | CONNECT HTTP 403 | Полный текст L27 и метаданные не получены |
| Запрос рецензии Omnitech | CONNECT HTTP 403 | Содержание L28 не получено |

README читались с изменяемых веток master, а не с фиксированных commit. Для воспроизводимого исследования следует закрепить SHA при дальнейшем использовании. Эти два README — свидетельства о назначении инструментов, не доказательства эффективности архитектурного процесса. TLA+ и adr-tools не устанавливались и не запускались.

При ревью получены читаемая страница и официальный PDF ATAM, оглавление SAIP у издателя, метаданные Crossref и авторская версия L30. Новые проверки и ограниченный целевой поиск записаны в [журнале](sources/review-2026-10-11/README.md). HTTP 200 PMC содержал browser challenge, а HTTP 202 IEEE не дал читаемого текста; эти ответы не засчитаны как чтение статей.

## Границы актуальности и следующий поиск

В исходном каталоге преобладает фундаментальная литература 1968–2023 годов. При ревью проверен эмпирический материал 2025 года и найдены метаданные работы 2026 года. **Полного обзора исследований 2024–2026 годов по-прежнему нет.** Дата подготовки и наличие свежих находок не доказывают полноту охвата.

Если после обязательного чтения потребуется обновление, выбрать соответствующее направление:

1. Последующие работы, цитирующие L10, L12 и L22: сравнительная оценка методов, промышленные кейсы и репликации.
2. Свежие обзоры architectural decision making, architecture evaluation, architecture knowledge и architecture metrics.
3. Исследования предсказательной валидности метрик изменяемости, влияния организационных факторов и стоимости применения методов.
4. Работы, оценивающие volatility-based decomposition и The Method; поиск должен допускать отсутствие независимых сравнительных исследований, а не заранее предполагать его.
5. Отрицательные результаты, неуспешное применение и альтернативные объяснения положительных кейсов.

Запросы и правила отбора находятся в [протоколе](03-research-protocol.md). Пока этот поиск не проведён, нельзя заключать, что выбранная гипотеза нова или что вопрос уже закрыт.

## Сетевые требования для продолжения

В черновик настроек добавлены домены SEI, сайта 42010, ISO, DOI, Crossref, ACM, IEEE, arXiv, Microsoft и издателя InformIT, а также chatgpt.com для общей ссылки пользователя. Для проверки ссылок из переданных ответов добавлены pmc.ncbi.nlm.nih.gov, link.springer.com, www.omnitech-inc.com и www.sciencedirect.com. Это перечень необходимых направлений доступа, а не список уже просмотренных сайтов. Ограничения текущей среды не были обойдены. Сохранение черновика не применяет настройки и не публикует среду; после применения нужно повторить конкретные запросы. Доступ через разрешённый домен не гарантирует доступность полного текста за paywall. Чужой приватный чат также может остаться недоступным независимо от сетевой настройки.
