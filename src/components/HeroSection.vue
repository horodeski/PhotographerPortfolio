<template>
  <section class="hero">
    <h1>Capture moments, create memories.</h1>
    <p>Discover the art of minimalist photography with our curated portfolio.</p>
    <button>View portfolio</button>
    <img
      src="https://images.pexels.com/photos/11894290/pexels-photo-11894290.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
      alt=""
    />
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
</style>
