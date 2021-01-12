<template>

  <div>
  <b-navbar type="dark" variant="dark" style="background-color: #e3f2fd;" >
    <b-navbar-nav>
      <a class="navbar-brand" href="#">
    <img src="../assets/logo+slogan.jpeg" width="30" height="30" alt="">
  </a>
      

      <!-- Navbar dropdowns -->
      <b-nav-item-dropdown text="Lang" >
        <b-dropdown-item href="#">EN</b-dropdown-item>
        <b-dropdown-item href="#">ES</b-dropdown-item>
        <b-dropdown-item href="#">RU</b-dropdown-item>
        <b-dropdown-item href="#">FA</b-dropdown-item>
      </b-nav-item-dropdown>

      <b-nav-item-dropdown text="User" >
        <b-dropdown-item href="#">Account</b-dropdown-item>
        <b-dropdown-item href="#">Settings</b-dropdown-item>
      </b-nav-item-dropdown>
<b-nav-item href="#">Home</b-nav-item>

    </b-navbar-nav>

  </b-navbar>
</div>
</template>


<style scoped>
 .navbar.navbar-dark.bg-dark{
    background-color: #306a9c!important;
 }
</style>