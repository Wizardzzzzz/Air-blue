<template>
  <footer class="footer__container">
    <div class="footer">
      <div class="footer__form">
        <div class="text__form">
          <h3 class="title__text">Send us a message</h3>
          <div class="form">
            <input class="email" type="email" placeholder="Email">
            <input class="name" type="text" placeholder="Your name">
            <input class="text" type="text" placeholder="Your message">
          </div>
          <button>Send</button>
        </div>
        <div class="text__form">
          <h3 class="title__text__second">Contact us</h3>
          <div class="form">
            <P class="form__text__subtitle">call us</P>
            <P class="form__number__subtitle">654 321 987</P>
            <P class="form__text__subtitle">visit us</P>
            <P class="form__number__subtitle">2905 West Drive, Buffalo Grove</P>
            <P class="form__text__subtitle">our social</P>
            <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
              <g clip-path="url(#clip0_9456_60)">
                <path
                    d="M22.6667 4.66674C22.6667 4.48993 22.5964 4.32036 22.4714 4.19533C22.3464 4.07031 22.1768 4.00007 22 4.00007H18.6667C16.9882 3.91646 15.3448 4.50059 14.0956 5.62484C12.8465 6.7491 12.093 8.32207 12 10.0001V13.6001H8.66667C8.48986 13.6001 8.32029 13.6703 8.19526 13.7953C8.07024 13.9204 8 14.0899 8 14.2667V17.7334C8 17.9102 8.07024 18.0798 8.19526 18.2048C8.32029 18.3298 8.48986 18.4001 8.66667 18.4001H12V27.3334C12 27.5102 12.0702 27.6798 12.1953 27.8048C12.3203 27.9298 12.4899 28.0001 12.6667 28.0001H16.6667C16.8435 28.0001 17.013 27.9298 17.1381 27.8048C17.2631 27.6798 17.3333 27.5102 17.3333 27.3334V18.4001H20.8267C20.9749 18.4022 21.1197 18.3548 21.238 18.2655C21.3563 18.1762 21.4415 18.0499 21.48 17.9067L22.44 14.4401C22.4665 14.3416 22.4701 14.2383 22.4504 14.1382C22.4308 14.0381 22.3884 13.9438 22.3265 13.8627C22.2647 13.7816 22.1851 13.7157 22.0938 13.6701C22.0025 13.6246 21.902 13.6006 21.8 13.6001H17.3333V10.0001C17.3665 9.67004 17.5215 9.36422 17.768 9.14233C18.0146 8.92044 18.335 8.79841 18.6667 8.80007H22C22.1768 8.80007 22.3464 8.72983 22.4714 8.60481C22.5964 8.47978 22.6667 8.31022 22.6667 8.1334V4.66674Z"
                    fill="white"/>
              </g>
              <defs>
                <clipPath id="clip0_9456_60">
                  <rect width="32" height="32" fill="white"/>
                </clipPath>
              </defs>
            </svg>
            <svg class="social" width="32" height="32" viewBox="0 0 32 32" fill="none"
                 xmlns="http://www.w3.org/2000/svg">
              <g clip-path="url(#clip0_9456_65)">
                <path
                    d="M10.7724 26.6671C12.744 26.733 14.7088 26.4031 16.5507 25.6968C18.3926 24.9905 20.0743 23.9221 21.4963 22.5548C22.9183 21.1875 24.0517 19.549 24.8297 17.7362C25.6077 15.9234 26.0144 13.973 26.0257 12.0004C26.9293 10.8823 27.6002 9.59482 27.9991 8.21372C28.0289 8.1046 28.0264 7.9892 27.9922 7.88142C27.9579 7.77363 27.8931 7.67806 27.8058 7.6062C27.7184 7.53435 27.6122 7.48928 27.4998 7.47642C27.3874 7.46356 27.2737 7.48346 27.1724 7.53372C26.6997 7.76126 26.1675 7.83475 25.6509 7.74386C25.1342 7.65296 24.6591 7.40225 24.2924 7.02705C23.8243 6.51449 23.2582 6.10109 22.6274 5.81135C21.9966 5.52162 21.3141 5.36143 20.6203 5.3403C19.9265 5.31916 19.2356 5.4375 18.5883 5.6883C17.9411 5.9391 17.3508 6.31727 16.8524 6.80038C16.17 7.46126 15.6702 8.28744 15.4015 9.19862C15.1328 10.1098 15.1044 11.075 15.3191 12.0004C10.8524 12.2671 7.78574 10.1471 5.33241 7.24038C5.25871 7.15692 5.1623 7.09672 5.05495 7.06714C4.9476 7.03757 4.83396 7.03989 4.72791 7.07382C4.62186 7.10776 4.52799 7.17184 4.45775 7.25825C4.38752 7.34465 4.34397 7.44964 4.33241 7.56038C3.86504 10.1529 4.20218 12.8264 5.29857 15.2218C6.39495 17.6172 8.19807 19.6197 10.4657 20.9604C8.94526 22.7042 6.81002 23.7933 4.50575 24.0004C4.38229 24.0209 4.26833 24.0794 4.17981 24.1679C4.09129 24.2563 4.03264 24.3702 4.01207 24.4937C3.9915 24.6171 4.01003 24.7439 4.06508 24.8563C4.12013 24.9686 4.20894 25.061 4.31908 25.1204C6.32377 26.1222 8.53139 26.6513 10.7724 26.6671Z"
                    fill="#D2EBFF"/>
              </g>
              <defs>
                <clipPath id="clip0_9456_65">
                  <rect width="32" height="32" fill="white"/>
                </clipPath>
              </defs>
            </svg>
            <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path
                  d="M16.0027 9.8467C12.5974 9.8467 9.85075 12.594 9.85075 16C9.85075 19.406 12.5974 22.1533 16.0027 22.1533C19.4079 22.1533 22.1546 19.406 22.1546 16C22.1546 12.594 19.4079 9.8467 16.0027 9.8467ZM16.0027 20.0004C13.8021 20.0004 12.0031 18.2064 12.0031 16C12.0031 13.7936 13.7968 11.9996 16.0027 11.9996C18.2086 11.9996 20.0022 13.7936 20.0022 16C20.0022 18.2064 18.2032 20.0004 16.0027 20.0004ZM23.8412 9.595C23.8412 10.3929 23.1987 11.0302 22.4062 11.0302C21.6085 11.0302 20.9713 10.3876 20.9713 9.595C20.9713 8.80241 21.6138 8.15977 22.4062 8.15977C23.1987 8.15977 23.8412 8.80241 23.8412 9.595ZM27.9157 11.0517C27.8247 9.12909 27.3856 7.42608 25.9775 6.02298C24.5747 4.61988 22.8721 4.18074 20.9499 4.08435C18.9689 3.97188 13.0311 3.97188 11.0501 4.08435C9.1333 4.17539 7.43068 4.61453 6.02253 6.01763C4.61439 7.42073 4.1807 9.12373 4.08433 11.0463C3.97189 13.0278 3.97189 18.9669 4.08433 20.9483C4.17535 22.8709 4.61439 24.5739 6.02253 25.977C7.43068 27.3801 9.12794 27.8193 11.0501 27.9157C13.0311 28.0281 18.9689 28.0281 20.9499 27.9157C22.8721 27.8246 24.5747 27.3855 25.9775 25.977C27.3803 24.5739 27.8193 22.8709 27.9157 20.9483C28.0281 18.9669 28.0281 13.0331 27.9157 11.0517ZM25.3564 23.0744C24.9388 24.1241 24.1303 24.9327 23.0755 25.3558C21.496 25.9824 17.7481 25.8378 16.0027 25.8378C14.2572 25.8378 10.504 25.977 8.92984 25.3558C7.88042 24.9381 7.07195 24.1294 6.64897 23.0744C6.02253 21.4946 6.16709 17.7458 6.16709 16C6.16709 14.2542 6.02789 10.5001 6.64897 8.92558C7.06659 7.87593 7.87507 7.06728 8.92984 6.6442C10.5093 6.01763 14.2572 6.16222 16.0027 6.16222C17.7481 6.16222 21.5014 6.02298 23.0755 6.6442C24.1249 7.06192 24.9334 7.87058 25.3564 8.92558C25.9828 10.5054 25.8383 14.2542 25.8383 16C25.8383 17.7458 25.9828 21.4999 25.3564 23.0744Z"
                  fill="white"/>
            </svg>

          </div>
        </div>
      </div>
    </div>
    <div class="icon">
      <div class="footer__nav">
        <a href>
          <svg width="45" height="26" viewBox="0 0 45 26" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path
                d="M7.128 17.964L13.428 4.356L19.728 17.964H7.128ZM21.24 21.204L23.292 25.632H26.856L15.12 0.431998H11.736L0 25.632H3.564L5.616 21.204H21.24Z"
                fill="white"/>
            <path
                d="M27.2025 2.448C27.2025 3.168 27.4185 3.744 27.8865 4.212C28.3545 4.68 28.9305 4.896 29.6505 4.896C30.3345 4.896 30.9105 4.68 31.3785 4.212C31.8465 3.744 32.0985 3.168 32.0985 2.448C32.0985 1.764 31.8465 1.188 31.3785 0.719999C30.9105 0.251999 30.3345 0 29.6505 0C28.9305 0 28.3545 0.251999 27.8865 0.719999C27.4185 1.188 27.2025 1.764 27.2025 2.448ZM31.1985 7.632H28.1025V25.632H31.1985V7.632Z"
                fill="white"/>
            <path
                d="M37.6183 10.332V7.632H34.6303V25.632H37.7263V17.244C37.7263 16.236 37.7983 15.336 37.9783 14.472C38.1223 13.644 38.4103 12.924 38.8423 12.312C39.2743 11.736 39.8143 11.268 40.4983 10.944C41.1463 10.62 42.0103 10.44 43.0183 10.44C43.3423 10.44 43.6303 10.476 43.9183 10.512C44.2063 10.548 44.4943 10.584 44.8183 10.656V7.38C44.5303 7.344 44.2423 7.308 43.9543 7.272C43.6663 7.236 43.3423 7.2 43.0543 7.2C41.7583 7.2 40.6783 7.488 39.7783 8.028C38.8783 8.568 38.1583 9.324 37.6183 10.332Z"
                fill="white"/>
          </svg>
        </a>
        <nav>
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About us</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Work</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </nav>
      </div>
    </div>

  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
