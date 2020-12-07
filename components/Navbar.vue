<template>
  <div class="navbar">
    <ul class="navbar__menu">
      <li class="nav__item">
        <nuxt-link class="nav_link" to="/">
          Опросы
        </nuxt-link>
      </li>
      <li class="nav__item">
        <nuxt-link class="nav_link" to="/users">
          Пользователи
        </nuxt-link>
      </li>
      <li class="nav__item">
        <nuxt-link class="nav_link" to="/blackList">
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
</template>

<style>
    .navbar {
        float: left;
    }
    .nav__item {
        list-style: none;
    }
    .nav__item {
      width: 150px;
      height: 100px;
      border: 1px solid #000;
      margin-bottom: 15px;
      border-radius: 10px;
      text-align: center;
    }
    .nav__item:hover {
      border: 3px solid green;
    }
</style>