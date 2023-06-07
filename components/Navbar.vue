<template>
  <div>
    <div>
      <b-navbar toggleable="lg" type="light" variant="">
        <b-navbar-brand href="#">
          <img src="~/assets/images/Frame.png" class="logo-nav" alt="">
        </b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>

<style lang="scss">
.logo-nav {
  width: 200px;
  margin-left: 20px;
}
</style>