<template>
  <nav class="col-md-2 d-none d-md-block bg-light sidebar">
    <div class="sidebar-sticky">
      <h6
        class="sidebar-heading d-flex justify-content-between align-items-center px-3 mt-4 mb-1 text-muted"
      >
        <span>後臺管理</span>
        <a class="d-flex align-items-center text-muted" href="#">
          <span data-feather="plus-circle"></span>
        </a>
      </h6>
      <ul class="nav flex-column">
        <li class="nav-item">
          <router-link class="nav-link" to="/admin/products">
            <i class="fas fa-box-open"></i> 產品列表
          </router-link>
          <router-link class="nav-link" to="/admin/orders">
            <i class="fas fa-box-open"></i> 訂單列表
          </router-link>
          <router-link class="nav-link" to="/admin/coupons">
            <i class="fas fa-box-open"></i> 優惠券
          </router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Sidebar',
  data() {
    return {};
  },
};
</script>