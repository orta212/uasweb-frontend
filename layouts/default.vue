<template>
  <div>
      <AdminNavbar/>
    <aside class="main-sidebar sidebar-dark-primary elevation-4">
      <AdminSidebar/>
    </aside>
    
    <div class="content-wrapper">
      <nuxt />
    </div>
    
    <footer class="main-footer">
      <!-- Footer content here -->
    </footer>
  </div>
</template>

<script>
import { jquery } from "jquery";
export default {
  name: 'default',
}
</script>