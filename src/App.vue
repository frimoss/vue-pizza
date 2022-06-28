<template>
  <div>
    <Header></Header>
    <div class="content">
      <div class="container">
        <PizzaCategories></PizzaCategories>
        <PizzaList></PizzaList>
      </div>
    </div>

  </div>

</template>

<script>
import Header from "@/components/Header";
import PizzaCategories from "@/components/PizzaCategories";
import PizzaList from "@/components/PizzaList";

export default {
  name: 'App',
  components: {
    Header,
    PizzaCategories,
    PizzaList
  }
}
</script>

<style>
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  list-style: none;
  font-family: Nunito,Roboto,system-ui,Tahoma,sans-serif;
}
html {
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
}
a {
  text-decoration: none;
}
a, b, body, h1, h2, h3, h4, h5, p, span {
  color: #232323;
}
h2 {
  font-size: 28px;
  font-weight: 600;
  line-height: 30px;
}
.container {
  max-width: 1200px;
  margin: 0 auto;
}
.content {
  padding: 40px 0;
}
</style>
