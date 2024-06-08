<template>
  <section class="about">
    <div class="col">
      <h2>Services</h2>
      <div class="card">
        <span>Portrait Photography</span>
        <div>
          <p>Capturing the essence of individuals or groups.</p>
          <i class="ph ph-arrow-right"></i>
        </div>
      </div>
      <div class="card">
        <span>Portrait Photography</span>
        <div>
          <p>Capturing the essence of individuals or groups.</p>
          <i class="ph ph-arrow-right"></i>
        </div>
      </div>
      <div class="card">
        <span>Portrait Photography</span>
        <div>
          <p>Capturing the essence of individuals or groups.</p>
          <i class="ph ph-arrow-right"></i>
        </div>
      </div>
      <div class="card">
        <span>Portrait Photography</span>
        <div>
          <p>Capturing the essence of individuals or groups.</p>
          <i class="ph ph-arrow-right"></i>
        </div>
      </div>
      <div class="card">
        <span>Portrait Photography</span>
        <div>
          <p>Capturing the essence of individuals or groups.</p>
          <i class="ph ph-arrow-right"></i>
        </div>
      </div>
    </div>
    <div class="col">
      <h2>Services</h2>
      <div class="card">
        <span>Portrait Photography</span>
        <div>
          <p>Capturing the essence of individuals or groups.</p>
          <i class="ph ph-arrow-right"></i>
        </div>
      </div>
      <div class="card">
        <span>Portrait Photography</span>
        <div>
          <p>Capturing the essence of individuals or groups.</p>
          <i class="ph ph-arrow-right"></i>
        </div>
      </div>
      <div class="card">
        <span>Portrait Photography</span>
        <div>
          <p>Capturing the essence of individuals or groups.</p>
          <i class="ph ph-arrow-right"></i>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>

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
