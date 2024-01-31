# Moscow-longevity-project
# Creation of a recommendation service
1. Relevance of the task
Since 2018, the “Moscow Longevity” project has been operating in Moscow,
which provides older Muscovites (55+ for women and 60+
for men) the opportunity to engage in a wide range of
educational, leisure and health activities. Classes
take place in groups offline and online under the guidance of professional
accredited teachers and in five years have become an important part of the city
infrastructure that improves the quality of life of the older generation,
level of socialization and versatile activity.
To date, more than half a million people have joined
to the project, and the number of areas of study exceeded several hundred.
Every month tens of thousands of new and existing members are looking for
suitable groups for you.
Coming soon on the “Moscow Longevity” page
(https://www.mos.ru/city/projects/dolgoletie/) the service will be launched
automated entry into groups, and into one of the user paths
it is planned to introduce recommendation mechanics. This is a recommendation
the solution can significantly reduce the time for selecting relevant
group for the participant, and will also reduce employee labor costs
Moscow Longevity for counseling older citizens in
as part of the search for suitable activities.
2. Description of the task
As part of the task, it is necessary to create a recommendation service,
which will help participants (new and existing) of the Moscow
longevity” select a suitable group for classes based on
accumulated data on user activity in the project. This is the solution
may become part of the registration service for “Moscow Longevity”, which
will be launched on MOS.ru soon.
This recording service has three basic user options:
script:
a) search for a group through the search bar;
b) search through a group catalog with a filtering system;
c) search through completing a survey in which participants answer
questions based on your interests.
In order to more relevantly select groups within the latter
scenario, we propose to develop a full-fledged recommendation
service/module that takes into account the behavior and patterns of consumption already
current participants.
Users of the recommendation service are divided into the following:
groups:
a) current (already registered in the project) participants
“Moscow longevity”
b) new (potential) participants
We do not identify the user (whether he is a member of the Moscow
longevity”) automatically, even if he is already authorized on MOS.ru. So
Thus, at the first stage of user interaction it is necessary
request data that will allow us to determine whether he is
participant of “Moscow Longevity” or not: full name, date of birth.
In case the user is not a member, we must
determine the interests and needs of the visitor and give him recommendations
by groups (through preset filters), and preferably not
in less than 3 different key areas (“for the mind”, “for the body”, “for
soul”) and one additional (additional education with a diploma,
obtaining a new profession).
If we have identified a valid participant, we
should refer to the history of his visits and, taking into account it (and/or other
data), offer additional classes.
Classes (groups) at “Moscow Longevity” according to format
are divided into two parts:
a) face-to-face classes
b) online classes
Thus, in addition to directing classes for face-to-face groups, we
should prioritize offering users classes taking place
as close as possible to his place of residence. Priority format in
“Moscow longevity” are face-to-face classes, hackathon participants with
When designing a recommendation service, it is proposed to take this into account
factor and offer mechanics aimed at engaging
users offline, even if the profile of their interests indicates that
they tend to choose online classes.
Initial data:
List of group filtering parameters in the recording service:
● areas of study (1,2,3 levels)
● class format (face-to-face / online)
● area of classes (for full-time classes)
● schedule (days of week / time)
List of data contained in the “Groups” dataset:
● group code
● direction 1
● direction 2
● direction 3
● address of the sites (for online classes it has a technical
meaning)
● district area
● site area
● schedule
List of data contained in the “Users” dataset:
● unique number
● date of creation of the personal file
● floor
● date of birth
● residential address (details to apartment building)
List of data contained in the “Attendance” dataset:
● unique lesson number
● unique group number
● unique participant number
● online/offline
● date of class
● class start time
● end time of class

