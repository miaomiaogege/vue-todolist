<template>
  <header class="nav-header">
    <img src="../../assets/img/arrow-left.png" class="icon-left" v-touch:tap="back">
    <span class="header-txt">{{title}}</span>
  </header>
</template>

<style lang="scss" src="./nvHeader.scss" scoped></style>

<script src="./nvHeader.js"></script>
