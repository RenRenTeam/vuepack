<style src="./css/shared.css"></style>

<template>
  <div id="app">
      <a v-link="{path: '/'}">Home</a>
      <a v-link="{path: '/about'}">About</a>
    <router-view></router-view>
  </div>
</template>
