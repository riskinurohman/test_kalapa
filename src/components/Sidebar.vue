<template>
  <aside class="sidebar bg-white p-3 text-center rounded-bottom">
    <ul>
      <li><a href="javascript:void(0)"><img :src="logo" class="img-fluid" style="width: 30px"/></a></li>
      <li><a href="javascript:void(0)"><i class="fa fa-eye"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-window-maximize"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-briefcase"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-cube"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-columns"></i></a></li>
    </ul>

    <!-- Divider -->
    <div class="pt-2 pb-2" style="color: #A6A4B1">
      <i class="fas fa-ellipsis-h"></i>
    </div>
    <!-- End Divider -->

    <ul>
      <li><a href="javascript:void(0)"><i class="fas fa-clone"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-cube"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-box"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-check-circle"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-redo"></i></a></li>
    </ul>
  </aside>
</template>
<script>
import Logo from "../assets/images/logo.png"

export default {
  name: 'Sidebar',
  data: function() {
    return {
      logo: Logo
    }
  }
} 
</script>
<style scoped>
  @media (min-width: 375px) and (max-width: 915px) {
    .sidebar {
      display: none;
    }
  }
  .sidebar {
    width: 100px;
    font-size: 1.5em;
    display: grid;
    height: 600px;
  }
  .sidebar ul {
    list-style-type: none;
    padding: 0;
  }
  .sidebar ul li {
    padding-top: 10px;
  }
  .sidebar ul li a {
    color: #6C6A77;
  }
</style>
