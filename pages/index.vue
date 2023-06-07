<template>
  <div class="">
    <Navbar />
    <div class="hero">
      <img src="~/assets/images/Hero_img.png" class="imghero" alt="">
      <img src="~/assets/images/Background.png" class="imgbg" alt="">
      <div class="contenthero px-4">
        <h3>Discover <br> Your Wonder</h3>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
        magna aliqua.
        Ut enim ad minim veniam.
      </div>
      <a href="#goto">
        <img src="~/assets/images/Scroll.png" class="imgscroll" alt="">
      </a>

    </div>

    <div class="section2 py-2">
      <div class="container px-3">
        <h3 id="goto">Who we are</h3>
        <div class="titlesection">Technology Company</div>
        <div class="descrition">
          Sed ut perspiciatis unde omnis iste natus sit voluptatem accusantium doloremque laudantium, totam rem aperiam,
          eaque
          ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
        </div>

        <div class="row mt-4 mb-3">
          <div class="col-4">
            <div class="mt-1">
              <span class="page">01</span><span class="garing">/</span><span class="total">03</span>
            </div>
          </div>
          <div class="col-8 text-right">
            <b-button-group>
              <button class="button-pref"><img src="~/assets/images/ArrowPref.png" alt=""></button>
              <button class="button-next"><img src="~/assets/images/ArrowNext.png" alt=""></button>
            </b-button-group>
          </div>
        </div>
      </div>

    </div>

    <div class="section3">
      <h3 class="text-center mt-3">Our Core Values</h3>
      <div class="description">
        Ridiculus laoreet libero pretium et, sit vel elementum convallis fames. Sit suspendisse etiam eget egestas.
        Aliquet odio et lectus etiam sit. <br>

        In mauris rutrum ac ut volutpat, ornare nibh diam. Montes, vitae, nec amet enim.
      </div>
      <div class="title">
        Dedication
      </div>
      <div class="description">
        Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat.
      </div>
      <div class="title">
        Intellectual Honesty
      </div>
      <div class="description">
        Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias conse.
      </div>
      <div class="title">
        Curiosity
      </div>
      <div class="description">
        At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque.
      </div>

      <div class="text-right">
        <img src="~/assets/images/Illustration.png" class="imgillu" alt="">
      </div>
    </div>

    <!-- Carousel -->
    <div class="section4 py-3">
      <div class="card-item mx-2">
        <div class="mx-3">
          <h3 class="pt-3">OUR SPECIALITY</h3>
          <div class="description my-2">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis euismod libero vel leo auctor, in venenatis
            nulla
            consequat. Sed commodo nunc sit amet congue aliquam.
          </div>
          <div class="img-content">
            <img src="~/assets/images/carouselPref.png" class="img-pref" alt="">
            <img src="~/assets/images/CarouselActive.png" class="img-active" alt="">
            <div class="description text-center">Seep Improvement</div>
            <img src="~/assets/images/carouselNext.png" class="img-next" alt="">
          </div>
          <div class="description-item my-2 text-center">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis euismod libero vel leo auctor, in venenatis
            nulla
            consequat. Sed commodo nunc sit amet congue aliquam.
          </div>
          <div class="navigation pb-4">
            <div class="row">
              <div class="col-4">
                <img src="~/assets/images/ArrowPrefCarousel.png" class="curpoint" alt="">
              </div>
              <div class="col-4 text-center">
                <div class="flexdis">
                  <div class="img-position active">&nbsp;</div>
                  <div class="img-position">&nbsp;</div>
                  <div class="img-position">&nbsp;</div>
                  <div class="img-position">&nbsp;</div>
                  <div class="img-position">&nbsp;</div>
                </div>
              </div>
              <div class="col-4 text-right">
                <img src="~/assets/images/ArrowNextCarousel.png" class="curpoint" alt="">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="footer">
      <img src="~/assets/images/Frame_footer.png" class="footer-logo mt-2 ml-3" alt="">
      <div class="cont">
        <div class="address-content mt-4 mx-2">
          <div class="text-center">
            <select name="dep" id="dep" class="footer-select">
              <option value="1">TECHNOLOGY DEPARTMENT</option>
            </select>

          </div>

          <div class="address mx-3 mt-3 pb-4">
            Jl. Lembong No 8 <br>
            Kel. Braga Kec. Sumur <br>
            Bandung, Kota <br>
            Bandung, Jawa Barat
          </div>
        </div>
        <div class="menus mx-2 mt-2">
          Who We Are
        </div>
        <div class="menus mx-2 mt-2">
          Our Values
        </div>
        <div class="menus mx-2 mt-2">
          The Perks
        </div>
      </div>

      <img src="~/assets/images/Footerbg.png" class="footerbg" alt="">
    </div>


  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600&family=Rubik:wght@400;500&display=swap');

html {
  scroll-behavior: smooth;
}

