<template>
  <div class="footer">
    <div class="soc-box">
      <a href="#" class="soc-item">
        <img src="../assets/img/tm.png" alt="">
      </a>
      <a href="#" class="soc-item">
        <img src="../assets/img/fb.png" alt="">
      </a>
      <a href="#" class="soc-item">
        <img src="../assets/img/hb.png" alt="">
      </a>
    </div>
  </div>
</template>

<script>

export default {
  data() {
    return {
      isMenuOpened: false
    }
  },
  methods: {

  },
  mounted() {

  }
};
</script>

<style lang="scss" scoped>

  .footer {
    position: absolute;
    bottom: 35px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: auto;
    z-index: 5;
  }
  .soc-box {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 170px;
    z-index: 12;
    margin-top: 80px;
    img {
      width: 35px;
    }
  }

  @media (max-width: 460px) {
    .soc-box {
      margin: 0 auto;
    }
  }

</style>
