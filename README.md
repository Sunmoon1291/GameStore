# GameStore
Это решение реализует интернет-магазин компьютерных игр, который представляет из себя онлайн
каталог товаров, который пользователи могут просматривать по категориям и страницам, корзину для
покупок, куда пользователи могут добавлять и удалять товары, и форму оплаты, где пользователи могут
вводить сведения, связанные с доставкой. Кроме того, реализована административная область, которая
включает в себя средства создания, чтения, обновления и удаления для управления каталогомтоваров,
и защищенная таким образом, чтобы изменения могли вносить только зарегистрированные администраторы.
Решение реализовано с помощью ASP.NET MVC 5 и включает в себя три проекта:
- GameStore.Domain содержит классы предметной области.
- GameStore.WebUI содержит контроллеры и представления; выступает в качестве пользовательского.
интерфейса для для интернет-магазина.
- GameStore.UnitTests содержит модульные тесты для других двух проектов.