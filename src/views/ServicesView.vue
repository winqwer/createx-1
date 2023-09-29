<template>
  <div class="serv-main">
    <div class="serv-main1">

      <div class="serv-maintext">
        <p><span>Homepage</span> / <span>Services</span></p>
        <h1>SERVICES</h1>
        <h3>If you are looking for a full-service construction company, look <br> to Createx Construction Bureau. We are
          doing our best <br> to be a partner for all of your construction needs.</h3>
      </div>
      <img class="serv-mainfon" src="../img/serv-fon-main.png" alt="">
    </div>
  </div>
  <div class="serv-mainslide">
    <div class="serv-text-mainslide">
      <img src="../img/serv-first-image.png" alt="">
      <div class="textimage">
        <h3>Construction</h3>
        <p>Sapien, feugiat faucibus orci arcu, vulputate. Tristique varius consectetur <br> vulputate arcu, scelerisque
          nisi, nibh. Enim semper id sodales ultricies sed ut ut <br> augue. Mattis habitant venenatis, gravida posuere
          massa ac interdum. Eget <br> aliquam dignissim ut vestibulum. </p>
        <button>Learn more</button>
      </div>
    </div>
    <div>
      <div class="serv-text-mainslide">

        <div class="textimage">
          <h3>Project Development</h3>
          <p>Volutpat tellus mauris sit sit. Posuere ut sit vestibulum amet viverra in. Est <br> nulla lectus purus
            tincidunt massa tortor. Hendrerit vulputate elementum <br> blandit massa vitae amet felis eget. </p>
          <button>Learn more</button>
        </div>
        <img src="../img/serv-two-image.png" alt="">
      </div>
    </div>
    <div>
      <div class="serv-text-mainslide">
        <img src="../img/serv-thre-image.png" alt="">
        <div class="textimage">
          <h3>Interior Design</h3>
          <p>Eleifend orci massa et facilisis orci feugiat ac. Congue in ut lacus, turpis <br> accumsan gravida.
            Aliquet
            mattis dignissim massa sociis a, id bibendum. <br> Egestas lorem eros, mi cras amet, vel eget molestie. Turpis
            enim
            arcu, amet <br> donec massa pellentesque nulla duis. Arcu dictum metus sed purus senectus <br> faucibus eget
            elementum
            pretium. </p>
          <button>Learn more</button>
        </div>
      </div>
    </div>
    <div>
      <div class="serv-text-mainslide">

        <div class="textimage">
          <h3>Repairs</h3>
          <p>Facilisis cursus feugiat sit pulvinar amet. Ac facilisi dictum commodo, tortor <br> gravida pretium, orci.
            Nunc
            sit sollicitudin id egestas mattis. Turpis viverra nec <br> urna ultrices urna. </p>
          <button>Learn more</button>
        </div>
        <img src="../img/serv-four-image.png" alt="">
      </div>
    </div>
  </div>
</template>
  
<style>
.serv-text-mainslide button:active {
border-radius: 4px;
background: var(--primary, #FF5A30);
color: var(--white, #FFF);
}
.serv-text-mainslide button {
  margin: 48px 0 0 0;
  color: var(--primary, #FF5A30);
text-align: center;
font-family: Ubuntu;
font-size: 14px;
font-style: normal;
font-weight: 700;
line-height: 44px; /* 314.286% */
letter-spacing: 0.5px;
text-transform: uppercase;
width: 160px;
height: 44px;
border-radius: 4px;
border: 1px solid var(--primary, #FF5A30);
background: none;
}
.serv-text-mainslide p {
  color: var(--gray-700, #787A80);

  /* base/regular */
  font-family: Ubuntu;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 160%;
  /* 25.6px */
}

.serv-text-mainslide h3 {
  margin: 0px 0 24px 0;
  color: var(--gray-900, #1E212C);

  /* h2 */
  font-family: Ubuntu;
  font-size: 32px;
  font-style: normal;
  font-weight: 700;
  line-height: 150%;
  /* 48px */
}

.serv-text-mainslide {
  gap: 80px;
  display: flex;
  align-items: center;
}

.serv-mainslide {
  margin: 120px 0px;
  gap: 120px;
  display: flex;
  align-items: center;
  flex-direction: column;
}

.serv-text-mainslide img {
  width: 575px;
  height: 420px;
}

.serv-maintext {
  position: relative;
  left: 77px;
}

.serv-maintext h3 {
  padding: 24px 0px 0px 0px;
  color: var(--gray-700, #787A80);

  /* lead/regular */
  font-family: Ubuntu;
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;
  /* 30px */
}

.serv-maintext h1 {
  color: var(--gray-900, #1E212C);

  /* display/1 */
  font-family: Ubuntu;
  font-size: 72px;
  font-style: normal;
  font-weight: 700;
  line-height: 130%;
  /* 93.6px */
  letter-spacing: 1px;
}

.serv-maintext p {
  padding: 0 0 40px 0;
}

.serv-maintext p :nth-child(1) {
  color: var(--gray-800, #424551);

  /* small/regular */
  font-family: Ubuntu;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;
  /* 21px */
}

.serv-maintext p :nth-child(2) {
  color: var(--gray-600, #9A9CA5);

  /* small/regular */
  font-family: Ubuntu;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;
  /* 21px */

}

.serv-main {
  max-width: 1920px;
  background: var(--gray-200, #F4F5F6);

}

.serv-main1 {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  max-width: 1920px;
}

.serv-mainfon {
  position: relative;
  left: 175px;

}</style>
  