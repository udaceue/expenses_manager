<template>

</template>

<script>
import TabMenu from 'primevue/tabmenu';
export default {
  name: "MenuBar",
  data() {
    return {
      items: [
        {label: 'Home', icon: 'pi pi-fw pi-home'},
        {label: 'Calendar', icon: 'pi pi-fw pi-calendar'},
        {label: 'Edit', icon: 'pi pi-fw pi-pencil'},
        {label: 'Documentation', icon: 'pi pi-fw pi-file'},
        {label: 'Settings', icon: 'pi pi-fw pi-cog'}
      ]
    }
  },
}
</script>

<style scoped>

</style>