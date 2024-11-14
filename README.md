Проект основан на Spring Framework совместно со Spring Boot. 

Основная функциональность Later — сохранение ссылок для последующего просмотра. Важно, чтобы пользователь мог легко сохранить ссылку и впоследствии так же легко найти её в приложении. Поэтому API такой:
GET /items — поиск сохранённых ссылок;
POST /items — сохранение новой ссылки;
DELETE /items/{itemId} — удаление ранее сохранённой ссылки с идентификатором itemId.