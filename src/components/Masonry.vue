<template>
  <div class="container">
    <div class="box-1">
        <img class="img" src='https://cdn.ascgroup.ru/news_media/13099/ACH02568.jpg'>
    </div>
    <div class="box-2">
        <img class="img" src='https://cdn.ascgroup.ru/news_media/13099/ACH02578.jpg'>
    </div>
    <div class="box-3">
        <img class="img" src='https://cdn.ascgroup.ru/news_media/13099/ACH02602.jpg'>
    </div>
    <div class="box-4">
        <img class="img" src='https://cdn.ascgroup.ru/news_media/13099/ACH02671.jpg'>
    </div>
    <div class="box-5">
        <img class="img" src='https://cdn.ascgroup.ru/news_media/13099/ACH02674.jpg'>
    </div>
    <div class="box-6">
        <img class="img" src='https://cdn.ascgroup.ru/news_media/13099/ACH02715.jpg'>
    </div>
  </div>
</template>
<style scoped lang="scss">
.container {
  display: grid;
  height: 100vh;
  grid-template-areas:
    "A A A A   A A A A   C C C C"
    "B B B B   D D D D   C C C C"
    "E E E E   E E E E   F F F F";
  grid-gap: 10px;
    .box-1 {
      grid-area: A;
      position: relative;
    }
    .box-2 {
      grid-area: B;
      position: relative;
    }
    .box-3 {
      grid-area: C;
      position: relative;
    }
    .box-4 {
      grid-area: D;
      position: relative;
    }
    .box-5 {
      grid-area: E;
      position: relative;
    }
    .box-6 {
      grid-area: F;
      position: relative;
    }
  .img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    position: absolute;
  }
}
</style>