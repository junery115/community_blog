<template>
  <div class="container">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">
        <img src="../assets/logo.png" width="30px" height="30px" />
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <router-link to="/login" class="nav-link"> Login</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/signup" class="nav-link">Signup</router-link>
          </li>
          <!-- <li class="nav-item dropdown"> -->
          <!--   <a -->
          <!--     class="nav-link dropdown-toggle" -->
          <!--     href="#" -->
          <!--     id="navbarDropdown" -->
          <!--     role="button" -->
          <!--     data-toggle="dropdown" -->
          <!--     aria-haspopup="true" -->
          <!--     aria-expanded="false" -->
          <!--   > -->
          <!--     Hey Jay -->
          <!--   </a> -->
          <!--   <div class="dropdown-menu" aria-labelledby="navbarDropdown"> -->
          <!--     <a class="dropdown-item" href="#">Logout</a> -->
          <!--   </div> -->
          <!-- </li> -->
        </ul>
      </div>
    </nav>
  </div>
</template>
