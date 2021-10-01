<template>
  <header>
    <div class="container">
      <img src="../assets/images/dc-logo.png" alt="" />
      <nav>
        <ul>
            <li v-for="(link, index) in menu" :key="index">
                <a :class="{active : link.current}" href="link.url">{{link.text}}</a>
            </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      menu: [
        {
          text: "CHARACTERS",
          url: "#",
          current: false,
        },
        {
          text: "COMICS",
          url: "#",
          current: true,
        },
        {
          text: "MOVIES",
          url: "#",
          current: false,
        },
        {
          text: "TV",
          url: "#",
          current: false,
        },
        {
          text: "GAMES",
          url: "#",
          current: false,
        },
        {
          text: "COLLECTIBLES",
          url: "#",
          current: false,
        },
        {
          text: "VIDEOS",
          url: "#",
          current: false,
        },
        {
          text: "FANS",
          url: "#",
          current: false,
        },
        {
          text: "NEWS",
          url: "#",
          current: false,
        },
        {
          text: "SHOP",
          url: "#",
          current: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/style/variables";
header {
  height: 7.5rem;
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  img {
    width: 5rem;
    height: 5rem;
  }

  ul {
    list-style: none;
    display: flex;
  }

  li {
    margin: 0 20px;
  }

  a {
    color: $darkGrey;
    text-decoration: none;
    font-weight: 600;
    padding: 2.8125rem 0;
    &:active {
      border-bottom: 5px solid $blue;
    }
  }
}
</style>