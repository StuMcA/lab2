<template>
  <menuBar />
  <router-view></router-view>
  <div class="center-bar">
    <footer>
        <p style="text-align:center">Copyright &copy; 2023 - F28IR</p>
    </footer>
  </div>
</template>

<script>
  import menuBar from '@/components/menuBar.vue';
  import productsPage from './pages/productsPage.vue';
  import HomePage from './pages/homePage.vue';
  export default {
    name: 'App',
    components: { menuBar }
  }

</script>

<style>

</style>