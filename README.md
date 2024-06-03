# memento

## Описание проекта 
Memento - мобильная и веб-платформа, помогающая учиться быстро и эффективно. Функциональность платформы основана на таких популярных образовательных техниках, как метод петля запоминания и корнелльская система записи 

Функциональность приложения основана на концепции флэш-карточек. Пользователь, изучающий какой-то материал может создать по этому материалу Карточку. Карточка представляет собой список вопросов по изучаемой теме. На каждый вопрос пользователь оставляет развернутый ответ. Карточки же в свою очередь могут формироваться в связанные по смыслу группы для обеспечения удобства структурирования и навигации. Затем в определенные промежутки времени пользователю приходят уведомления о том, что ему необходимо повторить какую-то Карточку. В процессе повторения пользователю придется ответить на оставленные им к данной теме вопросы. 

Помимо этого в приложение интегрирована система геймификации: за правильные ответы пользователи получают очки, из которых формируется их рейтинг. 

Таким образом, приложение стимулирует пользователя формулировать изучаемый им материал в контексте простых вопросов и ответов на них, что побуждает к дополнительному структурированию и пониманию материала. А соревновательный элемент системы геймификации стимулирует пользователей к более активному повторению материала.  

## Содержание репозитория 
Данный репозиторий содержит: 
- backend-систему, написанную на языке golang
- мобильное приложение для ОС Android, написанное при помощи языков Kotlin и Java
- [frontend-систему](https://github.com/FilBTi/memento-web), разработанную при помощи js

## Техническое задание 
- [ТЗ на систему](https://www.notion.so/f908d65e54734f38aa26cc5636e7a58d) ( Notion )
- [ТЗ на мобильное приложение](https://www.notion.so/Memento-MVP-5cb9628232044478bf6324f2047c8e3e) ( Notion ) 

## Дизайн-система 
1. [Мобильная версия для iOS](https://www.figma.com/design/1g3dpx5jVcydxGjsJO8dfo/memento?node-id=1103-2632&t=sXBfIqkRCXtekC9x-0) ( Figma )
2. [Мобильная версия для Android](https://www.figma.com/design/1g3dpx5jVcydxGjsJO8dfo/memento?node-id=1102-3&t=sXBfIqkRCXtekC9x-0) ( Figma ) 
3. [Web](https://www.figma.com/design/1g3dpx5jVcydxGjsJO8dfo/memento?node-id=1102-4&t=sXBfIqkRCXtekC9x-0) ( Figma ) 

## Средства разработки 
- backend-система выполнена на языке Golang с использованием таких фрейморков и библиотек, как: gin, cleanenv, pg, testify. В качестве СУБД используется PostgreSQL16
- мобильное приложение разработано для ОС Android на языке Kotlin с использованием таких технологий как: dagger2 , room, navigation component, coroutines, fastadapter
- frontend-система разработана на языке javascript с применением фреймворка React.

## Команда 
- Циминтия Николай Артурович, backend-разработчик.
- Шляхов Денис Олегович, Android-разработчик.
- Косенко Филипп Евгеньевич, frontend-разработчик, QA-инженер.
- Тишалович Леонид Михайлович, project-manager.
- Пластун Елизавета Олеговна, UI/UX дизайнер.

## Конференции 
-  53 конференция ППС (доклад, тезисы), "Разработка информационной системы для повышения эффективности образовательного процесса"
-  XIII Конгресс молодых ученых ИТМО (доклад, тезисы), "Разработка информационной системы для повышения эффективности образовательного процесса"
