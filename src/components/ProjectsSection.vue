<template>
  <section class="projects">
    <div class="bentogrid">
      <div class="item item1"><img src="../../public/paisagem.png" alt="Landscape" /></div>
      <div class="item item2"><img src="../../public/children.png" alt="Children" /></div>
      <div class="item item3"><img src="../../public/casal1.png" alt="Couple" /></div>
      <div class="item item4"><img src="../../public/casal2.png" alt="Beach" /></div>
    </div>
    <div class="description">
      <h2>Our Gallery</h2>
      <a href="">
        <p>Explore Our Work</p>
      </a>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
.projects {
  display: flex;
  gap: 4vw;
  align-items: center;
}

.bentogrid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(4, 1fr);
  grid-column-gap: 12px;
  grid-row-gap: 12px;
  width: 45vw;
  height: 100vh;
}

.item1 {
  grid-area: 1 / 1 / 3 / 2;
}
.item2 {
  grid-area: 1 / 2 / 2 / 3;
}
.item3 {
  grid-area: 2 / 2 / 3 / 3;
}
.item4 {
  grid-area: 3 / 1 / 5 / 3;
}

.item {
  background-color: #fff;
  border-radius: 8px;
}

.item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  border-radius: 8px;
}
.projects .description {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

@media (max-width: 860px) {
  .projects {
    align-items: flex-start;
    flex-direction: column-reverse;
    gap: 7vh;
  }
  .bentogrid {
    width: 100%;
  }
}
</style>
