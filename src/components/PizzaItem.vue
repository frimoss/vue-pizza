<template>
  <div class="pizza-block-wrapper">
    <div class="pizza-block">
      <a href="#">
        <img class="pizza-block__image" src="https://dodopizza.azureedge.net/static/Img/Products/Pizza/ru-RU/d48003cd-902c-420d-9f28-92d9dc5f73b4.jpg" alt="Pizza">
        <h4 class="pizza-block__title">Маргарита</h4>
        <p>Увеличенная порция моцареллы, итальянские травы, томатный соус</p>
      </a>
      <div class="pizza-block__bottom">
        <div class="pizza-block__price">от 369 ₽</div>
        <button class="button button--outline button--add">
          <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M10.8 4.8H7.2V1.2C7.2 0.5373 6.6627 0 6 0C5.3373 0 4.8 0.5373 4.8 1.2V4.8H1.2C0.5373 4.8 0 5.3373 0 6C0 6.6627 0.5373 7.2 1.2 7.2H4.8V10.8C4.8 11.4627 5.3373 12 6 12C6.6627 12 7.2 11.4627 7.2 10.8V7.2H10.8C11.4627 7.2 12 6.6627 12 6C12 5.3373 11.4627 4.8 10.8 4.8Z" fill="white"></path>
          </svg>
          <span>Добавить</span>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.pizza-block-wrapper {
  display: flex;
  justify-content: center;
}
.pizza-block {
  margin-bottom: 65px;
  text-align: center;
  transition: all .2s ease-in-out;
  width: 280px;
}
.pizza-block__image {
  width: 95%;
  margin: 5% 0px 0px 5%;
}
.pizza-block__title {
  font-size: 22px;
  line-height: 24px;
  font-weight: 800;
  margin-bottom: 10px;
}
.pizza-block p {
  font-size: 15px;
  line-height: 20px;
  color: rgb(92, 99, 112);
  font-weight: 400;
}

.pizza-block__bottom {
  align-items: center;
  display: flex;
  justify-content: space-between;
  margin-top: 20px;
}
.pizza-block__price {
  font-size: 22px;
  font-weight: 700;
  letter-spacing: .015em;
  line-height: 27px;
}

.button {
  -webkit-touch-callout: none;
  background-color: #fe5f1e;
  border: 1px solid transparent;
  border-radius: 30px;
  cursor: pointer;
  display: inline-block;
  min-width: 100px;
  padding: 10px 20px;
  text-align: center;
  transition: background-color .15s ease-in-out,border-color .15s ease-in-out;
  -webkit-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.button:hover {

}

.button, .button span {
  color: #fff;
}
.button--outline {
  background-color: #fff;
  border-color: #fe5f1e;
}
.button--outline, .button--outline span {
  color: #fe5f1e;
}

.button--add svg {
  margin-right: 2px;
}
.button i, .button path, .button span, .button svg {
  transition: all .15s ease-in-out;
}
.button--add span {
  font-size: 16px;
  font-weight: 600;
}
.button--outline svg path {
  fill: #fe5f1e;
}
</style>