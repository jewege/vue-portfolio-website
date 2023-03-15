<template lang="">
  <section class="contact-section">
    <form class="contact-form">
      <input
        type="text"
        name="name"
        id="name"
        autocomplete="off"
        placeholder="name"
      />
      <input
        type="email"
        name="email"
        id="email"
        autocomplete="off"
        placeholder="emai
        "
      />
      <textarea
        name="msg"
        id="msg"
        placeholder="message"
        autocapitalize="off"
      ></textarea>
      <button type="submit" class="form-submit-btn">Contact</button>
    </form>

    <!-- Map -->
    <div class="map">
      <iframe
        id="gmap_canvas"
        src="https://maps.google.com/maps?q=medan&t=&z=10&ie=UTF8&iwloc=&output=embed"
      ></iframe
      ><a href="https://2yu.co"></a><br />><a
        href="https://embedgooglemap.2yu.co"
      ></a>
    </div>
  </section>
</template>
<script>
export default {}
</script>
<style scoped>
.contact-section {
  padding: 50px 150px;
  height: 100vh;
  display: flex;
  gap: 50px;
  margin-top: 100px;
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  height: 40px;
  background: rgba(255, 255, 255, 0.2);
  border: 1px solid #fff;
  margin-bottom: 30px;
  border-radius: 5px;
  text-transform: capitalize;
  color: #fff;
  padding: 5px 10px;
}

::placeholder {
  color: #fff;
}

#msg {
  height: 250px;
  resize: none;
  font-family: sans-serif;
}

.form-submit-btn {
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

.form-submit-btn:hover {
  background: #000;
}

.map {
  width: 100%;
  height: 100%;
  padding: 10px;
  border: 2px solid #fff;
  background: rgba(255, 255, 255, 0.2);
  border-radius: 10px;
}

.map iframe {
  width: 100%;
  height: 100%;
  border-radius: 5px;
}

@media screen and (max-width: 600px) {
  .contact-section {
    padding: 10px;
    display: flex;
    flex-direction: column;
  }

  .contact-form input,
  .contact-form textarea {
    width: 90%;
    height: 40px;
  }

  .form-submit-btn {
    margin-left: 20px;
  }
  .map {
    width: 100%;
    height: 100%;
    padding: 10px;
    border: 2px solid #fff;
    background: rgba(255, 255, 255, 0.2);
    border-radius: 10px;
  }

  .map iframe {
    width: 100%;
    height: 100%;
    border-radius: 5px;
  }
}
</style>
