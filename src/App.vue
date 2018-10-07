<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <main>
      <router-view/>
    </main>
  </div>
</template>

<style>
body {
  background: #f1f1f1;
  font-size: 14px;
}
</style>
