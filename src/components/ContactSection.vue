<template>
  <section class="contact">
    <h1>Contact Us</h1>
    <p>We'd love to hear from you</p>
    <div class="box-email">
      <input placeholder="Your message" type="text" />
      <button>Send</button>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
.contact {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 5vh;
  padding: 10vw;
}

.contact input {
  padding: 16px;
  border: 1px solid #41393e;
  background-color: transparent;
  color: #f7fffb;
  outline: none;
  flex: 1;
  width: 20vw;
  border-radius: 7px;
  min-width: 245px;
}

button {
  min-width: 75px;
}

.box-email {
  display: flex;
  flex-wrap: wrap;
  gap: 1vw;
}

@media (max-width: 860px) {
  button {
    flex: 1;
  }
  .contact {
    gap: 3vh;
  }
}
</style>
