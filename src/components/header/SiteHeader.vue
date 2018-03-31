<template>
  <header class="site-header">
    <HeaderLogo/>
    <HeaderMenu/>
  </header>
</template>

<script>
import HeaderLogo from './HeaderLogo';
import HeaderMenu from './HeaderMenu';

export default {
  name: 'Header',
  components: {
    HeaderLogo,
    HeaderMenu,
  },
};
</script>

<style lang="scss">
.site-header {
  display: flex;
  align-items: center;
  background: #144852;
  height: 50px;
  padding: 0 40px;
}
</style>
