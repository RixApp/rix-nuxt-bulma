<template>
  <div>
    <div class="card login-card-custom">
      <div class="card-content">
        <p class="title">
          Rix
        </p>
        <p class="subtitle">
          Log In
        </p>
        <div class="field">
          <label class="label">Email</label>
          <div class="control">
            <input class="input" type="email" placeholder="example@gmail.com">
          </div>
        </div>

        <div class="field">
          <label class="label">Password</label>
          <div class="control">
            <input class="input" type="password" placeholder="*********">
          </div>
          <!-- <div class="control has-icons-left has-icons-right">
            <input class="input is-danger" type="password" placeholder="*********">
            <span class="icon is-small is-left">
              <i class="fas fa-envelope"></i>
            </span>
            <span class="icon is-small is-right">
              <i class="fas fa-exclamation-triangle"></i>
            </span>
          </div>
          <p class="help is-danger">This email is invalid</p> -->
        </div>

        <div class="field">
          <div class="control">
            <label class="checkbox">
              <input type="checkbox">
              I agree to the <a href="#">terms and conditions</a>
            </label>
          </div>
        </div>

        <div class="field is-grouped">
          <div class="control">
            <button class="button is-link">Submit</button>
          </div>
          <div class="control">
            <button class="button is-link is-light">Cancel</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
</script>
<style scoped>
.login-card-custom {
  max-width: 85%!important;
}
</style>
