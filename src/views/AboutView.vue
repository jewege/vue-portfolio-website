<template>
  <section class="about-section">
    <h1 class="about-heading">About Me</h1>
    <div class="about">
      <div class="about-img-container">
        <img
          src="https://img.freepik.com/free-photo/handsome-young-businessman-suit_273609-6513.jpg?w=740&t=st=1678802308~exp=1678802908~hmac=11c2767124b84e8db94affd452b2eac1f64d5b0716f11e592cd9d572fdec6aa2"
          class="about-img"
          alt=""
        />
      </div>
      <div class="about-info">
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Error
          mollitia vel porro accusamus laborum, iure deserunt minus, praesentium
          iste veritatis voluptas laboriosam sed cum adipisci commodi quod? Quis
          expedita animi officiis voluptatibus dicta aspernatur hic impedit
          optio repudiandae et quidem quas iure quia quaerat provident porro,
          reiciendis minima natus? Autem sapiente obcaecati deleniti fugiat et!
          Ex minus at perspiciatis. Fuga aperiam eos aliquid nesciunt quae
          pariatur perspiciatis ratione. Inventore aspernatur, perferendis sequi
          fuga quasi labore rem numquam laborum illum magnam iste corrupti,
          cupiditate vitae ipsa reprehenderit, nobis veniam fugit delectus! Sed
          necessitatibus nostrum dolor est deserunt numquam, esse minima fuga!
        </p>
        <div class="download-cv-btn">
          <button>downlaod cv</button>
        </div>
      </div>
    </div>

    <div class="skill-section">
      <h1 class="skill-heading">Skills</h1>
      <div class="skill-container">
        <div class="skill-card">
          <img src="../assets/js.png" class="skill-img" alt="" />
          <div class="skill-level">50%</div>
          <h1 class="skill-name">JavaScript</h1>
        </div>
        <div class="skill-card">
          <img src="../assets/html.png" class="skill-img" alt="" />
          <div class="skill-level">80%</div>
          <h1 class="skill-name">HTML</h1>
        </div>
        <div class="skill-card">
          <img src="../assets/css.png" class="skill-img" alt="" />
          <div class="skill-level">60%</div>
          <h1 class="skill-name">CSS</h1>
        </div>
        <div class="skill-card">
          <img src="../assets/vue.png" class="skill-img" alt="" />
          <div class="skill-level">50%</div>
          <h1 class="skill-name">Vue</h1>
        </div>
      </div>
    </div>
  </section>
</template>
<script></script>
<style scoped>
.about-section {
  width: 100%;
  min-height: 100vh;
  padding: 50px 100px;
  transition: 1s;
  margin-top: 100px;
}

.about-heading {
  font-size: 100px;
  background: #5f5f5f;
  text-transform: capitalize;
  text-align: center;
  margin-bottom: 50px;
  color: #353535;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-stroke: 8px transparent;
}

.about {
  width: 100%;
  display: flex;
  gap: 30px;
}

.about-img-container {
  width: 35%;
}

.about-img-container img {
  width: 100%;
}

.about-info {
  width: 60%;
  color: #fff;
}

.about-info p {
  text-align: left;
  opacity: 0.6;
  line-height: 40px;
  font-size: 20px;
}

.about-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 20px;
}

.download-cv-btn {
  display: flex;
  justify-content: center;
  align-items: center;
}

.download-cv-btn button {
  padding: 10px 20px;
  color: #fff;
  border: none;
  font-size: 16px;
  text-transform: capitalize;
  cursor: pointer;
  transition: 0.5s;
  background: rgba(92, 31, 31, 0.5);
  display: flex;
  justify-content: center;
  align-items: center;
}

.download-cv-btn button:hover {
  background: #000;
}

.skill-section {
  position: relative;
  margin: 100px 0;
}

.skill-heading {
  font-size: 100px;
  background: #5f5f5f;
  text-transform: capitalize;
  text-align: center;
  margin-bottom: 50px;
  color: #353535;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-stroke: 8px transparent;
}

.skill-container {
  width: 95%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  gap: 100px;
  color: #fff;
}

.skill-card {
  position: relative;
  width: 200px;
  /* border: 1px solid #fff; */
  padding: 10px;
}

.skill-img {
  height: 200px;
  display: block;
  margin: auto;
}

.skill-name {
  font-size: 30px;
  font-weight: 300;
  text-align: center;
  text-transform: capitalize;
  margin: 30px 0 20px;
}

.skill-level {
  position: absolute;
  top: 20px;
  right: 0;
  width: 150px;
  height: 150px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 22px;
  border-radius: 50%;
  border: 10px solid;
}

.skill-card:nth-child(1) .skill-level {
  background: #ff4f4f28;
  border-color: #ff4f4f;
  color: #ff4f4f;
}

.skill-card:nth-child(2) .skill-level {
  background: #4fa0ff28;
  border-color: #4fa0ff;
  color: #4fa0ff;
}

.skill-card:nth-child(3) .skill-level {
  background: #ffed4f28;
  border-color: #ffed4f;
  color: #ffed4f;
}

.skill-card:nth-child(4) .skill-level {
  background: #52ff4f28;
  border-color: #52ff4f;
  color: #52ff4f;
}

.skill-card:nth-child(5) .skill-level {
  background: #4fdfff28;
  border-color: #4fdfff;
  color: #4fdfff;
}

@media screen and (max-width: 600px) {
  .about-section {
    width: 100%;
    padding: 10px;
  }

  .about {
    width: 100%;
    flex-direction: column;
    justify-content: center;
  }

  .about-img-container {
    width: 100%;
  }

  .about-heading {
    font-size: 80px;
  }
  .about-info {
    width: 100%;
  }

  .skill-heading {
    font-size: 80px;
  }

  .skill-container {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 30px;
    color: #fff;
  }

  .skill-card {
    position: relative;
    width: 150px;
    padding: 10px;
  }

  .skill-img {
    height: 50px;
    display: block;
    margin: auto;
  }

  .skill-name {
    font-size: 18px;
    font-weight: 300;
    text-align: center;
    text-transform: capitalize;
    margin: 30px 0 20px;
  }
  .skill-level {
    position: absolute;
    top: 20px;
    right: 0;
    width: 50px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 12px;
    border-radius: 50%;
    border: 3px solid;
  }
}
</style>
