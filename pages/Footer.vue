<template>
    <footer>
        <div class="footer_columns">
            <div class="footer_column">
                <div class="footer_item header">О здоровом сне</div>
                <div class="footer_item"><a href="/">Блог Sleep Club</a></div>
                <div class="footer_item"><a href="/">Из чего состоит здоровье</a></div>
                <div class="footer_item"><a href="/">Сколько нужно спать</a></div>
                <div class="footer_item"><a href="/">Как улучшить свой сон</a></div>
                <div class="footer_item"><a href="/">Как обустроить спальню для здорового сна</a></div>
                <div class="footer_item"><a href="/">Безопасность детских товаров</a></div>
            </div>
            <div class="footer_column">
                <div class="footer_item header">Каталог</div>
                <div class="footer_item"><a href="/">Матрасы</a></div>
                <div class="footer_item"><a href="/">Кровати</a></div>
                <div class="footer_item"><a href="/">Диваны</a></div>
                <div class="footer_item"><a href="/">Наматрасники</a></div>
                <div class="footer_item"><a href="/">Подушки</a></div>
                <div class="footer_item"><a href="/">Одеяла</a></div>
                <div class="footer_item"><a href="/">Постельное белье</a></div>
                <div class="footer_item"><a href="/">Мебель для спальни</a></div>
                <div class="footer_item"><a href="/">Фотоотзывы</a></div>
            </div>
            <div class="footer_column">
                <div class="footer_item header">О компании</div>
                <div class="footer_item"><a href="/">Принципы и миссия</a></div>
                <div class="footer_item"><a href="/">Социальная политика</a></div>
                <div class="footer_item"><a href="/">История компании</a></div>
                <div class="footer_item"><a href="/">Производство</a></div>
                <div class="footer_item"><a href="/">Производство СИЗ</a></div>
                <div class="footer_item"><a href="/">Лаборатория сна</a></div>
                <div class="footer_item"><a href="/">Сертификаты</a></div>
                <div class="footer_item"><a href="/">Видеообзор продукции</a></div>
                <div class="footer_item"><a href="/">Новости</a></div>
                <div class="footer_item"><a href="/">Частые вопросы</a></div>
            </div>
            <div class="footer_column">
                <div class="footer_item header">Покупателям</div>
                <div class="footer_item"><a href="/">Дисконт-центр</a></div>
                <div class="footer_item"><a href="/">Акции и скидки</a></div>
                <div class="footer_item"><a href="/">Доставка и оплата</a></div>
                <div class="footer_item"><a href="/">Подарочные сертификаты</a></div>
                <div class="footer_item"><a href="/">Каталог тканей</a></div>
                <div class="footer_item"><a href="/">Как оформить заказ</a></div>
                <div class="footer_item"><a href="/">Гарантия</a></div>
                <div class="footer_item"><a href="/">Политика конфиденциальности</a></div>
                <div class="footer_item"><a href="/">Услуги</a></div>
                <div class="footer_item"><a href="/">Рассрочка</a></div>
                <div class="footer_item"><a href="/">Обмен и возврат товара</a></div>
                <div class="footer_item"><a href="/">Сроки изготовления</a></div>
            </div>
            <div class="footer_column">
                <div class="footer_item header">Партнерам</div>
                <div class="footer_item"><a href="/">Франчайзинг</a></div>
                <div class="footer_item"><a href="/">Предложение для отелей</a></div>
                <div class="footer_item"><a href="/">Оптовый каталог</a></div>
                <div class="footer_item"><a href="/">Международная кооперация</a></div>
                <div class="footer_item"><a href="/">Сотрудничество с дизайнерами и архитекторами</a></div>
                <div class="footer_item header">Контакты</div>
                <div class="footer_item"><a href="/">Контакты подразделений</a></div>
                <div class="footer_item"><a href="/">Оптовые продажи</a></div>
                <div class="footer_item header">Салоны</div>
                <div class="footer_city_and_sitemap">
                    <div class="footer_item"><a href="/">Красноярск</a></div>
                    <div class="footer_item"><a href="/">Карта сайта</a></div>
                </div>
            </div>
        </div>
        <div class="year_info_and_copyright">
            © 1990–{{ new Date().getFullYear() }}. ООО «ТД Аскона». Все права защищены.
        </div>
    </footer>
</template>
<style>
footer {
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    padding: 0 var(--container-padding);
    margin-top: 5rem;
}
.footer_columns {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: space-between;
}
.footer_column {
    display: flex;
    width: 18%;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: flex-start;
    align-items: flex-start;
}
.footer_item {
    margin-top: 0.5rem;
}
.header {
    font-weight: bold;
    margin-bottom: 0.5rem;
    margin-top: 2rem;
    pointer-events: none;
}
.footer_city_and_sitemap {
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    width: 100%;
}
.year_info_and_copyright {
    display: flex;
    align-items: center;
    height: 5rem;
}
</style>
