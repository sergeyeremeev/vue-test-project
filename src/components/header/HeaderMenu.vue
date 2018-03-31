<template>
  <nav class="site-menu">
    <ul>
      <li v-for="item in menuItems" :key="item.url">
        <a :href="item.url"><img :src="item.icon" alt="">{{item.text}}</a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'HeaderMenu',
  data() {
    return {
      menuItems: [
        {
          text: 'Policies',
          icon: '',
          url: '/policies',
        },
        {
          text: 'Claims',
          icon: '',
          url: '/claims',
        },
      ],
    };
  },
};
</script>

<style lang="scss">
.site-menu {
  height: 40px;
  width: auto;
  display: flex;
  align-items: center;

  ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    color: #fff;

    li {
      display: inline-block;
      margin-right: 10px;
    }
  }
}
</style>
