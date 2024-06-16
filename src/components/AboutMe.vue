<template>
  <section class="about">
    <div class="col">
      <h2>Services</h2>
      <div class="card" v-for="service in services" :key="service.title">
        <span>{{ service.title }}</span>
        <div>
          <p>{{ service.description }}</p>
          <i class="ph ph-arrow-right"></i>
        </div>
      </div>
    </div>
    <div class="col">
      <h2>Experience</h2>
      <div class="card" v-for="experience in experiences" :key="experience.title">
        <span>{{ experience.title }}</span>
        <div>
          <p>{{ experience.description }}</p>
          <i class="ph ph-arrow-right"></i>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const services = [
  { title: 'Portrait Photography', description: 'Capturing the essence of individuals or groups.' },
  { title: 'Wedding Photography', description: 'Documenting your special day with elegance.' },
  {
    title: 'Event Photography',
    description: 'Covering corporate and social events professionally.'
  },
  {
    title: 'Landscape Photography',
    description: 'Showcasing the beauty of nature and surroundings.'
  },
  {
    title: 'Product Photography',
    description: 'Highlighting your products with precision and creativity.'
  }
]

const experiences = [
  { title: 'Photography Degree', description: 'Graduated with a specialization in visual arts.' },
  { title: 'Workshops', description: 'Participated in various photography workshops.' },
  { title: 'Exhibitions', description: 'Showcased work in multiple art galleries.' },
  { title: 'Awards', description: 'Recipient of prestigious photography awards.' },
  { title: 'Publications', description: 'Featured in well-known photography magazines.' }
]
</script>

<style scoped>
.about {
  gap: 4vw;
  display: flex;
}

.about .col {
  width: 100%;
}

.about .col h2 {
  margin-bottom: 4vh;
}

.about .col .card {
  border-top: 1px solid #f7fffb;
  padding: 2vh 2vw;
  display: flex;
  flex-direction: column;
  gap: 1vh;
  transition: 0.3s all ease-in-out;
}

.about .col .card div {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.about .col .card div i {
  font-size: 2em;
  color: #72656d;
}
.about .col .card:hover div i {
  color: #f7fffb;
}

.col .card:last-child {
  border-bottom: 1px solid #f7fffb;
}
</style>
