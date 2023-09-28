<template>
  <div class="new-main">
    <div class="new-main1">
      <div class="new-maintext">
        <p><span>Homepage</span> / <span>News</span></p>
        <h1>NEWS</h1>
        <h3>Stay tuned with our news, expert tips and articles.</h3>
      </div>
      <div class="new-mainfon"></div>
    </div>



  </div>
  <div class="new-nextslide">
    <div>
      <h2>Categories</h2>
    </div>
    <div class="button">
      <button>All News</button>
      <button>Company News</button>
      <button>Innovation</button>
      <button>Industry News</button>
      <button>Expert Tips</button>
      <button>Marketing</button>
    </div>
    <div class="new-img">

      <div><img src="src/img/portfolio-card/article/image.png" alt="">
        <div class="new-img-text">
          <p class="slogo">How to Build Climate Change-Resilient Infrastructure</p>


          <div class="comment">
            <p> Industry News
              <span>|</span> June 24, 2020
              <span>|</span> <img src="src/img/portfolio-card/article/Chat.png" alt=""> 4 comments
            </p>
          </div>


          <p>Ipsum aliquet nisi, hendrerit rhoncus quam tortor, maecenas faucibus. <br> Tincidunt aliquet sit vel,
            venenatis
            nulla. Integer bibendum turpis convallis...</p>
        </div>
      </div>
      <div><img src="src/img/portfolio-card/article/image (2).png" alt="">
        <div class="new-img-text">
          <p class="slogo">How Construction Can Help Itself</p>


          <div class="comment">
            <p>Innovation
              <span>|</span> June 12, 2020
              <span>|</span> <img src="src/img/portfolio-card/article/Chat.png" alt=""> No comments
            </p>
          </div>

          <p>Porta habitant vitae quam interdum. Leo viverra non volutpat rhoncus <br> placerat vitae scelerisque. Rhoncus
            augue faucibus maecenas lacus...</p>
        </div>
      </div>
      <div><img src="src/img/portfolio-card/article/image (3).png" alt="">
        <div class="new-img-text">

          <p class="slogo">The Difference Between a Digger and an Excavator</p>


          <div class="comment">
            <p>Expert Tips
              <span>|</span> May 16, 2020
              <span>|</span> <img src="src/img/portfolio-card/article/Chat.png" alt=""> No comments
            </p>
          </div>


          <p>Cras est nisi purus velit facilisi vitae, dolor. Lorem scelerisque integer duis et <br> nulla lobortis
            cursus.
            Viverra erat sollicitudin praesent viverra...</p>
        </div>
      </div>
      <div><img src="src/img/portfolio-card/article/image (4).png" alt="">
        <div class="new-img-text">
          <p class="slogo">Building Construction Hand Tools</p>


          <div class="comment">
            <p>Expert Tips
              <span>|</span> February 25, 2020
              <span>|</span> <img src="src/img/portfolio-card/article/Chat.png" alt=""> 1 comment
            </p>
          </div>


          <p>Tellus quis aliquet volutpat nunc pulvinar donec sed sapien. Vitae elit id <br> dolor, tristique massa. Fames
            lobortis orci rutrum bibendum integer...</p>
        </div>
      </div>
      <div><img src="src/img/portfolio-card/article/image (5).png" alt="">
        <div class="new-img-text">
          <p class="slogo">Top 10 Construction Trends</p>


          <div class="comment">
            <p>Industry News
              <span>|</span> January 14, 2020
              <span>|</span> <img src="src/img/portfolio-card/article/Chat.png" alt=""> No comments
            </p>
          </div>


          <p>Dignissim sed enim, eleifend morbi condimentum. Congue id quis vulputate <br> dignissim eget. Ac ullamcorper
            nunc habitasse enim interdum platea...</p>
        </div>
      </div>
      <div><img src="src/img/portfolio-card/article/image (6).png" alt="">
        <div class="new-img-text">
          <p class="slogo">Types of Flooring Materials</p>


          <div class="comment">
            <p>Company News
              <span>|</span>
              December 1, 2019 <span>|</span>
              <img src="src/img/portfolio-card/article/Chat.png" alt=""> No comments
            </p>
          </div>


          <p>Maecenas donec lacinia nunc, quam sit magnis mauris. Neque bibendum et <br> mauris, aenean. Vel arcu amet in
            sem parturient integer duis et nulla...</p>
        </div>
      </div>
    </div>
    <div></div>
  </div>
