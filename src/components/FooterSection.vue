<template>
  <footer>
    <span>Geovana Sophia Horodeski</span>
    <nav>
      <ul>
        <li><a href="">About</a></li>
        <li><a href="">Portfolio</a></li>
        <li><a href="">Github</a></li>
        <li><a href="">Contact</a></li>
      </ul>
    </nav>
    <div class="line"></div>
    <div class="rightsReserved">
      <a>© 2024 Geovana Horodeski. All rights reserved.</a>
      <div class="links">
        <a href="">Privacy Policy</a>
        <a href="">Terms of Service</a>
        <a href="">Cookie Settings</a>
      </div>
    </div>
  </footer>
</template>

<script setup></script>

<style scoped>
footer {
  padding: 2vw;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
ul {
  list-style: none;
  display: flex;
  gap: 2vw;
  margin-top: 3vh;
}

.line {
  width: 100%;
  margin: 7vh 0;
  height: 0.2vh;
  background-color: #f7fffb;
}

.links {
  display: flex;
  gap: 2vw;
}

.rightsReserved {
  display: flex;
  width: 100%;
  align-items: center;
  justify-content: space-between;
}

@media (max-width: 860px) {
  .rightsReserved {
    flex-direction: column;
    gap: 5vh;
  }
}
</style>
