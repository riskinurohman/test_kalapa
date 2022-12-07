<template>
  <nav class="navbar rounded navbar-expand-lg navbar-light bg-white custom-navbar">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item align-self-center">
            <a class="nav-link" aria-current="page" href="#"><i class="fas fa-envelope"></i></a>
          </li>
          <li class="nav-item align-self-center">
            <a class="nav-link" href="#"><i class="fas fa-comment-alt"></i></a>
          </li>
          <li class="nav-item align-self-center">
            <a class="nav-link" href="#" tabindex="-1"><i class="fas fa-calendar"></i></a>
          </li>
          <li class="nav-item align-self-center">
            <a class="nav-link" href="#" tabindex="-1"><i class="fas fa-check-square"></i></a>
          </li>
          <li class="nav-item align-self-center">
            <a class="nav-link" href="#" tabindex="-1"><i class="fas fa-star text-warning"></i></a>
          </li>
        </ul>
        <ul class="navbar-nav ms-auto">
          <li class="nav-item align-self-center">
            <a class="nav-link" aria-current="page" href="#">
              <img :src="usa" class="img-fluid" style="width: 30px">English
            </a>
          </li>
          <li class="nav-item align-self-center">
            <a class="nav-link" href="#" tabindex="-1"><i class="fas fa-moon"></i></a>
          </li>
          <li class="nav-item align-self-center">
            <a class="nav-link" href="#" tabindex="-1"><i class="fas fa-search"></i></a>
          </li>
          <li class="nav-item align-self-center">
            <a class="nav-link" href="#" tabindex="-1">
              <i class="fas fa-shopping-cart"></i>
              <span class="position-absolute top-16 start-90 translate-middle badge rounded-pill bg-purple">
                6
              </span>
            </a>
          </li>
          <li class="nav-item align-self-center">
            <a class="nav-link" href="#" tabindex="-1">
              <i class="fas fa-bell"></i>
              <span class="position-absolute top-16 start-90 translate-middle badge rounded-pill bg-danger">
                5
              </span>
            </a>
          </li>
          <li class="nav-item align-self-center" style="line-height: 18px">
            <a class="nav-link" href="#" tabindex="-1">
              <span class="f-w-700 d-block">John Doe</span>
              <span>Admin</span>
            </a>
          </li>
          <li class="nav-item align-self-center">
            <a class="nav-link position-relative" href="#" tabindex="-1">
              <img :src="avatar" class="img-avatar rounded-circle">
              <span class="position-absolute bottom-0 translate-middle end-0 p-2 bg-success rounded-circle">
                <span class="visually-hidden">Online</span>
              </span>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>  
</template>
<script>
import USA from "../assets/images/usa.png"
import Avatar from "../assets/images/person1.jpg"

export default {
  name: 'Navbar',
  data: function() {
    return {
      usa: USA,
      avatar: Avatar
    }
  }
}
</script>
<style scoped>
  .custom-navbar {
    height: fit-content;
    width: 100%;
  }
  .img-avatar {
    width: 40px;
    height: 40px;
  }
  .online-badge {
    top: 40px;
    right: 15px;
  }
</style>
