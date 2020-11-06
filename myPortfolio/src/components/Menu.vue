<template>
    <nav>
        <div class="sideNav"> 
            <router-link to="/">Home</router-link>
            <router-link to="/project">Projects</router-link>
            <router-link to="/contact">Contact</router-link>
        </div>
    </nav>

</template>


<script>
export default {

}
</script>

<style>
.sideNav{
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  align-items: center;
}
</style>