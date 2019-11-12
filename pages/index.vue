<template>
  <div>
    <!-- start -->
    <div class="hero">
      <div class="hero-header"> 
        <h1>bay area CAR INSURANCE</h1>
        <!-- background photo credit: https://www.twenty20.com/photos/f221bd8f-d1ec-4f61-bba7-b2e5d797ff3e/?utm_t20_channel=bl -->
      </div>
    </div> 
    <!-- end -->
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss" scoped>
.hero {
display: grid;
grid-template-columns: repeat(5, 1fr);
grid-template-rows: repeat(5, 1fr);
grid-column-gap: 0px;
grid-row-gap: 0px;
align-items: stretch;
}
.hero {
  background: center / contain no-repeat url('~assets/images/road-trip-to-nowhere_t20_oow6yx.jpg');
  background-repeat: no-repeat;
  box-sizing: border-box;
  width: 100%;
  height: 87vh; // Always 100% of the viewport's height
  padding: 20px;
  display: grid;
  grid-template-rows: 1fr 1fr 1fr 1fr 1fr; // 5 rows
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr; // 5 columns
  grid-gap: 5px; // 5x5 works well for centering
}
.hero-header { 
  grid-area: 3 / 2 / 4 / 5; 
  color: #ffffff;
  border: 0;
  margin: 0;
  padding: 0;
  font-family: Montserrat, sans-serif;
  font-weight: 500;
  font-size: 50px;
  text-align: center;
}


</style>
