<template>
  <section>
    <div class="container">
      <ul>
        <li>
          <a href="">
            <img src="../assets/images/buy-comics-digital-comics.png" alt="">
            DIGITAL COMICS
          </a>
        </li>
        <li>
          <a href="">
            <img src="../assets/images/buy-comics-merchandise.png" alt="">
            DC MERCHANDISE
          </a>
        </li>
        <li>
          <a href="">
            <img src="../assets/images/buy-comics-subscriptions.png" alt="">
            SUBSCRIPTION
          </a>
        </li>
        <li>
          <a href="">
            <img src="../assets/images/buy-comics-shop-locator.png" alt="">
            COMIC SHOP LOCATOR
          </a>
        </li>
        <li>
          <a href="">
            <img src="../assets/images/buy-dc-power-visa.svg" alt="">
            DC POWER VISA
          </a>
        </li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {
    name: "Section_services"
}
</script>

<style lang="scss" scoped>
@import "@/assets/style/variables";
section {
  background-color: $blue;
  height: 9.6875rem;
  color: white;
}

ul {
  list-style: none;
  display: flex;
  height: 100%;
  align-items: center;
  justify-content: space-evenly;
}



a {
  color: white;
  text-decoration: none;
  display: flex;
  align-items: center;
}

img {
  height: 3.4375rem;
  margin-right: 1.25rem ;
}
</style>