.footer__container {
  max-width: 1600px;
  background: #008AFF;
  width: 100%;
  height: 867px;
  border-radius: 0 200px 0 0;
}

.footer__form {
  display: flex;
  justify-content: space-between;
  padding: 0 400px 0 227px;

}

.title__text {
  padding-top: 180px;
  width: 325px;
  height: 48px;
  left: 227px;
  top: 5687px;
  font-style: normal;
  font-weight: 500;
  font-size: 32px;
  line-height: 150%;
  /* identical to box height, or 48px */
  display: flex;
  align-items: center;
  color: #FFFFFF;
}

.form {
  max-width: 460px;
}

.email {
  background: #008AFF;
  border: unset;
  border-bottom: 1px solid white;
  padding: 0 241px 15px 0;
  margin: 56px 0 0 0;
  color: #ffffff !important;
}

.name {
  background: #008AFF;
  border: unset;
  border-bottom: 1px solid white;
  padding: 0 241px 15px 0;
  margin: 56px 0 0 0;
  color: #ffffff !important;
}

.text {
  background: #008AFF;
  border: unset;
  border-bottom: 1px solid white;
  padding: 0 241px 15px 0;
  margin: 56px 0 0 0;
  color: #ffffff !important;
}

.form input:hover {
  border-bottom: 2px solid white;

}

