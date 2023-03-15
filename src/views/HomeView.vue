<template>
  <section class="home-section">
    <h1 class="hero-heading">
      hello, i am <br />
      Jon
    </h1>
    <img
      src="https://img.freepik.com/free-photo/male-receptionist-elegant-suit-during-work-hours_23-2149714399.jpg?w=360&t=st=1678797340~exp=1678797940~hmac=06b10752e506bf0359149fdaed059948e6950dfa9f6278ac5516295c3369661a"
      class="home-img"
      alt=""
    />
  </section>
</template>

<script>
export default {
  name: 'HomeView',
  components: {}
}
</script>
<style scoped>
.home-section {
  margin-top: 30px;
  width: 100%;
  height: 100vh;
  padding: 50px;
  display: flex;
  align-items: center;
  opacity: 0;
  transition: 1s;
  position: relative;
  opacity: 1;
  z-index: 8;
}

.hero-heading {
  color: #fff;
  font-size: 120px;
  text-transform: capitalize;
  font-weight: 300;
  width: 50%;
}

.home-img {
  height: 100vh;
  width: 50%;
  object-fit: cover;
  opacity: 0.5;
}
@media screen and (max-width: 600px) {
  .home-section {
    width: 100%;
    padding: 0;
  }

  .hero-heading {
    width: 50%;
    font-size: 50px;
  }
  .home-img {
    display: flex;
    justify-content: center;
    width: 50%;
  }
} ;
</style>
