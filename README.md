# SocialMedia
(тестовое задание)

**Возможности**:
- Аутентификация и авторизация:
  * Пользователи могут зарегистрироваться, указав имя пользователя, электронную почту и пароль.
  * Пользователи могут войти в систему, предоставив правильные учетные данные.
  * API обеспечивает защиту конфиденциальности пользовательских данных, включая хэширование паролей и использование JWT.
- Обработка ошибок:
  * API возвращает понятные сообщения об ошибках при неправильном запросе или внутренних проблемах сервера
  * API осуществляет валидацию введенных данных и возвращает информативные сообщения при неправильном формате
- Управление постами:
  * Пользователи могут создавать новые посты, указывая текст, заголовок и прикрепляя изображения
  * Пользователи могут просматривать посты других пользователей
  * Пользователи могут обновлять и удалять собственные посты
- Взаимодействие пользователей:
  * Пользователи могут добавлять в друзья. До момента подтверждения заявки, пользователь остается в подписчиках,
    пока сам не отменит подписку


**Реализовать**:
- Взаимодействие пользователей:
  * Друзья должны быть подписчиками друг друга
  * Если один друг удаляет другого - он также от него отписывается. Второй остается в подписчиках
  * Друзья могут писать друг другу сообщения
- Подписки и лента активности:
  * Лента активности пользователя должна отображать последние посты от
    пользователей, на которых он подписан
  * Лента активности должна поддерживать пагинацию и сортировку по
    времени создания постов
- Документация API:
  * API должно быть хорошо задокументировано с использованием
    инструментов, таких как Swagger или OpenAPI
  * Документация должна содержать описания доступных эндпоинтов,
    форматы запросов и ответов, а также требования к аутентификации

**Технологии и инструменты**:
- Язык программирования: Java 17
- Фреймворк: Spring Boot
- База данных: PostgreSQL
- Аутентификация и авторизация: Spring Security
- Документация API: Swagger или OpenAPI (to be decided)

