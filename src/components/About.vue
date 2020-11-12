<template>
  <div id="about-section">
    <div class="about-page">
      <div class="content-row">
        <div class="content-img">
          <img src="../assets/img/dash.jpg" alt="">
        </div>
        <div class="text-block">
          <h3>ABOUT</h3>
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
          </p>
        </div>
      </div>
      <div class="content-row">
        <p class="pp">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
        <div class="media-box">
          <a href="#" class="media-item tm">
            <img src="../assets/img/tm.png" alt="">
          </a>
          <a href="#" class="media-item fb">
            <img src="../assets/img/fb.png" alt="">
          </a>
          <a href="#" class="media-item hb">
            <img src="../assets/img/hb.png" alt="">
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  data() {
    return {

    };
  }
};
</script>

<style lang="scss" scoped>

  .fullpage {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .about-page {
    width: 90%;
    max-width: 1690px;
    background-color: white;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: auto;
    min-height: calc(100vh - 140px);
    margin: auto;
    margin-top: 50px;
    padding: 30px 40px;
    &:before {
      position: absolute;
      content: '';
      top: -35px;
      right: -35px;
      width: 70%;
      height: 50%;
      background-color: #EF5845;
      z-index: -1;
    }
    &:after {
      position: absolute;
      content: '';
      bottom: -35px;
      left: -35px;
      width: 70%;
      height: 50%;
      background-color: #EF5845;
      z-index: -1;
    }
  }

  .content-row {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
  }

  .content-img {
    width: 48%;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    overflow: hidden;
    object-fit: cover;
    transform: translateX(-75px);
    margin-top: 60px;
    img {
      width: auto;
      min-width: 100%;
      height: auto;
      object-fit: cover;
    }
  }

  .text-block {
    width: 48%;
    h3 {
      color: #424242;
      font-family: 'Bebas Neue', sans-serif;
      font-size: 70px;
      line-height: 1.2;
      margin-bottom: 80px;
    }
  }

  .media-box {
    width: 252px;
    height: 252px;
    border-radius: 100%;
    border: 1px dashed #909399;
    position: relative;
    margin-top: 35px;
    margin-right: 35px;
    .media-item {
      position: absolute;
      &.tm {
        top: -10px;
        left: 0;
        transform: translateX(-25px);
      }
      &.fb {
        top: 50%;
        right: -40px;
        transform: translateY(-50%);
      }

      &.hb {
        left: 0;
        bottom: 0;
      }
    }
  }
  .pp {
    width: calc(100% - 380px);
    margin-top: 5vw;
    max-width: 970px;
  }
  .anim {
    animation: Circulate 7s infinite linear;
  }

  @keyframes Circulate {
    /* notice the only differences are the first rotate() property */

    from {
      left: 150px;
      top: 145px;

      transform:
        /* starting position offset */
        rotate(20deg)
          /* half circle size + .5px(for precision) */
        translate(-150.5px)
          /* how much the icon should rotate as it goes around */
        rotate(-40deg);
    }
    to {
      left: 150px;
      top: 145px;

      transform:
        /* full circle rotation: 360 + 20 offset */
        rotate(380deg)
          /* half circle size + .5px(for precision) */
        translate(-150.5px)
          /* how much the icon should rotate as it goes around */
        rotate(-40deg);
    }
  }

  @media (max-width: 990px) {
    .content-row {
      flex-direction: column-reverse;
      justify-content: flex-start;
      align-items: center;
    }

    .text-block {
      width: 100%;
      h3 {
        text-align: center;
        margin-bottom: 25px;
      }
      p {
        text-align: center;
      }
    }

    .content-img {
      width: 100%;
      transform: translate(0);
    }

    .pp {
      width: 100%;
      text-align: center;
    }

    .media-box {
      margin: 0;
      margin-top: 70px;
    }
  }

</style>
