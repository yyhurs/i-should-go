<template>
  <div>
    <Navbar />
    <AlertMsg />
    <div class="container-fluid mt-5">
      <div class="row">
        <Sidebar />
        <main role="main" class="col-md-9 ml-sm-auto col-lg-10 px-4">
          <router-view></router-view>
        </main>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from '@/components/backend/Navbar';
import Sidebar from '@/components/backend/Sidebar';
import AlertMsg from '@/components/AlertMsg';

export default {
  components: {
    Navbar,
    Sidebar,
    AlertMsg,
  },
};
</script>
