<template>
  <div class="nav">
  <v-button @click="$router.push('/')">Главная страница; </v-button>
  <v-button @click="$router.push('/log')">Авторизация; </v-button>
  <v-button @click="$router.push('/tab')">Таблица;</v-button>
  </div>
</template>

<script>
export default {
  name: "HeaderPnl"
}
</script>

<style scoped>
.nav{
  display: inline-table;
  text-transform: uppercase;
  font-size: 18px;
  padding-right: 10px;
  white-space: nowrap;
}
</style>