1. Актуальность задачи
С 2018 года в Москве работает проект “Московское долголетие”,
который предоставляет москвичам старшего возраста (55+ для женщин и 60+
для мужчин) возможность заниматься широким спектром
образовательно-досуговых и оздоровительных активностей. Занятия
проходят в группах офлайн и онлайн под руководством профессиональных
аккредитованных педагогов и за пять лет стали важной частью городской
инфраструктуры, повышающей качество жизни старшего поколения,
уровень социализации и разносторонней активности.
К настоящему времени более полумиллиона человек присоединились
к проекту, а количество направлений занятий превысило несколько сотен.
Ежемесячно десятки тысяч новых и действующих участников ищут
подходящие для себя группы.
В ближайшее время на странице “Московского долголетия”
(https://www.mos.ru/city/projects/dolgoletie/) будет запущен сервис
автоматизированной записи в группы, а в один из пользовательских путей
планируется внедрить рекомендательные механики. Это рекомендательное
решение сможет существенно сократить время на подбор релевантной
группы для участника, а также сократит трудозатраты сотрудников
Московского долголетия на консультирование граждан старшего возраста в
рамках поиска подходящих занятий.
2. Описание задачи
В рамках задачи необходимо создать рекомендательный сервис,
который поможет участникам (новым и уже действующим) “Московского
долголетия” выбрать подходящую группу для занятий, основываясь на
накопленных данных об активности пользователей в проекте. Это решение
может стать частью сервиса записи в “Московское долголетие”, который
будет запущен на MOS.ru в скором времени.
В этом сервисе записи предусмотрено три базовых пользовательских
сценария:
а) поиск группы через поисковую строку;
б) поиск через каталог групп с системой фильтрации;
в) поиск через прохождение опроса, в котором участники отвечают на
вопросы по своим интересам.
С целью более релевантного подбора групп в рамках последнего
сценария мы предлагаем разработать полноценный рекомендательный
сервис/модуль, учитывающий поведение и паттерны потребления уже
действующих участников.
Пользователи рекомендательного сервиса делятся на следующие
группы:
а) действующие (уже зарегистрированные в проекте) участники
“Московского долголетия”
б) новые (потенциальные) участники
Мы не идентифицируем пользователя (участник ли “Московского
долголетия”) автоматически, даже если он уже авторизован на MOS.ru. Таким
образом, на первом этапе взаимодействия с пользователем необходимо
запросить данные, которые позволят нам определить - является ли он
участником “Московского долголетия” или нет: ФИО, дату рождения.
В случае, если пользователь не является участником, мы должны
определить интересы и потребности посетителя и дать ему рекомендации
по группам (через предустановленные фильтры), причем желательно не
менее, чем в 3 разных ключевых направлениях (“для ума”, “для тела”, “для
души”) и одном дополнительном (допобразование с получением диплома,
получение новой профессии).
В случае, если мы идентифицировали действующего участника, мы
должны обратиться к истории его посещений и, учитывая ее (и/или иные
данные), предложить дополнительные занятия.

Занятия (группы) в “Московском долголетии” по формату проведения
делятся на две части:
а) очные занятия
б) онлайн-занятия
Таким образом, помимо направления занятий для очных групп мы
должны приоритетно предложить пользователям занятия, проходящие
максимально близко к месту его проживания. Приоритетным форматом в
“Московском долголетии “являются очные занятия, участникам хакатона при
проектировании рекомендательного сервиса предлагается учитывать этот
фактор и предложить механики, направленные на вовлечение
пользователей в оффлайн, даже если срез их интересов указывает на то, что
они склонны выбрать онлайн-уроки.
Исходные данные:
Список параметров фильтрации групп в сервисе записи:
● направления занятий (1,2,3 уровней)
● формат занятий (очно / онлайн)
● район занятий (для очных занятий)
● расписание (дни недели / время)
Список данных, содержащихся в датасете “Группы”:
● код группы
● направление 1
● направление 2
● направление 3
● адрес площадок (для онлайн-занятий имеет техническое
значение)
● округ площад
● район площадки
● расписание
Список данных, содержащихся в датасете “Пользователи”:
● уникальный номер
● дата создания личного дела
● пол
● дата рождения
● адрес проживания (детализация до многоквартирного дома)
Список данных, содержащихся в датасете “Посещаемость”:
● уникальный номер занятия
● уникальный номер группы
● уникальный номер участника
● онлайн/офлайн
● дата занятия
● время начала занятия
● время окончания занятия
