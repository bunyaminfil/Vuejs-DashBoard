<template>
  <footer class="footer">
    <div class="container-fluid">
      <div class="copyright">
        © {{ year }} made with <i class="tim-icons icon-heart-2"></i> by
        <a href="http://www.projectxr.com.tr" target="_blank" rel="noopener"
          >Project XR</a
        >
        for a better web.
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: 2021 //new Date().getFullYear() //güncel tarih
    };
  }
};
</script>
<style></style>
