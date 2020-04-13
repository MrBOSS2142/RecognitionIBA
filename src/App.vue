<template>
  <div class="h-100">
    <b-navbar toggleable="lg" type="dark" variant="dark" class="top-position" >
      <b-navbar-brand>RecognitionIBA</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse">
      </b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>

        <b-navbar-nav class="ml-auto">
          <b-nav-item-dropdown right>
            <template v-slot:button-content>
              <b>USER NAME</b>
            </template>
            <b-dropdown-item href="#">Профиль</b-dropdown-item>
            <b-dropdown-item href="#">Выход</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <Recognition />
  </div>
</template>

<script>
import Recognition from "./components/Recognition";

export default {
  name: 'App',
  components: {
    Recognition
  }
}
</script>

<style>
  html {
    height: 100%;
  }
  body{
    height: 100%;
    width: 100%;
    padding: 0;
    margin: 0;
  }
  .top-position{
    z-index: 10000;
  }
  .padd {
    padding: 30px;
  }
</style>
