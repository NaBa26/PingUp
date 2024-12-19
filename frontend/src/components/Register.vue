<template>
  <div class="container d-flex justify-content-center align-items-center vh-100">
    <div class="row w-100">
      
      <!-- Login Form -->
      <div class="col-md-5">
        <div class="card p-4 text-dark">
          <h3 class="text-center">Chat App</h3>
          <form>
            <div class="form-group">
              <label for="username">Username or Email</label>
              <input type="text" class="form-control" id="username" placeholder="Enter username or email">
            </div>
            <div class="form-group">
              <label for="password">Password</label>
              <input type="password" class="form-control" id="password" placeholder="Enter password">
            </div>
            <button type="submit" class="btn btn-primary btn-block">Log In</button>
          </form>
          <div class="text-center mt-3">
            <a href="#" class="text-secondary">Forgotten your password?</a>
            <p>Don't have an account? <a href="register.html" class="text-primary">Sign up</a></p>
          </div>
        </div>
      </div>
    </div>
  </div>
  </template>

<style lang="css" scoped>
body {
  background-color: #0D0D0D;
}

.card {
  max-width: 350px;
  margin: auto;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

.carousel-item img {
  height: 450px;
  object-fit: cover;
  border-radius: 10px;
}

.text-center a {
  color: #0095F6;
}

</style>