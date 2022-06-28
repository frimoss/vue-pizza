<template>
  <div class="content__top">
    <div class="categories">
      <ul>
        <li class="active">Все</li>
        <li class="">Мясные</li>
        <li class="">Вегетарианская</li>
        <li class="">Гриль</li>
        <li class="">Острые</li>
        <li class="">Закрытые</li>
      </ul>
    </div>
    <div class="sort">
      <div class="sort__label">
        <svg width="10" height="6" viewBox="0 0 10 6" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M10 5C10 5.16927 9.93815 5.31576 9.81445 5.43945C9.69075 5.56315 9.54427 5.625 9.375 5.625H0.625C0.455729 5.625 0.309245 5.56315 0.185547 5.43945C0.061849 5.31576 0 5.16927 0 5C0 4.83073 0.061849 4.68424 0.185547 4.56055L4.56055 0.185547C4.68424 0.061849 4.83073 0 5 0C5.16927 0 5.31576 0.061849 5.43945 0.185547L9.81445 4.56055C9.93815 4.68424 10 4.83073 10 5Z" fill="#2C2C2C"></path>
        </svg>
        <b>Сортировка по:</b>
        <span>популярности</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.content__top {
  align-items: center;
  display: flex;
  justify-content: space-between;
}
.categories ul {
  display: flex;
}
.categories ul li {
  -webkit-touch-callout: none;
  background-color: #f9f9f9;
  border-radius: 30px;
  cursor: pointer;
  font-weight: 700;
  margin-right: 10px;
  padding: 13px 30px;
  transition: background-color .1s ease-in-out;
  -webkit-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.categories ul li.active {
  background-color: #282828;
  color: #fff;
}

.sort__label {
  align-items: center;
  display: flex;
}
.sort__label b, .sort__label svg {
  margin-right: 8px;
}
.sort__label span {
  border-bottom: 1px dashed #fe5f1e;
  color: #fe5f1e;
  cursor: pointer;
}
</style>