button {
  margin-top: 80px;
  width: 226px;
  height: 56px;
  color: white;
  background: #FF9C8E;
  border-radius: 64px;
  border: white;
  font-weight: 600;
}

.form input::placeholder {
  color: white;
}

.form__text__subtitle {
  padding-top: 26px;
  width: 112px;
  height: 20px;
  font-style: normal;
  font-weight: 700;
  font-size: 13px;
  line-height: 20px;
  /* identical to box height */
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #FFFFFF;
  opacity: 0.5;
}

.form__number__subtitle {
  margin: 0 auto;
  width: 356px;
  height: 36px;
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 150%;
  /* identical to box height, or 36px */
  color: #FFFFFF;
}

.title__text__second {
  padding-top: 180px;
  font-style: normal;
  font-weight: 500;
  font-size: 32px;
  line-height: 150%;
  /* identical to box height, or 48px */
  display: flex;
  align-items: center;
  color: #FFFFFF;
}

.social {
  padding: 0 16px 0 16px;
}

.footer__nav {
  margin: 121px 228px;
  display: flex;
  column-gap: 80px;
  align-items: center;
}

header {
  line-height: 1.5;
  height: 867px;
  background-color: #2C2C2C;
  padding: 0 227px;

}

ul {
  display: flex;
  column-gap: 60px;
  padding: 0;
}

li {
  list-style-type: none;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
  border-radius: 30px 0;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
  display: flex;
  justify-content: end;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>