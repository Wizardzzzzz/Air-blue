<template>
  <div class="home">
    <div class="home__text">
      <h1 style="
font-style: normal;
font-weight: 600;
font-size: 64px;
line-height: 68px;
/* or 106% */
letter-spacing: -2px;
color: #FFFFFF;
">Strategic <br>Agency</h1>
      <p >We believe in the power of bold ideas that <br>can solve business challenges.</p>
      <button>Learn more</button>
    </div>
    <div class="slider">
      <swiper :navigation="true" :modules="modules" id="mySlider">
        <swiper-slide>
          <div style="position: relative">
            <img src="/public/img/slider1.png" alt="slider1">
            <div class="slider__text" style="position: absolute; left: 20%; top: 75%;">
              <h2>Intro</h2>
              <p class="subtitle">By the same illusion which lifts the <br>horizon.</p>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div style="position: relative">
            <img src="/public/img/slider2.png" alt="slider1">
            <div class="slider__text" style="position: absolute; left: 20%; top: 75%;">
              <h2>Intro</h2>
              <p class="subtitle">By the same illusion which lifts the <br>horizon.</p>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div style="position: relative">
            <img src="/public/img/slider3.png" alt="slider1">
            <div class="slider__text" style="position: absolute; left: 20%; top: 75%;">
              <h2>Intro</h2>
              <p class="subtitle">By the same illusion which lifts the <br>horizon.</p>
            </div>
          </div>
        </swiper-slide>
      </swiper>
    </div>
  </div>
</template>

<script>
import {Swiper, SwiperSlide} from 'swiper/vue';
import 'swiper/css';
import 'swiper/css/navigation';
import {Navigation} from 'swiper';

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Navigation],
    };
  },
};
</script>
<style scoped>
.swiper {
  max-width: 687px;
  max-height: 652px;
  min-height: 300px;
  width: 100%;
  height: 100%;
}
.slider__text{

}
.subtitle{
  margin: 0 0 0 22px;
  text-align: left;
  width: 264px;
  height: 40px;
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 140%;
  /* or 20px */
  color: #FFFFFF;
}
p {

  text-align: left;
  width: 264px;
  height: 40px;
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 140%;
  /* or 20px */
  color: #FFFFFF;
}

h2 {
  margin: 30px  0  0 22px;
  width: 52px;
  height: 20px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 700;
  font-size: 13px;
  line-height: 20px;
  /* identical to box height */
  text-align: center;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #FFFFFF;
}

.swiper-slide {
  text-align: center;
  font-size: 18px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.home {
  display: flex;
  padding-left: 227px;
}

.slider {
  flex: 0 0 50%;
}

.home__text {
  flex: 0 0 50%;
}

:deep(.swiper-button-prev) {
  left: 8%;
  top: 90%;
  height: 32px;
  width: 32px;
  border-radius: 20px;
  background-color: #ffffff;
}

:deep(.swiper-button-next) {
  left: 15%;
  top: 90%;
  height: 32px;
  width: 32px;
  border-radius: 20px;
  background-color: #ffffff;
}

:deep(.swiper-button-prev),
:deep(.swiper-button-next) {
  color: #253757;
  background-color: #FFFFFF;
  border-radius: 50px;
  width: 15px;
  height: 15px;
  padding: 11px;
  top: 84%;
  --swiper-navigation-size: 16px
}

.home__text {
  margin-top: 80px;
}

p {
  color: white;
}

button {
  margin-top: 63px;
  width: 226px;
  height: 50px;
  color: white;
  background: #FF9C8E;
  border-radius: 64px;
  border: white;
}

img {
  border-top-left-radius: 200px;
}

h1 {
  width: 490px;
  height: 136px;
  left: 218px;
  top: 240px;
  font-style: normal;
  font-weight: 600;
  font-size: 64px;
  line-height: 68px;
  /* or 106% */
  letter-spacing: -2px;
  color: #FFFFFF;
}

p {
  width: 362px;
  height: 54px;
  left: 218px;
  top: 408px;
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 150%;
  /* or 27px */
  color: #FFFFFF;
}

</style>