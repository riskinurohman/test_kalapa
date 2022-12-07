<template>
  <div class="mt-4 d-flex">
    <h3 class="text-muted border-end border-1 pe-2">Blog List</h3>
    <nav style="--bs-breadcrumb-divider: '>';" aria-label="breadcrumb">
      <ol class="breadcrumb p-1 ms-2">
        <li class="breadcrumb-item"><a href="#" class="breadcrumb-link">Home</a></li>
        <li class="breadcrumb-item"><a href="#" class="breadcrumb-link">Pages</a></li>
        <li class="breadcrumb-item"><a href="#" class="breadcrumb-link">Blog</a></li>
        <li class="breadcrumb-item text-muted">List</li>
      </ol>
    </nav>
    <div class="ms-auto align-self-center">
      <button type="button" class="btn btn-primary">
        <i class="fas fa-th-large"></i>
      </button>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Breadcrumb'
}
</script>