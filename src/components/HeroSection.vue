<template>
  <section class="hero">
    <h1>Capture moments, create memories.</h1>
    <p>Discover the art of minimalist photography with our curated portfolio.</p>
    <button>View portfolio</button>
    <img src="../../public/photograph.png" alt="" />
  </section>
</template>

<script setup></script>

<style scoped>
.hero {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 7vh;
  margin-top: 5vh;
}

.hero img {
  width: 100%;
  height: 70vh;
  object-fit: cover;
  margin-top: 5vh;
  border-radius: 10px;
}
.hero * {
  text-align: center;
}

@media (max-width: 860px) {
  .hero {
    gap: 4vh;
  }
}
</style>