* {
  font-family: 'Rubik';
  font-style: normal;
  font-weight: 400;
  font-size: 36px;
  line-height: 34px;
}

.hero {
  height: 90vh;
  position: relative;
  color: white;

  .imghero {
    position: absolute;
    top: 0px;
    left: 0px;
    width: 100vw;
    min-height: 350px;
    max-height: 500px;
    z-index: 1;
  }

  .imgbg {
    width: 100vw;
    height: 550px;
    position: absolute;
    top: 200px;
    z-index: 2;
  }

  .imgscroll {
    position: absolute;
    bottom: -30px;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 60px;
    z-index: 3;
    cursor: pointer;
  }

  .contenthero {
    position: absolute;
    top: 400px;
    width: 100vw;
    font-size: 16px;
    z-index: 4;

    h3 {
      font-size: 36px;
    }
  }
}

.section2 {

  h3 {
    font-weight: 500;
    font-size: 36px;
    color: #029FE4;
  }

  .titlesection {
    font-weight: 400;
    font-size: 18px;
    color: #000000;
  }

  .descrition {
    font-weight: 400;
    font-size: 14px;
    color: #777777;
  }

  .page {}

  .garing {
    color: #C0C0C0;
  }

  .total {
    color: #C0C0C0;
    font-size: 24px;
  }

  .button-pref {
    background: #F1F1F1;
    border: none;
    width: 60px;
    height: 60px;
  }

  .button-next {
    background: #1BA0E1;
    border: none;
    width: 60px;
    height: 60px;
  }
}

.section3 {
  background-color: #F8F8F8;
  padding-top: 20px;
  overflow: hidden;
  width: 100vw;

  h3 {
    font-weight: 500;
    font-size: 36px;
    color: #029FE4;
  }

  .description {
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: 0.01em;
    padding-left: 60px;
    padding-right: 40px;
    margin-bottom: 20px;
    color: #777777;
  }

  .title {
    font-weight: 400;
    font-size: 24px;
    line-height: 38px;
    padding-left: 60px;
  }

  .imgillu {
    width: 100vw;
    max-width: 800px;
  }
}

.section4 {
  background: #509FDD;
  width: 100vw;

  .card-item {
    background: white;
  }

  h3 {
    color: #029FE4;
    font-weight: 700;
    font-size: 24px;
    line-height: 28px;
  }

  .description {
    font-weight: 300;
    font-size: 14px;
    line-height: 24px;
    color: #303030;
  }

  .description-item {
    font-weight: 300;
    font-size: 14px;
    line-height: 24px;
    color: #A7A7A7;
  }

  .img-content {
    width: 100%;
    height: 280px;
    position: relative;
    overflow: hidden;

    .img-active{
      position: absolute;
      top: 40%;
      left: 50%;
      transform: translate(-50%, -50%);
      width:30%;
      max-width: 200px;
    }
    .description{
      position: absolute;
      transform: translate(-50%, -50%);
      bottom: 10px;
      left: 50%;
      width: 30%;
    }
    .img-pref{
      position: absolute;
      top: 150px;
      left: -30px;
      width: 30%;
      max-width: 200px;
      filter: blur(4px);
    }
    .img-next{
      position: absolute;
      top: 70px;
      right: -30px;
      width: 30%;
      max-width: 200px;
      filter: blur(4px);
    }
  }

  .curpoint:hover {
    cursor: pointer;
  }

  .flexdis {
    display: flex;
    flex-wrap: wrap;
    text-align: center;
  }

  .img-position {
    width: 25px;
    height: 25px;
    flex: 10%;
    margin: 2px;
    background-image: url('../assets/images/PageInactive.png');
    background-repeat: no-repeat;
  }

  .img-position.active {
    background-image: url('../assets/images/PageActive.png');
    background-repeat: no-repeat;
  }

}

.footer {
  width: 100vw;
  min-height: 80vh;
  background: #07477A;
  position: relative;
  overflow: hidden;

  .footer-logo {
    width: 220px;
  }

  .cont {
    position: absolute;
    top: 280px;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 90vw;
    height: fit-content;
    z-index: 2;
  }

  .address-content {
    background-color: white;

    .address {
      font-weight: 400;
      font-size: 18px;
      line-height: 21px;
      letter-spacing: 0.02em;
      color: #25A0D8;
    }

    .footer-select {
      margin-top: 20px;
      font-weight: 700;
      font-size: 14px;
      line-height: 17px;
      color: #00537C;
      text-transform: uppercase;
      height: 35px;
      width: 90%;
      border: 1px solid rgba(0, 0, 0, 0.3);
      border-radius: 4px;
    }
  }

  .menus {
    font-weight: 400;
    font-size: 16px;
    line-height: 48px;
    color: #FFFFFF;
  }

  .footerbg {
    width: 100vw;
    height: 300px;
    position: absolute;
    bottom: 0px;
    left: 0px;
    z-index: 1;
  }
}</style>
