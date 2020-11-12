<template>
  <div class="full-page">
    <MFooter></MFooter>
    <div class="chart-section" id="chart-section">
      <h2 class="h2-big-red">MRQ PRICE CHART</h2>
      <div class="chart">
        <div id="chart-token">
          <canvas id="myChartToken" height="100%" width="100%" ref="canvas"></canvas>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import { Line } from 'vue-chartjs'
  import MFooter from '~/components/MFooter.vue';

  export default {
    components: {
      MFooter
    },
    extends: Line,
    data() {
      return {

      }
    },
    mounted () {
      this.renderChart({
        labels: ['Jan 1', 'Jan 8', 'Jan 15', 'Jan 22', 'Jan 29', 'Jan 1', 'Jan 1'],
        datasets: [
          {
            label: 'Data One',
            backgroundColor: 'rgba(16, 16, 16, 0)',
            borderColor: '#EF5845',
            data: [50, 53, 55, 59, 51, 50, 56],
            pointRadius: 8,
            lineTension: 0,
            fill: true,
            pointBackgroundColor: '#EF5845'
          }
        ]
      }, {
        legend: {
          display: false
        },
          responsive: true,
          maintainAspectRatio: false
        });
    },
  }
</script>

<style lang="scss" scoped>

  .full-page {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .chart-section {
    padding-bottom: 100px;
    width: 90%;
    max-width: 1200px;
    height: auto;
  }

  .chart {
    background: linear-gradient(210.55deg, #ECECEC 19.14%, #ECECEC 154.68%);
    box-shadow: -18.5318px -18.5318px 46.3296px rgba(255, 255, 255, 0.8), 4.63296px 4.63296px 34.7472px rgba(110, 178, 193, 0.35), inset -9.26592px -6.94944px 92.6592px rgba(255, 255, 255, 0.18);
    border-radius: 27.7978px;
    padding: 40px;
    box-sizing: border-box;
    margin: auto;
  }
  #chart-token {
    width: 100%;
    height: 500px;
    canvas {
      width: 100% !important;
    }
  }

  .h2-big-red {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 148px;
    line-height: 1.3;
    color: #EF5845;
    margin: 60px auto;
    text-align: center;
  }

  @media (max-width: 1366px) {
    .h2-big-red {
      font-size: 100px;
    }
  }

  @media (max-width: 990px) {
    .h2-big-red {
      font-size: 70px;
    }

    #chart-token {
      height: 420px;
    }
  }

  @media (max-width: 460px) {
    .h2-big-red {
      font-size: 35px;
    }

    #chart-token {
      height: 270px;
    }

    .chart {
      padding: 15px;
    }
  }
</style>
