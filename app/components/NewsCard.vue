<template>
  <div class="news-card">
    <h3 class="news-card__title">Первые земельные участки реализованы на специальных торгах для малого и среднего бизнеса</h3>
    <div class="news-card__description">На каждый участок претендовали в среднем шесть участников. Стоимость одной из сделок выросла в ходе аукциона в 26 раз.</div>
    <div class="news-card__link">Подробнее</div>
    <div class="news-card__bottom">
      <div class="news-card__original">mos.ru</div>
      <div class="news-card__date">12.01.2020</div>
    </div>
  </div>
</template>

<script lang="ts" setup>

</script>

<style lang="less" scoped>
.news-card {
  padding: 30px;
  border-radius: 3px;
  box-shadow: 
    0 1px 4px 0 rgba(0, 0, 0, 0.05),
    0 2px 4px 0 rgba(0, 0, 0, 0.05);
}
.news-card__title {
  font-size: 18px;
  line-height: 22px;
  color: var(--main-color);
}
.news-card__description {
  margin-top: 25px;
  font-size: 14px;
  line-height: 20px;
}
.news-card__link {
  margin-top: 20px;
  font-size: 14px;
  line-height: 20px;
  text-decoration: underline;
  color: var(--main-color);
}
.news-card__bottom {
  margin-top: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.news-card__original,
.news-card__date {
  font-size: 14px;
  line-height: 20px;
  color: var(--gray-color);
}
</style>