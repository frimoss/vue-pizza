<template>
  <div>
    <h2 class="content__title">Все пиццы</h2>
    <div class="content__items">
      <PizzaItem></PizzaItem>

<!--      <div class="pizza-block-wrapper">-->
<!--        <div class="pizza-block">-->
<!--          <a href="#">-->
<!--            <img class="pizza-block__image" src="https://dodopizza-a.akamaihd.net/static/Img/Products/bf3377af7cfe4962915668d14bb8d0f4_584x584.jpeg" alt="Pizza">-->
<!--            <h4 class="pizza-block__title">Пепперони</h4>-->
<!--            <p>Пикантная пепперони, увеличенная порция моцареллы, томатный соус</p>-->
<!--          </a>-->
<!--          <div class="pizza-block__bottom">-->
<!--            <div class="pizza-block__price">от 419 ₽</div>-->
<!--            <button class="button button&#45;&#45;outline button&#45;&#45;add">-->
<!--              <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">-->
<!--                <path d="M10.8 4.8H7.2V1.2C7.2 0.5373 6.6627 0 6 0C5.3373 0 4.8 0.5373 4.8 1.2V4.8H1.2C0.5373 4.8 0 5.3373 0 6C0 6.6627 0.5373 7.2 1.2 7.2H4.8V10.8C4.8 11.4627 5.3373 12 6 12C6.6627 12 7.2 11.4627 7.2 10.8V7.2H10.8C11.4627 7.2 12 6.6627 12 6C12 5.3373 11.4627 4.8 10.8 4.8Z" fill="white"></path>-->
<!--              </svg>-->
<!--              <span>Добавить</span>-->
<!--            </button>-->
<!--          </div>-->
<!--        </div>-->
<!--      </div>-->

    </div>
  </div>
</template>

<script>
import PizzaItem from "@/components/PizzaItem";
export default {
  name: 'PizzaList',
  components: {
    PizzaItem
  }
}
</script>

<style scoped>
.content__title {
  font-size: 38px;
  font-weight: 800;
  margin-bottom: 50px;
  margin-top: 60px;
}

.content__items {
  grid-column-gap: 11px;
  display: grid;
  grid-template-columns: repeat(4,1fr);
  grid-template-rows: repeat(1,1fr);
}

</style>