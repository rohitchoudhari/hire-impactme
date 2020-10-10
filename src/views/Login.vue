<template>
    <br>
    <section class="section">
        <div class="container">
            <h3 class="title is-3 has-text-centered">Log In</h3>
            <div class="columns is-centered">
                <div class="column is-5">
                  <form action="" class="box">
                    <div class="field">
                      <label for="" class="label">Email</label>
                      <div class="control">
                        <input name="email" class="input is-small" type="email" placeholder="Email" required>
                      </div>
                    </div>
                    <div class="field">
                      <label for="" class="label">Password</label>
                      <div class="control">
                        <input name="password" type="password" placeholder="*******" class="input is-small" required>
                      </div>
                    </div>
                    <div class="field">
                      <label for="" class="checkbox">
                        <input type="checkbox">
                       Remember me
                      </label>
                    </div>
                    <div class="field">
                      <button class="button is-success">
                        Log In
                      </button>
                      <a class="button" href="/signup">Sign Up</a>
                    </div>
                  </form>
                </div>
              </div>
              <p></p>
        </div>
        
    </section>
</template>



<script>
export default {
    name: 'Login'
}
</script>