</template>
  
<style>
.new-img-text p:nth-child(3) {
  color: var(--gray-800, #424551);

/* base/regular */
font-family: Ubuntu;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 160%; /* 25.6px */
}
.new-img-text span {
  margin: 0 12px;
  color: var(--gray-700, #787A80);
  font-family: Ubuntu;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;

}

.comment p {
  color: var(--gray-700, #787A80);
/* small/regular */
font-family: Ubuntu;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 21px */
}

.comment {
  display: inline-flex;
  align-items: center;
  gap: 12px;
}

.new-img-text>p :nth-child(2) {
  color: var(--gray-700, #787A80);
  /* small/regular */
  font-family: Ubuntu;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;
  /* 21px */
}


.new-img-text {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 12px;
  padding: 24px 24px 21px 24px;
}

.slogo {
  color: var(--gray-900, #1E212C);


  font-family: Ubuntu;
  font-size: 20px;
  font-style: normal;
  font-weight: 700;
  line-height: 150%;
}

.new-img>div {
  border-radius: 4px;
  background: var(--white, #FFF);
  max-width: 600px;
  min-height: 482px;

  box-shadow: 0px 4px 4px -4px rgba(30, 33, 44, 0.03), 0px 12px 10px -6px rgba(154, 156, 165, 0.04), 0px 30px 24px -10px rgba(154, 156, 165, 0.05), 0px 80px 80px -20px rgba(154, 156, 165, 0.08);
}

.new-img {
  margin: 30px 0;
  gap: 30px;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.button {
  margin: 60px 0;
}

.new-nextslide div>button:focus:active {
  border-radius: 4px;
  border: 1px solid var(--primary, #FF5A30);
  color: #FF5A30;

}

.new-nextslide div>button {
  min-height: 46px;
  min-width: 205px;
  color: var(--gray-600, #9A9CA5);
  text-align: center;
  font-family: Ubuntu;
  font-size: 16px;
  font-style: normal;
  font-weight: 700;
  line-height: 160%;
  background: none;
  border: none;

}


.new-nextslide h2 {
  display: flex;
  justify-content: center;
  color: var(--gray-900, #1E212C);
  text-align: center;

  font-family: Ubuntu;
  font-size: 46px;
  font-style: normal;
  font-weight: 700;
  line-height: 130%;

}

.new-nextslide {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 120px;
  background: var(--white, #FFF);
  max-width: 1920px;
}

.new-maintext {
  position: relative;
  left: 80px;
}

.new-maintext p {
  padding: 0 0 53px 0;
}

.new-maintext p :nth-child(1) {
  color: var(--gray-800, #424551);


  font-family: Ubuntu;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;
}

.new-maintext p :nth-child(2) {
  color: var(--gray-600, #9A9CA5);


  font-family: Ubuntu;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;
}

.new-maintext h1 {
  color: var(--gray-900, #1E212C);
  font-family: Ubuntu;
  font-size: 72px;
  font-style: normal;
  font-weight: 700;
  line-height: 130%;
  letter-spacing: 1px;
}

.new-maintext h3 {
  color: var(--gray-700, #787A80);


  font-family: Ubuntu;
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 150%;
}

.new-mainfon {
  width: 1080px;
  height: 600px;
  /* background: linear-gradient(90deg, #F4F5F6 0%, rgba(244, 245, 246, 0.86) 11.48%, rgba(244, 245, 246, 0.00) 41.15%); */
  background-image: linear-gradient(90deg, #F4F5F6 0%, rgba(244, 245, 246, 0.86) 11.48%, rgba(244, 245, 246, 0.00) 41.15%), url(../img/hand.png);
  background-size: cover;

  position: relative;
  left: 175px;


}

.new-main1 {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  max-width: 1920px;
}

.new-main {
  max-width: 1920px;
  background: var(--gray-200, #F4F5F6);


}
</style>
  