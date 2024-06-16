<template>
  <div class="feedback">
    <h1>Client Testimonials</h1>
    <p>Hear from our clients</p>
    <div class="cardContent">
      <div class="card" v-for="testimonial in testimonials" :key="testimonial.name">
        <p>“{{ testimonial.feedback }}”</p>
        <div class="user">
          <img :src="testimonial.image" alt="" />
          <div>
            <span>{{ testimonial.name }}</span>
            <div class="stars">
              <i v-for="n in testimonial.stars" :key="n" class="ph-fill ph-star"></i>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
const testimonials = [
  {
    feedback: 'A remarkable experience with breathtaking photos.',
    name: 'Carlos Marques',
    image: 'https://www.designi.com.br/images/preview/12161378.jpg',
    stars: 5
  },
  {
    feedback: 'The photos captured the essence of the moment perfectly.',
    name: 'Ana Silva',
    image:
      'https://img.freepik.com/fotos-gratis/pessoa-de-origem-indiana-se-divertindo_23-2150285283.jpg',
    stars: 4
  },
  {
    feedback: 'Exceptional service and stunning photography.',
    name: 'João Pereira',
    image: 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQx7eB46iYuBJXT24DFxvaAbAsbSH9lRUAwXEdXr7hzjTJxb8jRV5LttC-UeiMFSuD953o&usqp=CAU',
    stars: 5
  },
  {
    feedback: 'Professional and creative, highly recommend.',
    name: 'Maria Souza',
    image:
      'https://storage.googleapis.com/production-hostgator-brasil-v1-0-8/958/301958/ejqVH04K/ed9331fe80e14c86a1701f63d0238e27',
    stars: 5
  },
  {
    feedback: 'Captured our wedding beautifully, memories for a lifetime.',
    name: 'Paulo Lima',
    image: 'https://s3-sa-east-1.amazonaws.com/doctoralia.com.br/doctor/912957/91295778c2a22a7fd7d91496b859f1e0_large.jpg',
    stars: 5
  },
  {
    feedback: 'Amazing photos and great experience overall.',
    name: 'Lucia Fernandes',
    image:
      'https://storage.alboom.ninja/sites/12999/media/bw-90491_7e7a83c9f481_555e7fdfd539127c89967fa48ef01de0_64ee202522c3.jpg?t=1601045305',
    stars: 4
  }
]
</script>
<style scoped>
.feedback {
  background-color: #2b2629;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 10vw;
  margin-top: 15vh;
}

.feedback h1 {
  margin-bottom: 3vh;
}

.cardContent {
  display: flex;
  flex-wrap: wrap;
  gap: 2vw;
  margin-top: 10vh;
}

.card {
  background-color: #181618;
  padding: 2vw;
  width: 21vw;
  border-radius: 2vw;
}

.card img {
  width: 3vw;
  object-fit: cover;
  height: 3vw;
  border-radius: 50%;
}

.card .user {
  display: flex;
  align-content: center;
  gap: 1vw;
  margin-top: 3vh;
}

.user div {
  display: flex;
  flex-direction: column;
}
.user div .stars {
  display: flex;
  flex-direction: row;
}

.user i {
  color: #00b6d2 !important;
}
</style>
