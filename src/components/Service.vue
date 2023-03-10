<template>
  <div class="service">
    <div class="service__info">
      <p class="title">Process</p>
      <h4 class="title__info">Air is a full service creative agency</h4>
      <p class="title__subtitle">Deep analytics, strong strategy and bright creative ideas.
        We are sure that first-rate job is possible only if all three components are united.</p>
    </div>
    <div class="service__list">
      <div class="service__list__item__first">
        <h4 class="service__item__title__first">
          001
        </h4>
        <p class="service__item__subtitle">
          Brand Development
          Copywriting
          <br>Logo & Webite Design
          Packaging
        </p>
        <a>
          <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="20" cy="20" r="20" fill="#56CCF2"/>
            <g clip-path="url(#clip0_9456_184)">
              <path d="M20 12L18.59 13.41L24.17 19H12V21H24.17L18.59 26.59L20 28L28 20L20 12Z" fill="white"/>
            </g>
            <defs>
              <clipPath id="clip0_9456_184">
                <rect width="24" height="24" fill="white" transform="translate(8 8)"/>
              </clipPath>
            </defs>
          </svg>
          Learn more
        </a>

      </div>
      <div class="service__list__item__second">
        <h4 class="service__item__title__Second">
          002
        </h4>
        <p class="service__item__subtitle">
          Сontent Production<br> Graphic Design <br>Video Production <br>Post Production
        </p>
        <a>
          <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="20" cy="20" r="20" fill="#FCC91D"/>
            <g clip-path="url(#clip0_9456_197)">
              <path d="M20 12L18.59 13.41L24.17 19H12V21H24.17L18.59 26.59L20 28L28 20L20 12Z" fill="white"/>
            </g>
            <defs>
              <clipPath id="clip0_9456_197">
                <rect width="24" height="24" fill="white" transform="translate(8 8)"/>
              </clipPath>
            </defs>
          </svg>
          Learn more
        </a>
      </div>
      <div class="service__list__item__third">
        <h4 class="service__item__title__third">
          003
        </h4>
        <p class="service__item__subtitle">
          Marketing Strategy<br>
          Email Marketing<br>
          Paid Advertising<br>
          Blog Content & SEO
        </p>
        <a>
          <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="20" cy="20" r="20" fill="#15D850"/>
            <g clip-path="url(#clip0_9456_210)">
              <path d="M20 12L18.59 13.41L24.17 19H12V21H24.17L18.59 26.59L20 28L28 20L20 12Z" fill="white"/>
            </g>
            <defs>
              <clipPath id="clip0_9456_210">
                <rect width="24" height="24" fill="white" transform="translate(8 8)"/>
              </clipPath>
            </defs>
          </svg>
          Learn more
        </a>
      </div>
      <div class="service__list__item__four">
        <h4 class="service__item__title__four">
          004
        </h4>
        <p class="service__item__subtitle">
          Digital Communications<br>
          Influencer Marketing<br>
          Product Placements<br>
          Strategic Partnerships
        </p>
        <a>
          <svg width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="24" cy="24" r="24" fill="#F36363"/>
            <g clip-path="url(#clip0_9456_223)">
              <path d="M24 16L22.59 17.41L28.17 23H16V25H28.17L22.59 30.59L24 32L32 24L24 16Z" fill="white"/>
            </g>
            <defs>
              <clipPath id="clip0_9456_223">
                <rect width="24" height="24" fill="white" transform="translate(12 12)"/>
              </clipPath>
            </defs>
          </svg>
          Learn more
        </a>
      </div>
    </div>
  </div>
  <!--  <div class="work">-->

  <!--  </div>-->
</template>

<script>
export default {
  name: "AboutUs"
}
</script>
<style scoped>
/*.work {*/
/*  margin: 0 auto;*/
/*  width: 1479px;*/
/*  height: 976px;*/
/*  background: #FF9C8E;*/
/*}*/

.service__info {
  flex: 0 0 50%;
  margin: 110px 0 0 0;
}

.service__list {
  flex: 0 0 50%;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(5, 1fr);
  grid-column-gap: 30px;
  grid-row-gap: 30px;
}


.service__list__item__first {
  grid-area: 2 / 1 / 4 / 3;
  background: #ffffff;
  border-radius: 24px;

}

.service__list__item__second {
  grid-area: 1 / 3 / 3 / 5;
  background: #ffffff;
  border-radius: 24px;

}

.service__list__item__third {
  grid-area: 4 / 1 / 6 / 3;
  background: #ffffff;
  border-radius: 24px;

}

.service__list__item__four {
  grid-area: 3 / 3 / 5 / 5;
  background: #ffffff;
  border-radius: 24px;

}
.service__item__subtitle {
  margin: 0 auto;
  padding: 32px 26px 32px 32px;
  width: 200px;
  height: 80px;
  font-style: normal;
  font-weight: 600;
  font-size: 13px;
  line-height: 150%;
  /* or 20px */
  color: #6C788B;
}

.service {
  display: flex;
  margin: 0 250px 0 227px;
  justify-content: space-between;
  column-gap: 3%;
}

.title__info {

  width: 362px;
  height: 84px;
  font-style: normal;
  font-weight: 600;
  font-size: 32px;
  line-height: 130%;
  /* or 42px */
  display: flex;
  align-items: center;
  /* Text/100 */
  color: #253757;
}

.title__subtitle {
  width: 362px;
  height: 105px;
  left: 227px;
  top: 2457px;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 150%;
  /* or 21px */
  color: #6C788B;
}

.title {
  width: 78px;
  height: 20px;
  font-style: normal;
  font-weight: 700;
  font-size: 13px;
  line-height: 20px;
  /* identical to box height */
  text-align: center;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #C0CDD7;
}

a {
  padding: 0 0 32px 32px;
  display: flex;
  column-gap: 16px;
  align-items: center;
  font-style: normal;
  font-weight: 600;
  font-size: 15px;
  line-height: 22px;
  /* identical to box height */
  text-align: center;
  /* Text/200 */
  color: #334563;
}

.service__item__title__first {
  padding: 34px 44px 0 44px;
  width: 22px;
  height: 20px;
  font-style: normal;
  font-weight: 600;
  font-size: 13px;
  line-height: 20px;
  /* identical to box height */
  text-align: center;
  text-transform: uppercase;
  color: #56CCF2;
}

.service__item__title__Second {
  padding: 34px 44px 0 44px;
  width: 25px;
  height: 20px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 13px;
  line-height: 20px;
  /* identical to box height */
  text-align: center;
  text-transform: uppercase;
  color: #FCC91D;
}

.service__item__title__third {
  padding: 34px 44px 0 44px;
  width: 25px;
  height: 20px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 13px;
  line-height: 20px;
  /* identical to box height */
  text-align: center;
  text-transform: uppercase;
  color: #15D850;
}

.service__item__title__four {
  padding: 34px 44px 0 44px;
  width: 26px;
  height: 20px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 13px;
  line-height: 20px;
  /* identical to box height */
  text-align: center;
  text-transform: uppercase;
  color: #F36363;

}
</style>