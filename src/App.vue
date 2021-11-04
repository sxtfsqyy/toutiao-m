<template>
  <div id="app">
  <!--路由出口-->
  <div id="nav">
    <router-link to="/"> home</router-link>
    <router-link to="/about">about</router-link>
    </div>
    <router-view/>
    <h1>黑马头条</h1>
  </div>
</template>
<style lang="less"></style>
