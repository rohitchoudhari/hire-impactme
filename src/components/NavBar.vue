<template>

  <nav class="navbar is-spaced is-light is-fixed-top" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="/">
        <img src="/images/impactme_logo.png" width="111" height="30">
      </a>
    </div>
  
    <div id="navbarBasicExample" class="navbar-menu">
      <div class="navbar-start">
        <a class="navbar-item">
          Explore Creators
        </a>
      </div>
  
      <div class="navbar-end">
        <div class="navbar-item">
          <div class="buttons">
            <a class="button is-primary" href="/signup">
              <strong>Sign up</strong>
            </a>
            <a class="button is-light" href="/login">
              Log in
            </a>
          </div>
        </div>
      </div>
    </div>
  </nav>

</template>


<script>
export default {
    name: "NavBar"
}
</script>