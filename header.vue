<template>
    <nav>
        <div class="nav-inner">
            <!-- logo here -->
            <div class="logo">
                <img src="/assets/lock the deal img.png" alt="">
            </div>
            <!-- searchbar -->
            <input type="text" placeholder="Search For Products" ><font-awesome-icon :icon="['fas', 'magnifying-glass']" />
            <!-- icons -->
            <font-awesome-icon :icon="['fas', 'wallet']" />
            <font-awesome-icon :icon="['fas', 'cart-shopping']" />
            <font-awesome-icon :icon="['fas', 'user']" />
        </div>
    </nav>
    <section>
        <label for="energy">Energy</label>
        <label for="electrical">Electricals</label>
     
  
    </section>
</template>

<script setup>
</script>

<style scoped>

nav{
    height: 100px;
    color: brown;
}

nav img{
    height: 50px;
}


</style>