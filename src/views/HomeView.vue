<template>
   <div class="px-2 text-center">
                <img class="mb-4" src="../assets/logo.png" alt="" width="10%" height="10%">  
  <div class="py-5 text-center container">
    <div class="col-lg-6 col-md-8 mx-auto">
      <h1 class="fw-light">ยินดีต้อนรับสู้เว็บไซต์</h1>
      <p class="lead text-body-secondary">
        สินค้ายอดนิยมหรือสินค้าที่กำลังลดราคา
      </p>
    </div>
    <div class="container mt-5">
      <h1 class="text-center mt-4">สินค้ายอดนิยม</h1>
      &nbsp;
      <div class="row">
        <div class="col-md-3 mb-4">
          <div class="card">
            <img src="../assets/p1.jpg" alt="ชื่อสินค้า 1" />
            <div class="card-body text-center">
              <h5 class="card-title">ชื่อสินค้า 1</h5>
              <p class="card-text">ราคา: ฿1,000</p>
              <p class="card-text">ต้นไม้แห่งชีวิต</p>
              <a href="/productdt" class="btn btn-primary">
                <i class="fas fa-shopping-cart"></i> ข้อมูลสินค้า
              </a>
            </div>
          </div>
        </div>
        <div class="col-md-3 mb-4">
          <div class="card">
            <img
              src="../assets/p2.jpg"
              class="card-img-top"
              alt="ชื่อสินค้า 2"
            />
            <div class="card-body text-center">
              <h5 class="card-title">ชื่อสินค้า 2</h5>
              <p class="card-text">ราคา: ฿1,500</p>
              <p class="card-text">เฟอร์นิเจอร์ภายในบ้าน</p>
              <button class="btn btn-primary">
                <i class="fas fa-shopping-cart"></i> ข้อมูลสินค้า
              </button>
            </div>
          </div>
        </div>
        <div class="col-md-3 mb-4">
          <div class="card">
            <img
              src="../assets/p3.jpg"
              class="card-img-top"
              alt="ชื่อสินค้า 3"
            />
            <div class="card-body text-center">
              <h5 class="card-title">ชื่อสินค้า 3</h5>
              <p class="card-text">ราคา: ฿2,000</p>
              <p class="card-text">โต๊ะทำงาน</p>
              <button class="btn btn-primary">
                <i class="fas fa-shopping-cart"></i> ข้อมูลสินค้า
              </button>
            </div>
          </div>
        </div>
        <div class="col-md-3 mb-4">
          <div class="card">
            <img
              src="../assets/p4.jpg"
              class="card-img-top"
              alt="ชื่อสินค้า 4"
            />
            <div class="card-body text-center">
              <h5 class="card-title">ชื่อสินค้า 4</h5>
              <p class="card-text">ราคา: ฿2,500</p>
              <p class="card-text">โต๊ะทำงาน</p>
              <button class="btn btn-primary">
                <i class="fas fa-shopping-cart"></i> ข้อมูลสินค้า
              </button>
            </div>
          </div>
        </div>
        <div class="col-md-3 mb-4">
          <div class="card">
            <img
              src="../assets/p5.jpg"
              class="card-img-top"
              alt="ชื่อสินค้า 2"
            />
            <div class="card-body text-center">
              <h5 class="card-title">ชื่อสินค้า 5</h5>
              <p class="card-text">ราคา: ฿1,500</p>
              <p class="card-text">ห้องรับประทานอาหาร</p>
              <button class="btn btn-primary">
                <i class="fas fa-shopping-cart"></i> ข้อมูลสินค้า
              </button>
            </div>
          </div>
        </div>
        <div class="col-md-3 mb-4">
          <div class="card">
            <img
              src="../assets/p6.jpg"
              class="card-img-top"
              alt="ชื่อสินค้า 2"
            />
            <div class="card-body text-center">
              <h5 class="card-title">ชื่อสินค้า 6</h5>
              <p class="card-text">ราคา: ฿1,500</p>
              <p class="card-text">โต๊ะทำงาน</p>
              <button class="btn btn-primary">
                <i class="fas fa-shopping-cart"></i> ข้อมูลสินค้า
              </button>
            </div>
          </div>
        </div>
        <div class="col-md-3 mb-4">
          <div class="card">
            <img
              src="../assets/p7.jpg"
              class="card-img-top"
              alt="ชื่อสินค้า 2"
            />
            <div class="card-body text-center">
              <h5 class="card-title">ชื่อสินค้า 7</h5>
              <p class="card-text">ราคา: ฿1,500</p>
              <p class="card-text">ห้องครัว</p>
              <button class="btn btn-primary">
                <i class="fas fa-shopping-cart"></i> ข้อมูลสินค้า
              </button>
            </div>
          </div>
        </div>
        <div class="col-md-3 mb-4">
          <div class="card">
            <img
              src="../assets/p8.jpg"
              class="card-img-top"
              alt="ชื่อสินค้า 2"
            />
            <div class="card-body text-center">
              <h5 class="card-title">ชื่อสินค้า 8</h5>
              <p class="card-text">ราคา: ฿1,500</p>
              <p class="card-text">ห้องนั่งเล่น</p>
              <button class="btn btn-primary">
                <i class="fas fa-shopping-cart"></i> ข้อมูลสินค้า
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
