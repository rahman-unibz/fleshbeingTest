<template>
  <div class="certificates">
    <div class="title">
      <h3>Le Nostre Certificazioni</h3>
      <h5>unici in Trento Alto Adige</h5>
    </div>
    <div class="box-container">
      <div class="box">
        <img src="/certificate_1.png" alt="certificate_1" />
        <h6>3M Architectural Market</h6>
        <p>certificazione x prodotti interior design</p>
      </div>
      <div class="box">
        <img src="/certificate_2.png" alt="certificate_2" />
        <h6>3M Window Film</h6>
        <p>certificazione per pellicole a controllo solare</p>
      </div>
      <div class="box">
        <img src="/certificate_3.png" alt="certificate_3" />
        <h6>3M Endorsed</h6>
        <p>certificazione legata al mondo del wrapping</p>
      </div>
    </div>
  </div>
</template>
<style scoped>
.certificates {
  max-width: 1004px;
  margin: 0 auto;
  padding-top: 50px;
}

h3 {
  font-size: 24px;
  line-height: 25px;
  text-transform: uppercase;
  margin-bottom: 10px;
}

h5 {
  font-size: 21px;
  line-height: 25px;
  color: #646464;
}

h6 {
  font-size: 20px;
  font-family: 'Spartan', sans-serif;
  color: #000;
  margin-top: 30px;
}

.box-container {
  margin: 60px 0;
  display: flex;
}

.box-container .box {
  flex-basis: 33.33%;
  padding-bottom: 20px;
}

.box-container .box p {
  font-size: 16px;
  font-family: 'Playfair Display', serif;
  color: #646464;
  font-weight: 600;
}
</style>
