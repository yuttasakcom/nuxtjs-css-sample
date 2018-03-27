<template>
  <header class="main-header">
    <div>
        <a href="" class="main-header__brand">uHost</a>
      </div>
    <nav class="main-nav">
      <ul class="main-nav__items">
        <li class="main-nav__item"><a href="">Package</a></li>
        <li class="main-nav__item"><a href="">Order</a></li>
        <li class="main-nav__item main-nav__item--cta"><a href="">Start Hosting</a></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
.main-header {
  width: 100%;
  background: #2ddf5c;
  padding: 8px 16px;
}

.main-header > div {
  display: inline-block;
  vertical-align: middle;
}

.main-header__brand {
  color: #0e4f1f;
  text-decoration: none;
  font-weight: bold;
  font-size: 22px;
}

.main-nav {
  display: inline-block;
  text-align: right;
  width: calc(100% - 74px);
}

.main-nav__items {
  margin: 0;
  padding: 0;
  list-style: none;
}

.main-nav__item {
  display: inline-block;
  margin: 0 16px;
}

.main-nav__item--cta a {
  color: white;
  background: #ff1b68;
  padding: 8px 16px;
  border-radius: 8px;
}

.main-nav__item--cta a:hover,
.main-nav__item--cta a:active {
  color: #ff1b68;
  background: white;
  border: none;
}

.main-nav__item a {
  text-decoration: none;
  color: #0e4f1f;
  font-weight: bold;
  padding: 3px;
}

.main-nav__item a:hover,
.main-nav__item a:active {
  color: white;
  border-bottom: 5px solid white;
}

.main-nav__item--cta a {
  color: white;
  background: #ff1b68;
  padding: 8px 16px;
  border-radius: 8px;
}

.main-nav__item--cta a:hover,
.main-nav__item--cta a:active {
  color: #ff1b68;
  background: white;
  border: none;
}
</style>
