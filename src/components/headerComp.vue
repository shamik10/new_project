<template>
  <div class="header container">
    <div class="header-inner">
      <router-link to="/">КФС</router-link>
      <nav class="header-nav">
        <ul class="header-nav__items">
          <li class="header-nav__item">
            <router-link to="/">
              Меню
            </router-link>
          </li>
          <li class="header-nav__item">
            <router-link to="/">
              Купоны
            </router-link>
          </li>
          <li class="header-nav__item">
            <router-link to="/">
              Акции
            </router-link>
          </li>
          <li class="header-nav__item">
            <router-link to="/">
              Рестораны
            </router-link>
          </li>
          <li class="header-nav__item">
            <router-link to="/">
              Работа у нас 
            </router-link>
          </li>
        </ul>
      </nav>
    </div>
    <router-link to="/" >
      
      <button class="header-btn">
        Войти
      </button>
    </router-link>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  .header {
    display: flex;
    justify-content: space-between;
  }

  .header-inner {
    display: flex;
    gap: 50px;
  }

  .header-nav__items {
    display: flex;
    gap: 30px;
  }
</style>