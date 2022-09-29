<img src="https://github.com/Guru-Collective/Whitepaper/raw/master/images/logo_text.png" width="320">

# Whitepaper

## Abstract
## Glossary

* [**Blockchain**](#blockchain) — A decentralized database with a cryptographic guarantee of information immutability;
* [**Token**](#token) — a unit of account whose transaction information is stored in the [Blockchain](#blockchain); 
* [**Smart Contract**, **DeFi Protocol**](#smart-contract) — децентрализованное программное приложение (DApp, decentralized application), использующее [блокчейн](#blockchain) в качестве среды исполнения и оперирующее токенами;
* [**NFT**](#nft) — частный случай смарт-контракта, используемого для реализации невзаимозаменяемого токена — цифрового сертификата о каком-либо праве на какой-либо актив или услугу цифрового, либо реального мира; 
* [**DAO**](#dao) — организация, представленная правилами, закодированными в виде смарт-контрактов, являющаяся прозрачной, контролируемой заинтересованными сторонами и не подверженной влиянию центрального органа власти;
* [**Web3**](#web3) — следующая итерация эволюции Всемирной паутины — на основе [блокчейна](#blockchain), которая включает в себя такие концепции, как децентрализация и экономика на основе токенов;
* [**Guru Collective (далее ДАО)**](#gurucollective) — бизнес-сообщество единомышленников, объединенных идеей исследования, изучения и внедрения блокчейн-технологий таких как [Web3](#web3) и разделяющих общие ценности и миссию сообщества;
* [**Ценности Guru Collective**](#dao-values) — основополагающие факторы сообщества Guru Collective, которые разделяют участники сообщества
* [**Сообщество Guru Collective**](#community) принимает в свои ряды только лучших профессионалов своего дела, чтобы сделать их выдающимися;
Сообщество Guru Collective придерживается максимальной прозрачности и открытоски как в организационных, так и в бизнес-процессах;
Сообщество Guru Collective не разделяет участников по каким-либо качествам и свойствам. Единственный критерий, оцениваемый сообществом — профессионализм и репутация;
Сообщество Guru Collective разделяет идеи взаимоуважения и взаимоподдержки. Мы уважаем друг-друга и помогаем достичь как общие, так и частные цели!
* [**Миссия Guru Collective**](#mission) — повышение осведомленности о децентрализованных технологиях, увеличение социального влияния сообщества, а также рост капитализации участников за счет повышения собственной экспертизы, а также при помощи профессионального сообщества. 
* [**Протокол Guru Collective (далее Протокол)**](#[protocol]) — комплекс смарт-контрактов, используемый для координации сообщества Guru Collective, использующий [блокчейн](#blockchain) и оперирующий включая (но не ограничиваясь перечисленным далее) токенами ликвидности, токенами репутации, а также NFT для реализации инвестиционных стратегий, а также деятельности по управлению протоколом;
* [**Guru NFT**](#gurunft) — невзаимозаменяемый токен, выступающий в качестве «карты доступа», открывающей владельцу доступ к экосистеме Guru Collective в течение всего срока подписки. Может существовать в различных форматах, в зависимости от уровня доступа.
* [**Подписка**](#subscription) — период времени, в течение которого Владелец Guru NFT обладает доступом к экосистеме Guru Collective и ее закрытым информационным ресурсам. Доступный срок подписки определяется числом токенов ликвидности во владении участника и также может быть продлен за счет сжигания токенов ликвидности. 
* [**Ликвидность протокола**](#protocol-liquidity) — общий объем средств, зарезервированных на смарт-контрактах протокола;
* [**Утилитарный токен**](#utility-token) — токен, дающий своим владельцам право доступа к каким-либо сервисам и продуктам.
* [**Токен ликвидности ($GCL)**](#liquidity-token) — утилитарный токен протокола, используемый для пополнения ликвидности. Каждому токену соответстует определенный процент от общего объема ликвидности протокола. Провайдеры ликвидности могут истребовать свой процент, использовав функцию Burn LP в панели управления ДАО
* [**Токен репутации ($GURU)**](#reputation-token) — утилитарный токен протокола, позволяющий менять параметры работы протокола, а также принимать решения по развитию протокола в рамках процесса управления ДАО. Может быть получен в результате голосования сообщества в качестве вознаграждения за управление протоколом,  за вклад в деятельность сообщества 
* [**Участник**](#участник) — член сообщества Guru Collective, разделяющий его миссию и ценности, а также владеющий токенами репутации и/или токенами ликвидности;
* [**Сообщество**](#community) — сообщество участников Guru Collective;
* [**Организационный комитет**](#организационный-комитет) — группа участников Guru Collective, принимающая на себя задачи по реализации операционной деятельности. Состав организационного комитета может быть изменен сообществом в рамках управления протоколом.
* [**Экспертный комитет**](#экспертный-комитет) — группа участников Guru Collective,
* [**Операционная деятельность**](#токен) — деятельность организационного комитета, обеспечивающяя достижение целей и реализацию миссии Guru Collective;
* [**Управление протоколом (также governance)**](#токен) — комплекс процессов, включающий в себя, но не ограничивающийся:
процессом распределения ликвидности протокола в различные инвестиционные стратегии;
процессом внесения изменений в параметры протокола;
процессом сопровождения операционной деятельности Guru Collective.
* [**Голосование**](#voting) — процесс принятия решения в рамках ДАО, в котором участники могут отдать голос  за какое-либо решение, вынесенное на голосование сообщества. Результатом голосования является вариант, за который было отдано больше всего голосов, выраженных в количестве токенов на счету каждого участника, принявшего участие в голосовании
Кумулятивное голосование — вид голосования, в котором число голосов, принадлежащих одному участнику, умножается на число выбираемых мест и распределяется произвольно между произвольным числом вариантов. Результатом голосования являются варианты, получившие наибольшее число голосов, выраженных в количестве токенов на счету каждого участника, принявшего участие в Голосовании
* [**Параметры протокола**](#voting) —  набор параметров, определяющих процесс работы Guru Collective. Сообщество может проголосовать за внедрение новых параметров при условии принятия соотвествующего решения. По решению сообщества может быть назначен организационный комитет, избираемый голосованием
* [**Решение**](#solution) — решение, принятое сообществом в рамках процесса управления протоколом и верифицированное в [блокчейне](#blockchain).
Любое решение может быть вынесено только по голосованию сообщества, принятого в соответствии с регламентом процесса управления;
* [**Регламент процесса управления**](#voting) — документ, содержащий описание последовательности действий, необходимых для обеспечения максимально прозрачного процесса принятия решения, а такде внесения изменений в параметры протокола в рамках процесса управления протоколом
* [**Вознаграждение за управление протоколом**](#voting) — каждый участник вправе запросить вознаграждение в виде токенов репутации и/или токенов ликвидности за осуществление операционной деятельности в пользу ДАО. Владельцы токенов репутации могут проголосовать за начисление токенов репутации другим участникам сообщества в рамках регулярной инфляции репутации. 
Владельцы токенов репутации могут 
* [**Панель управления ДАО**](#voting) — Веб приложение с доступным для участников  пользовательским интерфейсом, в котором все участники ДАО принимают участие в принятии решений в процессе голосования.
* [**Сжигание токенов ликвидности (далее Burn LP)**](#burnlp) — Механизм регуляции числа токенов ликвидности, за счет вывода их части из оборота посредством различных механизмов, таких как приоретение подписки и голосования.
* [**Инвестиционная стратегия (далее Стратегия)**](#strategy) — предложение по распределению ликвидности протокола в различные DeFi-протоколы, а также другие протоколы и/или организации по решению сообщества. Владельцы токенов репутации могут предлагать инвестиционные стратегии в соответствии с шаблоном. Инвестиционные стратегии могут включать в себя, но не ограничиваться различными DeFi-протоколами с которыми ДАО может взаимодействовать. Также в качестве составляющих инвестиционной стратегии могут выступать приватные раунды различных DeFi-протоколах, прошедших внутренний аудит сообщества
* [**Шаблон инвестиционной стратегии**](#strategy-template) — документ, содержащий описание последовательности действий, необходимых для реализации максимально прозрачного процесса реализации инвестиционной стратегии
* [**Вклад в деятельность сообщества (далее Вклад)**](#xxx) — деятельность, направленная на реализацию целей и миссии сообщества, которая может быть оценена в рамках аудита.  
* [**Аудит**](#audit) — процесс оценки сообществом эффективности инвестиционной стратегии и/или вклада в деятельность сообщества в рамках операционной деятельности сообщства.
* [**Минимальный срок исполнения**](#execution-period) — период, в рамках которого производится оценка эффективности стратегии, В зависимости от эффективности конкретной стратегии, участник, который ее предложил, может запросить вознаграждение в виде токенов ликвидности. После завершения минимального срока исполнения, сообщество может проголосовать за продление использования инвестиционной стратегии, если оценка эффективности стратегии является приемлемой для сообщества
* [**Эффективность стратегии**](#voting) — разница между оценкой объема ликвидности протокола, направленного в инвестиционную стратегию на момент старта стратегии и на момент завершения минимального срока исполнения;
* [**Оценка эффективности стратегии**](#voting) — исчисляемая в процентах оценка эффективности стратегии за конкретный спринт, равная доле дохода конкретной инвестиционной стратегии в общем доходе ДАО за текущий спринт.
* [**Технические ограничения ДАО**](#dao-restrictions) — набор программных ограничений внутри смарт-контракта ДАО предназначенных для защиты сообщества от несанкицонированного доступа и связанных с этим 
* [**Спринт**](#sprint) — минимальный период отчетности, принятый Сообществом. В рамках этого периода осуществляется краткосрочное планирование задач Сообщества, а также может производиться промежуточная оценка эффективности текущей инвестиционной стратегии и/или вклада в сообщество конкретных участников. 
При запуске проекта спринт составляет две календарные недели, но может быть изменен по решению Сообщества. 
* [**Инфляция репутации**](#reputation-inflation) — процесс выпуска новых токенов репутации. Сообщество получает возможность дополнительно выпустить х токенов репутации каждый спринт, где
х= Общая эмиссия  0.05 
Сообщество вправе распоряжаться эмиссией по своему усмотрению, либо перераспределить токены между текущими участниками, либо передав токены новым участникам, внесшим существенный вклад в деятельность сообщества.
* [**Распределение репутации**](#reputation-) — по итогам спринта участники могут проголосовать за распределение токенов, появившихся в результате инфляции репутации в зависимости от вклада участников в сообщество. Участники, выполнившие работу могут вынести на голосование свою кандидатуру, приложив отчет о проделанной работе и презентовав его на статус-созвоне по итогам спринта. По итогам статус-созвона будет сформировано кумулятивное голосование, по итогам готового будет распределена свежая эмиссия токенов.  
* [**Координатор**](#coordinator) — участник сообщества, который обеспечивает постановку задач, а также контроль за их соблюдением в рамках одного спринта. По итогам статус-колла сообщество может произвести оценку эффективности координатора, распределив ему вознаграждение в рамках оценки его эффективности в рамках кумулятивного голосования
* [**Экстренная остановка ДАО**](#dao-shutdown) — процесс экстренной остановки всей активности ДАО с целью сохранения его правильного функционированя и предотвращения несанкционированных операций.

## Обзор экосистемы DeFi 

### State of DeFi
### Предпосылки для токенизации сообществ 
### ДАО как инструмент координации и мотивации

## Концепция Guru Collective
### Мотивация создания Guru Collective
### Миссия Guru Collective
### Ценности Guru Collective
### Целевая аудитория Guru Collective

## Обзор экосистемы Guru Collective
### Образовательная программа Guru Academy
### Бизнес клуб Guru Collective
### Акселератор Guru Collective

## Прочие положения

