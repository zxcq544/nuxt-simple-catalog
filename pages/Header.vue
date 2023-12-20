<script setup lang="ts"></script>
<template>
    <header>
        <div class="header_upper">
            <div class="corner">
                <a href="/">
                    <img src="/img/askona-logo.svg" alt="Askona" class="logo_img" />
                </a>
            </div>

            <div class="city"><a href="/">Москва</a></div>

            <div class="num_markets"><a href="/">74 салона</a></div>

            <div class="search">
                <input type="text" placeholder="Поиск" name="main_search_input" />
            </div>

            <div class="order_status"><a href="/">Статус заказа</a></div>
            <div class="login"><a href="/">Войти</a></div>
            <div class="compare"><a href="/">Сравнить</a></div>
            <div class="heart"><a href="/">Избранное</a></div>
            <div class="basket"><a href="/">Корзина</a></div>
            <!-- <nav>
			<ul>
				<li aria-current={$page.url.pathname === "/universal_product" ? "page" : undefined}>
					<a href="/universal_product?group_id=1&color=Белый премиум&size=140*200">
						Universal Product
					</a>
				</li>
			</ul>
		</nav> -->
        </div>
        <div class="header_lower">
            <div class="product_types">
                <a class="product_type" href="/category/bed">Кровати</a>
                <a class="product_type" href="/category/matras">Матрасы</a>
                <a class="product_type" href="/">Диваны и кресла</a>
                <a class="product_type" href="/">Подушки и одеяла</a>
                <a class="product_type" href="/">Текстиль и одежда</a>
                <a class="product_type" href="/">Для детей</a>
                <a class="product_type" href="/">Мебель</a>
                <a class="product_type" href="/">Для здоровья</a>
            </div>
            <div class="call_me">
                <div class="number"><a href="/">8 800 200-40-90</a></div>
                <div><a class="call_me_action" href="/">перезвоните мне</a></div>
            </div>
        </div>
    </header>
</template>
<style>
header {
    display: flex;
    flex-direction: column;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
}

.header_upper {
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    flex-wrap: nowrap;
    align-items: center;
    height: 3.6rem;
    border-bottom: 1px solid #f2f2f2;
    padding: 0 var(--container-padding);
}
.header_lower {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    height: 3.6rem;
    padding: 0 var(--container-padding);
    border-bottom: 1px solid #eee;
    box-sizing: border-box;
}

.product_types {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: space-between;
    align-items: center;
    width: 85%;
    height: 100%;
}

.product_type {
    display: flex;
    height: 100%;
    align-items: center;
}
.call_me {
    display: flex;
    width: 10%;
    flex-direction: column;
}

.number {
    font-weight: bold;
}
.call_me_action {
    font-size: smaller;
    border-bottom: 1px dashed;
}

.corner {
    width: 10rem;
    height: 3rem;
}

.corner a {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100%;
}

.search {
    width: 35%;
    height: 70%;
    display: flex;
}
.search input {
    width: 100%;
    border-radius: 0.5rem;
    border: 1px solid #bbb;
    padding-left: 2rem;
}

.search input:focus {
    border: 1px solid #00b9bf;
    outline: none;
}

.logo_img {
    width: 100%;
    height: 100%;
}
</style>
