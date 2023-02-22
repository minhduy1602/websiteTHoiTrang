<template>
  <div
    id="carouselExampleCaptions"
    class="carousel slide"
    data-bs-ride="carousel"
  >
    <div class="carousel-indicators">
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="1"
        aria-label="Slide 2"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="2"
        aria-label="Slide 3"
      ></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          src="https://theme.hstatic.net/200000182297/1000887316/14/ms_banner_img1.jpg?v=407"
          class="d-block w-100 h-100"
          alt="..."
        />
      </div>
      <div class="carousel-item">
        <img
          src="https://cdn2.yame.vn/cimg/images/cbdc9d4f-e559-0100-6904-0019cc0f8fa8.jpg"
          class="d-block w-100 h-100"
          alt="..."
        />
      </div>
      <div class="carousel-item">
        <img
          src="https://cmsv2.yame.vn/uploads/70bfcc1b-0ca6-44f5-9d64-623925564cc5/Banner_Sale_T%e1%ba%bft_(02).jpg?quality=80&w=0&h=0"
          class="d-block w-100 h-100"
          alt="..."
        />
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</template>
<style scoped>
.carousel-item {
  height: 774px;
}
</style>
