<template>
  <nav class="navbar navbar-expand-md navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="/">Home</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="navbar-nav">
        <ul class="menu">
          <li><router-link to="/about">About</router-link></li>
          <li><router-link to="/contact">Contact</router-link></li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<style scoped>
a {
  font-size: 2rem;
  color: #010101;
}
.navbar-nav {
  margin: 10px auto;
  text-align: center;
}
.menu {
  list-style: none;
  margin-bottom: 20px;
}
.menu li {
  display: inline;
}
.menu li a {
  padding: 20px;
  text-decoration: none;
}
</style>
