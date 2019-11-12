<template>
  <main>
    <!-- start -->
    <section class="hero">
          <h1>SF BAY AREA INSURANCE</h1>
    <article>
      <p>"This is the precept by which I have lived: Prepare for the worst; expect the best; and take what comes." </p>
      <p>~ Hannah Arendt</p>
    </article>

      <!-- <div class="hero-header">  -->
        <!-- <h1>bay area CAR INSURANCE</h1> -->
        <!-- background photo credit: https://www.twenty20.com/photos/f221bd8f-d1ec-4f61-bba7-b2e5d797ff3e/?utm_t20_channel=bl -->
      <!-- </div> -->
    </section> 

    <div class="cta-box secondary-background-color">
      <ul>
        <li>
          <h3 class="fl-heading secondary-color">
            <span class="fl-heading-text">GET A FREE ATLANTA INSURANCE QUOTE</span>
          </h3>
        </li>
        <li>
            <button class="bg-green-500 
              hover:bg-green-400 
              text-white font-bold 
              py-2 px-4 
              border-b-4 
              border-green-700 
              hover:border-green-500 
              rounded
              w-10/12">
            Instant Quote
          </button>
        </li>
        <li >
          <button class="bg-white
            hover:bg-gray-400 
            text-blue-500
            font-bold 
            py-2 
            px-4 
            rounded
            w-10/12">
            Instant Quote
          </button>
        </li>
      </ul>
    </div>     
<!-- end -->
  </main>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss" scoped>
.container {
  word-wrap: break-word;
  overflow-wrap: break-word;
}
.secondary-color {
  color: #ffffff;
}
.secondary-background-color {
  background: #1a92cd;
}
/* .hero {
display: grid;
grid-template-columns: repeat(5, 1fr);
grid-template-rows: repeat(5, 1fr);
grid-column-gap: 0px;
grid-row-gap: 0px;
align-items: stretch;
}
*/
/* Styles for the hero image */
.hero {
  /* Photo by mnm.all on Unsplash */
  background: url('~assets/images/road-trip-to-nowhere_t20_oow6yx.jpg') center;
  background-size: cover;
  padding: 4rem 2rem;
  /* grid styles */
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  align-items: center;
  height: 75vh;
}

.hero > * {
  color: white;
}

.hero > h1 {
  font-size: 4rem;
  padding-bottom: 1rem;
}

.hero > article > p {
  font-size: 1.2rem;
  font-weight: 200;
}

.hero > article > a {
  padding: 1rem;
  margin-top: .75rem;
}

/* Styles for Call to Action */
.cta-box {
  background: #1a92cd;
  height: 25vh;

}
.cta-box > ul {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  justify-content: center;
  align-items: center;
}

.cta-box > ul > li {
  border-color:  #1a92cd;
  background: #1a92cd;

}


.fl-heading {
  font-family: Montserrat, sans-serif;
  font-weight: 600;
  font-size: 24px;
  text-align: left;
}

</style>
