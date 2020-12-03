<template>
    <div class="navbar">
        <div class="navbar__menu">
            <ul class="navbar__nav">
                <li class="nav__item">
                    <nuxt-link class="nav_link" to="#">
                        Опросы
                    </nuxt-link>
                </li>
                <li class="nav__item">
                    <nuxt-link class="nav_link" to="#">
                        Пользователи
                    </nuxt-link>
                </li>
                <li class="nav__item">
                    <nuxt-link class="nav_link" to="#">
                        Черные списки
                    </nuxt-link> 
                </li>
                <li class="nav__item">
                    <nuxt-link class="nav_link" to="#">
                        Колл-центр
                    </nuxt-link>
                </li>
            </ul>
        </div>
    </div>
</template>

<style>
    .navbar {
        float: left;
    }
    .nav__item {
        list-style: none;
    }
</style>