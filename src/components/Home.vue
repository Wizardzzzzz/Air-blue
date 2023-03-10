<template>
  <div class="home" id="home">
    <h4>Who we are</h4>
    <p>We embrace a strategic approach to creative ideas. We are interested in people and human relationships. This is
      the main thing you need to know about us. We believe in the power of bold ideas that can solve business
      challenges.</p>
  </div>
  <div class="what-we-do" id="about_us">
    <H1 class="what-we-do-title">Our expertise</H1>
    <div class="item__list">
      <div class="item__first">
        <img class="home__img" src="/public/img/image3.png" alt="image1">
        <h6 class="item__title">Branding</h6>
        <p class="item__suptitle">
          We create additional value for  <br> companies, products, services as well as verbal and visual ways to deliver it
          to <br>the audience.</p>
      </div>
      <div class="item_second">
        <img class="home__img" src="/img/image2.png" alt="image1">
        <h6 class="item__title">Communication</h6>
        <p class="item__suptitle">
          We strive to create communications that can increase media performance. We use everything — words, meanings,
          stories, art, movies.
        </p>
      </div>
      <div class="item_third">
        <img class="home__img" src="/img/image1.png" alt="image1">
        <h6 class="item__title">Strategy</h6>
        <p class="item__suptitle">
          We create business growth strategies, from the moment of its birth to the achievement of the necessary
          business indicators.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home"
}
</script>

<style scoped>
body {
  margin: 0;
  padding: 0;
}

.background {
  background: #F2F9FF;
}

.home {
  padding: 148px 0 0 0;
  margin: 0 423px 0;
}

h4 {
  width: 191px;
  height: 48px;
  font-style: normal;
  font-weight: 600;
  font-size: 32px;
  line-height: 150%;
  /* identical to box height, or 48px */
  display: flex;
  align-items: center;
  /* Text/100 */
  color: #253757;
}

p {
  margin: 16px 0 0 0;
  width: 754px;
  height: 144px;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 150%;
  /* or 36px */
  color: #6C788B;
}

h1 {
  width: 561px;
  height: 78px;
  font-style: normal;
  font-weight: 600;
  font-size: 52px;
  line-height: 150%;
  /* identical to box height, or 78px */
  align-items: center;
  text-align: center;
  /* Text/100 */
  color: #253757;
}

.what-we-do-title {
  margin: 276px 520px 64px 519px;
}

.item__list {
  display: flex;
  justify-content: space-between;
  padding: 0 0 154px 0;
  margin: 0 267px 0 267px;
}

.item__title {
  width: 264px;
  height: 28px;
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 140%;
  /* identical to box height, or 28px */
  text-align: center;
  /* Text/100 */
  color: #253757;
}

.item__suptitle {
  margin-bottom: 100px;
  width: 264px;
  height: 84px;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 150%;
  /* or 21px */
  text-align: center;
  color: #6C788B;
}

.home__img {
  max-height: 166px;
  max-width: 166px;
  margin: 0 auto 40px;
  display: flex;
  justify-content: center;
  border-radius: 24px;
}
</style>