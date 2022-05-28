<template>
  <h1>ТАБЛИЦА</h1>
  <table class="table">
    <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
    </thead>
    <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>Vladimir</td>
      <td>Qwerty</td>
      <td>@321</td>
    </tr>
    <tr>
      <th scope="row">5</th>
      <td>ZxC</td>
      <td>Q3532ty</td>
      <td>@google</td>
    </tr>
    </tbody>
  </table>
</template>

<script>
export default {
  name: "TablePanel"

}
</script>

<style scoped>
.table{
  position: fixed;
  left: 20%;
  top: 30%;
  width: 60%;
}
</style>