<template>
<CCarousel controls indicators  class="pt-5">
  <CCarouselItem>
    <img class="d-block w-100 h-80 " src="/images/school2.jpeg" alt="slide 1"/>
    <CCarouselCaption class="d-none d-md-block text-dark" >
    <div id="example1" class="bg-dark" >
 <h5 class="text-white"> High Gate Academy of Excellency</h5>
      <p class="text-white">Some representative placeholder content for the first slide.</p>
</div>
    </CCarouselCaption>


  </CCarouselItem>
    <CCarouselItem>
    <img class="d-block  w-100  h-80 " src="/images/school3.jpeg" alt="slide 3"/>
  </CCarouselItem>

    <CCarouselItem>
    <img class="d-block  w-100  h-80 " src="/images/school1.jpeg" alt="slide 5"/>
  </CCarouselItem>
</CCarousel>

</template>
<style>
#example1 {
  border: 2px solid dark;
  padding: 10px;
  border-radius: 15px 50px 30px 5px;
  opacity:0.7;
  width: 500px;
  height: 100px;
  top: 0;
  left: 0;
  animation: 3s ease-in 1s infinite reverse both running slidein;


}

#example2 {
  border: 2px solid red;
  padding: 10px;
  border-radius: 50px 20px;
}

</style>
