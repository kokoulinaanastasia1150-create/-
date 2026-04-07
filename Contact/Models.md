| Свойство | Тип |	Валидация |
| --- | --- | ---|
| Id	| int	| Автоинкремент |
| FullName	| string	| Не пустое, минимум 2 символа |
| PhoneNumber	| string	| Формат: +7XXXXXXXXXX или 8XXXXXXXXXX или XXXXXXXXXX (10 цифр) | 
| Email	| string	| Должен содержать @ и . (может быть пустым) | 
| Category	| string	| Одно из: Семья, Работа, Друзья, Другое |
| CreatedAt	| DateTime	| Дата создания (устанавливается автоматически) |
