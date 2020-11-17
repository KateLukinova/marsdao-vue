<template>
  <div class="header">
    <div class="container header-container">
      <a href="#" class="logo">
        <svg width="344" height="103" viewBox="0 0 344 103" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
          <rect width="344" height="103" fill="url(#pattern0)"/>
          <defs>
            <pattern id="pattern0" patternContentUnits="objectBoundingBox" width="1" height="1">
              <use xlink:href="#image0" transform="scale(0.00290698 0.00970874)"/>
            </pattern>
            <image id="image0" width="344" height="103" xlink:href="data:image/png;base64,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"/>
          </defs>
        </svg>
      </a>
      <nav class="my-navbar">
        <a href="#" class="nav-toggler" @click="isMenuOpened = !isMenuOpened">
                    <span class="navbar-toggler-icon">
                        <svg width="22" height="14" viewBox="0 0 22 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M0 7H22" stroke="white" stroke-width="2" stroke-linejoin="round"/>
                            <path d="M0 1H22" stroke="white" stroke-width="2" stroke-linejoin="round"/>
                            <path d="M0 13H22" stroke="white" stroke-width="2" stroke-linejoin="round"/>
                        </svg>
                    </span>
        </a>
        <div class="my-navbar-collapse" v-bind:class="{ show: isMenuOpened }">
          <a href="#" class="menu-close" @click="isMenuOpened = !isMenuOpened">
            <svg width="19" height="19" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M1 1L18 18" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M18 1L0.999999 18" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </a>
          <ul class="ul-nav">
            <li class="nav-item">
              <a class="nav-link" href="#">Docs</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Forum</a>
            </li>
            <li class="nav-item">
              <a href="#chart-section" class="nav-link" v-smooth-scroll @click="isMenuOpened = !isMenuOpened">CHARTS</a>
            </li>
            <li class="nav-item">
              <a href="#about-section" class="nav-link" v-smooth-scroll @click="isMenuOpened = !isMenuOpened">ABOUT</a>
            </li>
            <li class="nav-item">
              <a class="nav-link login-button" href="#">
                <svg xmlns="http://www.w3.org/2000/svg" width="25.072" height="23.485" viewBox="0 0 25.072 23.485">
                  <g id="Wallet" transform="translate(-4 -5)">
                    <path id="Path_1" data-name="Path 1" d="M4,8.914a.933.933,0,0,1,.933-.933H28.14a.933.933,0,0,1,.933.933V25.862a.933.933,0,0,1-.933.933H4.933A.933.933,0,0,1,4,25.862Zm1.865.933V24.93H27.207V9.847Z" transform="translate(0 1.691)" fill="#fff" fill-rule="evenodd"/>
                    <path id="Path_2" data-name="Path 2" d="M13.033,15.314A4.014,4.014,0,0,1,17.047,11.3h5.585a.933.933,0,0,1,.933.933V18.4a.933.933,0,0,1-.933.933H17.047A4.014,4.014,0,0,1,13.033,15.314Zm4.014-2.149a2.149,2.149,0,0,0,0,4.3H21.7v-4.3Z" transform="translate(5.122 3.572)" fill="#fff" fill-rule="evenodd"/>
                    <path id="Path_3" data-name="Path 3" d="M16.262,15.534a1.22,1.22,0,1,0-1.22-1.22A1.22,1.22,0,0,0,16.262,15.534Z" transform="translate(6.261 4.589)" fill="#fff" fill-rule="evenodd"/>
                    <path id="Path_4" data-name="Path 4" d="M21.915,7.17c.123-.027.262-.061.391-.094l.079-.02c.168-.042.335-.082.505-.116a2.736,2.736,0,0,1,.876-.061.517.517,0,0,1,.38.192,1.809,1.809,0,0,1,.228,1.075.933.933,0,0,0,1.865,0,3.579,3.579,0,0,0-.6-2.2,2.372,2.372,0,0,0-1.6-.917,4.54,4.54,0,0,0-1.5.077c-.218.043-.422.093-.6.136l-.092.023c-.137.034-.241.06-.332.079l-.039.009L4.782,9.627a.933.933,0,0,0,.462,1.807Z" transform="translate(0.045 0)" fill="#fff" fill-rule="evenodd"/>
                  </g>
                </svg>
                CONNECT
              </a>
            </li>
          </ul>
        </div>
      </nav>
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
  .logo {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    width: 17.5vw;
    min-width: 180px;
    svg {
      width: 100%;
    }
  }

  .menu-close {
    display: none;
  }

  .header {
    position: absolute;
    top: 0;
    left: 0;
    background-color: transparent;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    z-index: 11;
    -webkit-transition: all 0.5s ease;
    -o-transition: all 0.5s ease;
    transition: all 0.5s ease;
    margin-top: 33px;
    width: 100%;
  }
  .header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  nav {
    .nav-link {
      font-family: 'Bebas Neue', cursive;
      font-style: normal;
      font-size: 37px;
      line-height: 1.2;
      color: #FFFFFF;
      margin-left: 30px;
      display: -webkit-box;
      display: -ms-flexbox;
      display: flex;
      -webkit-box-pack: center;
      -ms-flex-pack: center;
      justify-content: center;
      -webkit-box-align: center;
      -ms-flex-align: center;
      align-items: center;
      text-transform: uppercase;
      position: relative;
      transition: all 0.5s ease;
      &:after {
        position: absolute;
        content: '';
        width: 0;
        height: 5px;
        background-color: white;
        bottom: 0;
        left: 0;
        transition: all 0.5s ease;
      }
      &:hover:after {
        width: 100%;
      }
      img {
        margin-left: 11px;
      }
      &.login-button {
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #EF5845;
        min-width: 200px;
        box-shadow: 5px 5px 12px #00000029;
        border-radius: 40px;
        min-height: 55px;
        &:hover {
          transform: scale(1.1);
          &:after {
            display: none;
          }
        }

        svg {
          margin-right: 14px;
        }
      }
    }
  }
  .ul-nav {
    display: flex;
    align-items: center;
    justify-content: flex-end;
  }

  .nav-toggler {
    display: none;
  }

  @media (max-width: 1366px) {
    nav .nav-link {
      font-size: 26px;
      margin-left: 18px;
      line-height: 1;
      &.login-button {
        min-width: 150px;
        img {
          margin-right: 16px;
        }
      }
    }
  }

  @media (max-width: 768px) {
    .nav-toggler {
      display: block;
    }

    .my-navbar-collapse {
      transform: translateX(100%);
      position: fixed;
      top: 0;
      right: 0;
      width: 100vw;
      background-color: #1b1e21;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      transition: all 0.5s ease;
      &.show {
        transform: translateX(0);
      }
    }

    .ul-nav {
      display: flex;
      flex-direction: column;
    }

    .menu-close {
      display: block;
      position: absolute;
      top: 50px;
      right: 50px;
    }

    .header {
      margin-top: 0;
    }

    nav .nav-link {
      margin-left: 0;
      margin-bottom: 25px;
    }
  }

</style>
