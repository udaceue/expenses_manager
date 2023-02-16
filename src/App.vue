<script>
import MenuBar from "./components/MenuBar.vue";
import AccountsList from "./components/AccountsList.vue";

export default {
  name: "App",
  data() {
    return{

    }
  },
  components:{
    AccountsList,
    MenuBar,
  }
}

</script>

<template>
    <MenuBar :collapsed="collapsed"></MenuBar>
  <div class="main-container">
    <AccountsList></AccountsList>
  </div>
</template>

<style>
.main-container{
  padding: 0.2rem;
}
</style>
