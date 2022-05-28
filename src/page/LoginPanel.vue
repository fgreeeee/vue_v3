<template>
  <h1>LOGIN</h1>
  <div class="log">
    <form>
      <div class="mb-3">
        <label for="exampleInputEmail1" class="form-label">Email Адрес</label>
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
      </div>
      <div class="mb-3">
        <label for="exampleInputPassword1" class="form-label">Пароль</label>
        <input type="password" class="form-control" id="exampleInputPassword1">
      </div>
      <div class="mb-3 form-check">
        <input type="checkbox" class="form-check-input" id="exampleCheck1">
        <label class="form-check-label" for="exampleCheck1">Запомнить меня</label>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "LoginPanel"
}
</script>

<style scoped>
.log{
  position: fixed;
  left: 30%;
  top: 30%;
  width: 40%;

}
</style>