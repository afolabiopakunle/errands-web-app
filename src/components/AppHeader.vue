<template>
  <div>
    <header>
      <nav class="navbar navbar-expand-lg navbar-light">
        <a class="navbar-brand ml-5" href="#">
          <img src="../assets/logo-blue.png" style="width:110px; margin-top: -14px;" alt="logo" />
        </a>
        <button
          class="navbar-toggler navbar-toggler-right"
          type="button"
          data-toggle="collapse"
          data-target="#navb"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navb">
          <ul class="navbar-nav mr-auto"></ul>
          <form class="form-inline my-2 my-lg-0">
            <ul class="navbar-nav position-relative">
              <li class="nav-item">
                <a class="nav-link active" id="all-errands" href="#">All Errands</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" id="post-errand" href="#">Post Errand</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Wallet</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Profile</a>
              </li>
            </ul>
            <div class="notification-box">
              <i class="material-icons md-24">notification_important</i>
              <span class="notification">4</span>
            </div>
            <div class="user-box">
              <img src="../assets/idris.jpg" class="profile-picture" alt="profile-pix" />
              <span>
                <i class="material-icons md-24 text-dark">keyboard_arrow_down</i>
              </span>
            </div>
          </form>
        </div>
      </nav>
    </header>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style scoped>
</style>