<template>
  <form class="form-signin">
  <h1 class="h3 mb-3 font-weight-normal">Please log in</h1>
  <label for="inputEmail" class="sr-only">Email address</label>
  <input type="email" id="inputEmail" class="form-control" placeholder="Email address" required="" autofocus="">
  <label for="inputPassword" class="sr-only">Password</label>
  <input type="password" id="inputPassword" class="form-control" placeholder="Password" required="">
  <div class="checkbox mb-3">
    
  </div>
  <button class="btn btn-lg btn-primary btn-block" type="submit">Sign in</button>

</form>
</template>

  <script>
export default {
  name: 'UserManage',
  props: {
    msg: String
  }
}
</script>

<style>
.form-signin {
    width: 100%;
    max-width: 330px;
    padding: 15px;
    margin: auto;
}
</style>
     