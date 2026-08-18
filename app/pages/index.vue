<template>
  <div class="index-page global-container">
    <div class="index-page__header">
      <h1 class="index-page__title">Список новостей</h1>
      <div class="index-page__search">Поиск</div>
    </div>
    <div class="index-page__controls">
      <div class="index-page__tabs">
        <div class="index-page__tab">Все</div>
        <div class="index-page__tab">Lenta</div>
      </div>
      <div class="index-page__view">
        view
      </div>
    </div>
    <div class="index-page__list">
      <NewsCard />
      <NewsCard />
      <NewsCard />
      <NewsCard />
    </div>
    <div class="index-page__pagination">
      <div class="index-page__page index-page__page--active">1</div>
      <div class="index-page__page">2</div>
      <div class="index-page__page">3</div>
      <div class="index-page__page">...</div>
      <div class="index-page__page">200</div>
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style lang="less" scoped>
.index-page__title {
  font-size: 36px;
  font-weight: bold;
}
.index-page__controls,
.index-page__header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.index-page__controls {
  margin-top: 63px;
}
.index-page__tabs {
  display: flex;
  gap: 10px;
}
.index-page__list {
  margin-top: 28px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
}
.index-page__pagination {
  margin-top: 50px;
  display: flex;
  justify-content: center;
  gap: 10px;
}
.index-page__page {
  font-weight: bold;
  font-size: 18px;
  line-height: 100%;
}
.index-page__page--active {
  color: var(--main-color);
}
</style>
