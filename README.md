# ТЕХНОЛОГИЯ РАЗРАБОТКИ ПРОГРАММНОГО ОБЕСПЕЧЕНИЯ
Данный конспект можно разделить на 4 части:\
\
**1.** В первой части рассматриваются проблемы, связанные с низкой производительностью и низким процентом успешно завершенных проектов в современной разработке программного обеспечения.\
\
**2.** Во второй представлены различные методы проектирования, включая нисходящее программирование, объектно-ориентированное программирование и гибкие методологии, такие как _XP_ и _Crystal Clear_.\
\
**3.** В третьей описываются этапы развития программного обеспечения, включая сбор и анализ требований, проектирование, разработку, тестирование и сопровождение.\
\
**4.** И в четвёртом представлены различные приемы формулирования требований, такие как создание словаря терминов и распределение требований по подсистемам.
## 1. Проблемы с низкой производительностью
В литературе по программной разработке обсуждаются вопросы, связанные с недостаточной эффективностью и низким процентом успешного завершения проектов в современной сфере программирования. Такие трудности могут быть обусловлены разнообразными факторами, такими как:
1) **Недостаточная проработка требований:** Недостаточное внимание к формулированию и анализу требований к программному продукту может привести к непониманию задачи, увеличению количества ошибок и дополнительным затратам на исправления в дальнейшем.
2) **Недостаточное тестирование:** Недостаточное тестирование программного продукта может привести к выявлению серьезных ошибок и дефектов на поздних стадиях разработки, что затрудняет и замедляет процесс завершения проекта.
3) **Недостаточное управление проектом:** Неэффективное управление проектом, включая планирование, контроль и коммуникацию, может привести к задержкам, бюджетным перерасходам и общей неудаче проекта.
4) **Технические проблемы:** Проблемы с выбором технологий, архитектурой системы, проектированием и реализацией могут привести к низкой производительности и неудовлетворительным результатам.\
\
Изучение этих проблем помогает разработчикам и менеджерам понять основные причины неудачных проектов и принять меры для улучшения процесса разработки программного обеспечения, увеличения производительности и повышения процента успешно завершенных проектов.
## 2. Методы проектирования
В лекций рассматриваются разнообразные методы проектирования, каторые могут сыграть важную роль в формировании высококачественного программного продукта.
1) **Нисходящее программирование:** Этот метод проектирования начинается с общего описания системы и последовательно уточняется до уровня деталей. Разработчики начинают с формулирования общих требований, затем разбивают их на более мелкие задачи и постепенно приступают к написанию кода. Этот подход позволяет более точно планировать и контролировать процесс разработки.
2) **Объектно-ориентированное программирование (ООП):** ООП - это методология программирования, основанная на концепциях объектов и классов. Программное обеспечение разрабатывается путем создания объектов, которые взаимодействуют друг с другом для выполнения определенных задач. ООП способствует повторному использованию кода, упрощает его понимание и обеспечивает более гибкую архитектуру программ.
3) **Гибкие методологии (XP и Crystal Clear):** Гибкие методологии разработки программного обеспечения, такие как _Extreme Programming_ (XP) и [Crystal Clear](CrystalClear.png) , предлагают подходы к разработке, ориентированные на гибкость, быструю адаптацию к изменениям и активное \
\
взаимодействие с заказчиком. _XP_, например, подчеркивает парное программирование, тестирование итераций, частые поставки и непрерывную интеграцию. _Crystal Clear_, с другой стороны, уделяет внимание коммуникации, простоте и участию пользователей в процессе разработки.
## 3. Этапы развития программного обеспечения
В материалах описываются этапы развития программного продукта, которые представляют собой последовательность деятельностей, необходимых для создания, тестирования и поддержки программного обеспечения. Эти этапы включают:
1. **Сбор и анализ требований:** На этом этапе происходит взаимодействие с заказчиком для определения функциональных и нефункциональных требований к программному продукту. Это важный этап, поскольку правильно сформулированные требования являются основой успешной разработки.
2. **Проектирование:** На этом этапе определяется архитектура программного продукта, разрабатываются детальные планы реализации требований, проектируются интерфейсы и структура программы.
3. **Разработка:** В этот этап входит написание кода программы в соответствии с разработанным проектом. Разработчики преобразуют проектные решения в рабочий программный код.
4. **Тестирование:** После завершения разработки программного продукта проводится тестирование, включающее проверку на соответствие требованиям, выявление ошибок и дефектов, а также проверку работоспособности и производительности.
5. **Сопровождение:** Этот этап включает в себя поддержку и обслуживание программного продукта после его выпуска. В рамках сопровождения могут выполняться исправление ошибок, добавление новых функций, обновление и адаптация к изменяющимся требованиям.\
\
Эти этапы представляют общепринятую последовательность деятельностей в процессе разработки программного обеспечения и помогают структурировать работу команды разработчиков, обеспечивая систематический подход к созданию качественного и функционального программного продукта.
## 4. Приемы формулирования требований
В конспекте о разработке программного обеспечения также представлены различные приемы формулирования требований, которые помогают уточнить и структурировать требования к программному продукту. Некоторые из этих приемов включают:
1. **Создание словаря терминов:** Этот прием предполагает составление специального словаря, в котором собраны определения всех терминов, элементов и структур данных, связанных с разрабатываемой системой. Это помогает участникам проекта использовать единые термины и избежать недопонимания при общении.
2. **Распределение требований по подсистемам:** Данный прием предполагает разделение общих требований к программному продукту на более мелкие и конкретные требования, которые относятся к отдельным подсистемам или компонентам системы. Это позволяет более детально определить функциональность каждой части системы и облегчает управление процессом разработки.\
\
Эти приемы помогают улучшить процесс формулирования требований, сделать их более структурированными и понятными для всех участников проекта. Создание словаря терминов и распределение требований по подсистемам способствует более эффективной коммуникации в команде разработки и помогает избежать недоразумений при интерпретации требований к программному продукту.
