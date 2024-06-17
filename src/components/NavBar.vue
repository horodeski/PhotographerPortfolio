<template>
  <nav>
    <div class="logo"></div>
    <ul>
      <li><a href="">Home</a></li>
      <li><a href="">About</a></li>
      <li><a href="">Gallery</a></li>
    </ul>
    <button>
      <i class="ph ph-file"></i>
      <a> View Portfolio </a>
    </button>
  </nav>
</template>

<script setup></script>

<style scoped>
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
}

nav ul {
  display: flex;
  gap: 1vw;
  list-style: none;
}

nav .logo {
  background-color: rgb(252, 252, 252);
  width: 7vw;
  height: 5vh;
}

nav button {
  border: 2px solid white;
  padding: 1vh 1.8vw;
  border-radius: 10px;
  color: white;
  background-color: transparent;
  cursor: pointer;
}
/* nav button span {
  font-size: 18px;
} */

nav button i {
  display: none;
}

@media (max-width: 860px) {
  nav ul {
    gap: 2vw;
  }
  nav button i {
    display: block;
  }

  nav button a {
    display: none;
  }
}
</style>
