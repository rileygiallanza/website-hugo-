---
title: Portraits

design:
  columns: "1"
---
  <html>
  <div class="gallery">
  <figure class="gallery_item">
  <img src="/portraits/image1.jpg" class="gallery_img alt="Image 1">
  </figure>
  <figure class="gallery_item">
    <img src="/portraits/image17.jpg" class="gallery_img alt="Image 2">
  </figure><figure class="gallery_item">
  <img src="/portraits/image3.jpg" class="gallery_img alt="Image 3">
  </figure><figure class="gallery_item gallery_item--4">
    <img src="/portraits/image4.jpg" class="gallery_img alt="Image 4">
  </figure><figure class="gallery_item gallery_item--5">
  <img src="/portraits/image5.jpg" class="gallery_img alt="Image 5">
  </figure><figure class="gallery_item gallery_item--6">
    <img src="/portraits/image6.jpg" class="gallery_img alt="Image 6">
  </figure><figure class="gallery_item gallery_item--7">
  <img src="/portraits/image7.jpg" class="gallery_img alt="Image 7">
  </figure><figure class="gallery_item gallery_item--8">
    <img src="/portraits/image8.jpg" class="gallery_img alt="Image 8">
  </figure><figure class="gallery_item gallery_item--9">
  <img src="/portraits/image9.jpg" class="gallery_img alt="Image 9">
  </figure><figure class="gallery_item gallery_item--10">
    <img src="/portraits/image10.jpg" class="gallery_img alt="Image 10">
  </figure><figure class="gallery_item gallery_item--11">
  <img src="/portraits/image11.jpg" class="gallery_img alt="Image 11">
  </figure><figure class="gallery_item gallery_item--12">
    <img src="/portraits/image12.jpg" class="gallery_img alt="Image 12">
  </figure><figure class="gallery_item gallery_item--13">
  <img src="/portraits/image13.jpg" class="gallery_img alt="Image 13">
  </figure><figure class="gallery_item gallery_item--14">
    <img src="/portraits/image14.jpg" class="gallery_img alt="Image 14">
  </figure><figure class="gallery_item gallery_item--15">
  <img src="/portraits/image15.jpg" class="gallery_img alt="Image 15">
  </figure><figure class="gallery_item gallery_item--16">
    <img src="/portraits/image16.jpg" class="gallery_img alt="Image 16">
  </figure><figure class="gallery_item gallery_item--17">
  <img src="/portraits/image2.jpg" class="gallery_img alt="Image 17">
  </figure>
</div>

<style>

.gallery {
  display: grid;
  grid-template-columns: repeat(3, 250px);
  grid-auto-rows: auto;
  grid-gap: 0rem;
  
}

.gallery_img {
  height: 300px;
  background: transparent;
  border: 0;
  box-shadow: 0 20px 40px -14px rgba(0, 0, 0, 0.25);
  display: flex;
  flex-direction: column;
  overflow: hidden;
}
