<template>
<div id="header">
    <!-- <v-app-bar
      absolute
      color="white"
      elevate-on-scroll
      scroll-target="#scrolling-techniques-7" 
    > -->
    <v-app-bar
      color="transparent"
    >

      <v-toolbar-title><NuxtLink to="/">kazumawada</NuxtLink></v-toolbar-title>

      <v-spacer></v-spacer>
    <NuxtLink to="/profile">プロフィール</NuxtLink>|
    <NuxtLink to="/apps">作ったもの</NuxtLink>
    <!-- <NuxtLink to="/articles">ブログ記事</NuxtLink> -->
    </v-app-bar>

</div>
</template>