---
title: Portraits

design:
  columns: "1"
---
<div class="container">
  <div class="tile">
  <img src="/portraits/image.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image5.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image2.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image8.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image4.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image3.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image17.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image15.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image10.jpg" alt="">
  </div>
   <div class="tile">
  <img src="/portraits/image9.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image1.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image11.jpg" alt="">
  </div>
   <div class="tile">
  <img src="/portraits/image12.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image13.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image14.jpg" alt="">
  </div>
   <div class="tile">
  <img src="/portraits/image7.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image16.jpg" alt="">
  </div>
  <div class="tile">
  <img src="/portraits/image6.jpg" alt="">
  </div>
</div>

<style>
.container{
    display: grid;
    grid-template-columns: repeat(6, 1fr);
    grid-gap: 1rem;
    width: 1700px;
  }
.tile img{
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.tile:nth-child(1){
  grid-column: span 2;
  grid-row: span 3;
}
.tile:nth-child(2){
  grid-column: span 2;
  grid-row: span 2;
}
.tile:nth-child(5){
  grid-column: span 2;
  grid-row: span 3;
}
.tile:nth-child(6){
  grid-column: span 2;
  grid-row: span 2
}
.tile:nth-child(9){
  grid-column: span 2;
  grid-row: span 3;
}
.tile:nth-child(10){
  grid-column: span 2;
  grid-row: span 2;
}
.tile:nth-child(13){
  grid-column: span 2;
  grid-row: span 3;
}
.tile:nth-child(14){
  grid-column: span 2;
  grid-row: span 2
}
.tile:nth-child(17){
  grid-column: span 3;
  grid-row: span 2;
}
.tile:nth-child(18){
  grid-column: span 3;
  grid-row: span 2;
}