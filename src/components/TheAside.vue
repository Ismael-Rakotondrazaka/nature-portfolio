<template>
  <aside id="aside" class="fixed-top bg-white h-100 p-3" style="width: 300px">
    <img src="@/assets/images/avatar_g2.jpg" alt="" class="w-100" />
    <h1 class="text-uppercase">Portfolio</h1>
    <h2 class="text-muted">Template by W3.CSS</h2>
    <div class="nav flex-column">
      <li class="nav-item">
        <a href="" class="nav-link text-uppercase text-black active">
          Portfolio
        </a>
      </li>
      <li class="nav-item">
        <a href="" class="nav-link text-uppercase text-black">About</a>
      </li>
      <li class="nav-item">
        <a href="" class="nav-link text-uppercase text-black">Contact</a>
      </li>
    </div>
  </aside>
</template>

<script>
export default {
  name: "TheAside",
};
</script>

<style>
@media screen and (max-width: 992px) {
  #aside {
    display: none;
  }
}
</style>
