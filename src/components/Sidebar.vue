<template>
  <aside class="sidebar bg-white p-3 text-center">
    <ul>
      <li><a href="javascript:void(0)"><i class="fa fa-eye"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-window-maximize"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-briefcase"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-cube"></i></a></li>
      <li><a href="javascript:void(0)"><i class="fas fa-columns"></i></a></li>
    </ul>

    <!-- Divider -->
    <div class="pt-3 pb-3" style="color: #6C6A77">
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
export default {
  name: 'Sidebar'
}
</script>
<style scoped>
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
