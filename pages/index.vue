<template>
  <div id="main">
    <NuxtLink to="/cold">منوی سرد</NuxtLink>
    <NuxtLink to="/hot">منوی گرم</NuxtLink>
  </div>
</template>

<style>
#main {
  display: flex;
  flex-direction: column;
  background-image: url("/assets/image/main.jpg");
  background-size: 100vw 100vh;
  background-repeat: no-repeat, repeat;
  width: 100lvw;
  height: 100vh;
  text-align: center;
  align-items: center;
  justify-content: center;
  align-self: center;
}
a {
  font-size: 3rem;
  padding-bottom: 2rem;
  color: #fff;
}
</style>
