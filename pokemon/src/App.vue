<template>
  <div class="p-14">
    <router-link class="title" to="/">Home</router-link>
  </div>
  <router-view/>
</template>

<style>
.title {
  display: flex;
  align-content: center;
  justify-content: center;
  font-size: 20px;
  font-weight: 600;
}

</style>
