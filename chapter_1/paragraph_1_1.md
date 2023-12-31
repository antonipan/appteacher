## 1.1 Особенности разработки мобильных android-приложений

#### Обоснование разработки мобильного приложения.

На сегодняшний день мировой рынок мобильных приложений стремительно идёт вверх. Так в статье [###] сайта mindbox.ru приводятся следующие данные: 

На этом же сайте говорится, что среднее количество скачиваний на пользователя России составляет - . Для сравнения возьмём другие ведущие мировые страны: 

Получается, пользователь проводит в смартфоне очень много времени, что существенно увеличивает шансы на восстребованность нашего приложения. Тем более Россия уже не один год проводит политику импортозамещения, что повышает востребованность в отечественных айти-разработках. 

    *Таким образом, наша данное направление является очень перспективным для реализации нашего проекта.*

#### Выбор вида мобильного приложения

Чтобы оправдать собственные ожидания и экономно расходовать имеющиеся ресурсы при создании мобильного приложения, необходимо понимать, какой вид приложения мы хотим создать. 
Существуют следующие виды приложений:

1. **Нативные** (от англ. native - родственный) - приложения, которые разработаны под определённую платформу (родную). Для Android-прложений - это приложения, созданные в программе Andoid Studio, и написанные на языках java и kotlin (последний одобрила корпорация Google в 2019 году). Главными достоинствами нативных приложений являются 1) доступ ко все аппаратным возможностям устройства (камера, геолокация, датчики движения и т.д.) и 2) потенциально меньшее количество багов, 3) производительность, 4) лучшая кастомизация, 5) сбор и анализ пользовательских данных. Недостатком нативного приложения будут: длительность разработки, дороговизна. 

2. **Веб-приложения** - приложения, которые будут открываться браузером смартфона. По сути это веб-сайты, которые выглядят как мобильные приложения. Плюсы данных приложений: быстрая скорость разработки, совместимость с любой ОС, отсутствует согласованность с магазином. Недостатки: зависимость от интернет-трафика, низкая кастомизация, нет доступа к аппратной части устройства, сложнее поиск приложений в интернете. 

3. **Гибридные приложения** - приложения, которые сочетают в себе как функционал нативного приложения, так и использование веб-ресурсов. Выглядят и используются как нативные приложения, используют компонент для открытия веб-ресурсов (WebView). 

Преимущества:
- широкий функционал и высокая степень кастомизации;
- можно создать приложение, которое будет работать с несколькими платформами;
- удешевляют и ускоряют разработку MVP или несложного готового продукта для заказчиков;
- являются серединным решением между функционалом и производительностью нативного приложения и дешевизной веб-приложения.
Недостатки:
- слишком сложные приложения лучше делать нативными, как и приложения с громоздкими визуальными решениями вроде игр;
- разработка потребует больше времени и усилий, чтобы гибридное приложение выглядело и ощущалось как нативное;
- магазины приложений отклоняют недостаточно хорошо работающие гибридные приложения и важно соблюдать стандарты качества.

    *Таким образом, мы сделали обзор видов приложений и остановимся пока на нативном приложении.*

#### Выбор операционной системы. 

Мы решили свой выбор остановить на разработке мобильного приложения под android-ОС. И вот почему.

Android — это операционная система с открытым исходным кодом, основанная на ядре Linux и разработанная Google. Он используется в самых разных устройствах, включая смартфоны, планшеты, телевизоры и смарт-часы.

В настоящее время Android является самой используемой в мире операционной системой для мобильных устройств.  Согласно отчету Statcounter, за последние 12 месяцев доля Android на рынке составляет 71.96%.

Её основными преимуществами являются:
1. Количество пользователей. В 2020 году было зафиксировано 2,8 миллиарда активных пользователей Android, а доля этой системы на мировом рынке составила 75%.
2. Большие возможности. Система позволяет реализовать любые задумки, которые необходимо внедрить для удобства пользователей.
3. Доступная стоимость публикации. Чтобы выложить приложение в Google Play, нужен аккаунт разработчика
4. Скорость публикации. Публикация приложения в магазин занимает не более трёх суток, в отдельных ситуациях — неделю. Google Play не выдвигает специфических требований к функциональности приложения. Главное, чтобы оно не нарушало правила.

    *Таким образом, операционная система android, на наш взгляд, является оптимальной для вхождения в разработку мобильных приложений.*

#### Особенности разработки мобильных приложений

Разработка мобильных приложений - это динамичный процесс, требующий постоянного обучения и адаптации к новым технологиям и трендам. Успешная разработка требует подробного изучения платформы, тщательного планирования, тестирования и внимания к пользовательскому опыту. Вот основные особенности, отличающие ее от других видов разработки:
Android - это система, имеющая свои особенности, требования к программному обеспечению и набор инструментов. В процессе разработки необходимо учитывать: 
* адаптивность интерфейса к размеру и разрешению экрана и обеспечивать корректное отображение. Дело в том, что android-гаджеты - это самая распространнёная цифровая техника, которая отличается многообразием. Поэтому оптимизировать приложение под самые распространнённые экраны:
* Предыдущий пункт подходит и к версиям самой операционной системы. На осень 2023 года самыми популярными будут версии:
* Устройства имеют ограниченные ресурсы, такие как процессорная мощность, оперативная память и батарея. Очень неприятно, если приложение будет потреблять слишком много заряда батареи, или оперативной памяти будет не хватать. Тут нужно соблюсти баланс между быстродействием приложения и ёмкостью ресурсной системы и батареи.
* Приложение необходимо разрабатывть таким образом, чтобы пользовательский интерфейс был удобным и приятным, креативность и стандартизация пользовательского интерфейса также должна быть в балансе. При разработки UI также необходимо учитывать психологию человека. 
* Нужно обеспечить надежность и безопасность приложения, чтобы защитить персональные данные пользователя от несанкционированного доступа. И чем меньше приложение собирает персональные данные, тем лучше. 
* Приложения должны соответствовать определенным правилам и требованиям магазинов (Google Play, RuStore, AppGallery), чтобы быть опубликованными.
* Мобильные приложения могут быть спроектированы так, чтобы при необходимости работать в оффлайн-режиме.
* Мобильные устройства имеют широкий набор аппаратных возможностей, таких как камера, геолокация, акселерометр и датчики отпечатков пальцев. Можно использовать эти возможности для создания более интерактивного и функционального приложения.
* Мобильные платформы и устройства постоянно обновляются, поэтому необходимо обеспечивать поддержку своих приложений, выпуская регулярные обновления и исправления ошибок (по стандарту не реже одного раза в год).

Ещё более подробно с особенностями и требованиями к разработке мобильных приложений можно почитать (<span style='color:  yellow;'>здесь</span>). 

    *Таким образом, здесь представлены самые общие особенности разработки мобильных приложений без привязки к операционной системе. Их необходимо учитывать при создании нашего приложения.* 

Мы провели краткий обзор по особенностям и обосновали выбор направления разработки приложения для проверки знаний обучающихся: это нативное мобильное приложение, созданное на базе операцоинной системы Android с учётом особенностей создания мобильных приложений.


