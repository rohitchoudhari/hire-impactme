<template>
    <br>
    <section class="section">
        <div class="container">
            <h3 class="title is-3 has-text-centered">Sign Up</h3>
            <div class="columns is-centered">
                <div class="column is-5">
                  <form action="/signup" method="POST" class="box">
                    <div class="field">
                      <label for="" class="label">Name*</label>
                      <div class="control">
                        <div class="columns is-1">
                          <div class="column"><input class="input is-small" name="first_name" type="text" placeholder="First Name" required></div>
                          <div class="column"><input class="input is-small" name="last_name" type="text" placeholder="Second Name" required></div>
                        </div>
                      </div>
                    </div>
                    <div class="field">
                      <label for="" class="label">Email ID*</label>
                      <div class="control">
                        <input type="email" name="email_id" placeholder="mail@domain.com" class="input is-small" required>
                      </div>
                    </div>
                    <div class="field">
                      <label for="username" class="label">Username*</label>
                      <div class="control">
                        <input type="text" name="username" placeholder="Username" class="input is-small" required>
                      </div>
                    </div>
                    <div class="field">
                      <label for="" class="label">Password*</label>
                      <div class="control">
                        <input type="password" name="password" placeholder="*******" class="input is-small" required>
                      </div>
                    </div>
                    <div class="field">
                      <label for="" class="label">Confirm Password*</label>
                      <div class="control">
                        <input type="password" name="confirmPassword" placeholder="*******" class="input is-small" required>
                      </div>
                    </div>

                    <div class="field">
                      <label for="" class="label">Upload Profile Picture</label>
                      <div class="control">
                        <input type="file" class="filepond" name="profile_picture" accept="image/png, image/jpeg, image/gif"/>
                      </div>
                    </div>

                    <div class="field">
                      <button class="button is-success">
                        Sign Up
                      </button>
                      <a class="button" href="/login">Log In</a>
                    </div>
                  </form>
                </div>
              </div>
              <p></p>
        </div>
        
    </section>
</template>