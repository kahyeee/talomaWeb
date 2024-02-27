<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="#">
        <img src="@/assets/logo.png" width="70" height="auto" class="align-text-top alt=">
      </a>
      <div class="btn-group">
        <button type="button" class="btn dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
          Action
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Action</a></li>
          <li><a class="dropdown-item" href="#">Another action</a></li>
          <li><a class="dropdown-item" href="#">Something else here</a></li>
          <li><hr class="dropdown-divider"></li>
          <li><a class="dropdown-item" href="#">Separated link</a></li>
        </ul>
      </div>
      <ul class="nav justify-content-center align-text-end dropsown-menu">
        <li class="nav-item">
          <a class="nav-link active link-dark " aria-current="page" href="#">族群介紹</a>
        </li>
        <li class="nav-item">
          <a class="nav-link link-dark" href="#">活動資訊</a>
        </li>
        <li class="nav-item">
          <a class="nav-link link-dark" href="#">影音專區</a>
        </li>
        <li class="nav-item">
          <a class="nav-link link-dark" href="#">關於我們</a>
        </li>
      </ul>
      <div class="d-flex align-items-center">
        <div class="hstack gap-3">
          <div class="hstack-item ms-auto">
            <a class="log-in link-dark text-decoration-none" href="">登入</a>
          </div>
          <div class="vr"></div>
          <div class="hstack-item">
            <a class="sign-in link-dark text-decoration-none" href="">註冊</a>
          </div>
        </div>
      </div>
    </div>
    
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
}
</style>
