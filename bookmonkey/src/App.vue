<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <!-- <router-link to="/books">Books</router-link> hier ist path der matcher -->
    <router-link :to="{ name: 'books' }">Books</router-link>
    <!-- hier ist name der matcher und man kann den path namen ändern -->
  </nav>
  <router-view />
</template>
