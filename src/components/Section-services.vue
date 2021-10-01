<template>
  <section>
    <div class="container">
      <ul>
        <li v-for="(service, index) in services" :key="index">
          <a href="#">
            <img :src="service.path" alt="">
            {{service.text}}
          </a>
        </li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {
    name: "Section_services",
    data() {
      return {
        services:[
          {
            text: "DIGITAL COMICS",
            path: "images/buy-comics-digital-comics.png",
            url: "#"
          },
          {
            text: "DC MERCHANDISE",
            path: "images/buy-comics-merchandise.png",
            url: "#" 
          },
          {
            text: "SUBSCRIPTION",
            path: "images/buy-comics-subscriptions.png",
            url: "#" 
          },
          {
            text: "COMIC SHOP LOCATOR",
            path: "images/buy-comics-shop-locator.png",
            url: "#" 
          },
          {
            text: "DC POWER VISA",
            path: "images/buy-dc-power-visa.svg",
            url: "#" 
          },
        ]
      }
    },
}
</script>

<style lang="scss" scoped>
@import "../assets/style/variables";
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