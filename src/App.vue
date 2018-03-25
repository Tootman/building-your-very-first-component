
<!--App.vue (Parent component)-->
<template>
    <div id="app">
        <navbar-component></navbar-component>
        <div class="container">
            <page-heading-component></page-heading-component>
            <staff-list-component></staff-list-component>
        </div>
        Finally: <djsComponent/>
    </div>
</template>

<script>
    import PageHeadingComponent from './PageHeadingComponent.vue'
    import StaffListComponent from './StaffListComponent.vue'
    import NavbarComponent from './NavbarComponent.vue'
    import djsComponent from './djsComponent.vue'
    export default {
        name: 'app',
        components: {NavbarComponent, 
        PageHeadingComponent,
         StaffListComponent,
         djsComponent
         }, //Register other components
    }
</script>

<style scoped>
</style>