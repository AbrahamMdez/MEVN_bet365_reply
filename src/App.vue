<template>
  <router-link to="/"></router-link>
  <router-link to="/main"></router-link>
  <router-view/>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto+Slab&display=swap");

:root {
  --main-font-family: 'Roboto Slab', serif;
  --main-color: #14805e;
  --secondary-color: #ffdf1b;
  --text-color: #fff;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    outline: none;
    border: none;
    text-decoration: none;
    list-style: none;
    font-family: var(--main-font-family);
}

</style>
