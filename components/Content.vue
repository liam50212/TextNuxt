<template>
  <main>
    <section>
      <div class="container-fuild">
        <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4">
          <div v-for="(post, index) in posts" :key="index" class="col mb-5">
            <div style="position: relative;">
              <img class="main-img" :src="post.img">
              <div class="video-thumbnail-overlay-bottom-group">
                <div class="ytm-thumbnail-overlay-time-status-renderer" data-style="DEFAULT">{{post.time}}</div>
              </div>
            </div>
            <div class="img-title d-flex mt-2">
              <img class="style-scope yt-img-shadow mt-2 mr-2" alt="" :src="post.icon">
              <h5>{{ post.title }}</h5>
              <a href="#">
                <svg viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false"
                  class="style-scope yt-icon" style="pointer-events: none; display: block; width: 30px; height: 30px;">
                  <g class="style-scope yt-icon">
                    <path
                      d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"
                      class="style-scope yt-icon"></path>
                  </g>
                </svg>
              </a>
            </div>
            <div class="img-date mb-5 mt-2 text-center">{{ post.date }}</div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
  export default {
    data() {
      return {
        posts: [
          {
            title: '正妹人妻在公婆面前要求老公刪掉網美的IG，結果公公出現老司機的反應 (中文字幕)',
            date: '2 小時前 40 秒 觀看次數：74,283次',
            img: 'https://i.ytimg.com/vi/8iYYzbiNukQ/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLB0Me-RXDUjjYSyHnhhzfFKtEfEeg',
            time: '09:39',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLSqSm1JsLlsmODvhfJkGIVBpVQaTVVonr-YAgeo=s68-c-k-c0x00ffffff-no-rj',
          },
          {
            title: '【前端尬聊 EP1】平常前端工作都在幹嘛，如何增加效率更有生產力？ | 布魯斯前端',
            date: '5 個月前 1 小時 50 分鐘 觀看次數：3,038次',
            img: 'https://i.ytimg.com/vi/p3CK74T9GHQ/hq720.jpg?sqp=-oaymwEcCK4FEIIDSEbyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLB5l2cCnA5XeNmKvIXRJCG18TM3lAg',
            time: '08:39',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLQ_XCcQ3OvhEZ8-mHbVnYbNtJ-89d2e93EoUwAR=s68-c-k-c0x00ffffff-no-rj',
          },
          {
            title: '【webpack4 #26】- Vendor 與 Entry',
            date: '5 個月前 6 分鐘 18 秒 觀看次數：181次',
            img: 'https://i.ytimg.com/vi/Dp1iYNlmijA/hq720.jpg?sqp=-oaymwEXCNAFEJQDSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLDF5FjBAdo8CYZOBHU_6pBVu5Uq2Q',
            time: '28:00',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLRJBkpJ1KE2up2XNO-1vc841IHw5YFoM8dkUXwxBA=s68-c-k-c0x00ffffff-no-rj',
          },
          {
            title: '卡卡遇上师父布布，battle场面瞬间“炸裂” 优酷综艺 YOUKU SHOW',
            date: '觀看次數：28,711次 2021年8月15日',
            img: 'https://i.ytimg.com/vi/GM26pUBLBDc/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&amp;rs=AOn4CLBlBKU__rSxaesNjUEJeMjsDTBzFw',
            time: '26:15',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLRvI_DeVpXy4fWUDrMqb5sASI2TkfFbUn43Q1or=s68-c-k-c0x00ffffff-no-rj',
          },
          {
            title: '《大嘻哈時代》SheATH「辣太辣太辣」｜選手特輯',
            date: '6 小時前 14 秒 觀看次數：89,243次',
            img: 'https://i.ytimg.com/vi/3QMGAwjkOZw/hq720.jpg?sqp=-oaymwEcCK4FEIIDSEbyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCzpPEHzlXZVQr_OTyZPYR1PaluVw',
            time: '55:39',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLRrNoIKF7EsfQwCM8r3mIFDSf2cP6sM04F2ZcRp8A=s68-c-k-c0x00ffffff-no-rj',
          },
          {
            title: 'Alex Skrindo, Severin & Like Lions - Heart [NCS Release]',
            date: '10 小時前 25 秒 觀看次數：14,653次',
            img: 'https://i.ytimg.com/vi/Ueg-SUFGb4M/hq720.jpg?sqp=-oaymwEcCK4FEIIDSEbyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDQxcRm7OT2SZKwEyZMtf51_b82Sw',
            time: '25:17',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLQPUsOFTh7JnkDWMwnS737uhnk7EsENZkBXnZ5rMA=s68-c-k-c0x00ffffff-no-rj',
          },
          {
            title: 'SOMI(전소미)- DUMB DUMB @인기가요 inkigayo 20210815',
            date: '5 小時前 16 秒 觀看次數：55,273次',
            img: 'https://i.ytimg.com/vi/8FGGOAJVV80/hq720.jpg?sqp=-oaymwEcCK4FEIIDSEbyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDsKDU69CjVWXrgmy7Px_O7yT-3SQ',
            time: '17:25',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLT5Mih3kHCv2pvZCbZ1T-yyv0WuUZF2EsATod563A=s68-c-k-c0x00ffffff-no-rj',
          },
          {
            title: '【歌詞版】搶先版熱門歌單 Chinese Rap Songs',
            date: '9 小時前 30 秒 觀看次數：47,283次',
            img: 'https://i.ytimg.com/vi/W_XQhFGsmzQ/hq720.jpg?sqp=-oaymwEcCK4FEIIDSEbyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLASm29OQVIDRs6zUC4oH5XblFzIKg',
            time: '11:42',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLS8xOHu7v8pyn0onETVp7pcfINDNQ8BdjhuWl8o=s68-c-k-c0x00ffffff-no-rj',
          },
          {
            title: 'Nuxt The Next Headless Git Based CMS?',
            date: '8 小時前 45 秒 觀看次數：88,281次',
            img: 'https://i.ytimg.com/vi/KnKmSFeTUjY/hq720.jpg?sqp=-oaymwEcCK4FEIIDSEbyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLA-pznitVvEovYo9wcQVUVTXoPaQQ',
            time: '16:35',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLQJrey6zXmT2KQJ_hp4sUaEt-flBRHb98cX0D3r=s68-c-k-c0x00ffffff-no-rj',
          },
          {
            title: 'TWICE子瑜太內向受Jessi「特別關照」 Mina & 彩瑛雙向愛意外曝光｜鏡週刊 鏡娛樂即時',
            date: '9 小時前 40 秒 觀看次數：79,223次',
            img: 'https://i.ytimg.com/vi/cG8KD-aQev0/hq720.jpg?sqp=-oaymwEcCK4FEIIDSEbyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLB4JZtOGUj-O85a7JjkmmDlYAzUjQ',
            time: '07:14',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLTBolQ34Qu4fcowPnLaCw3piF1p-95G9UPx0SRg=s68-c-k-c0x00ffffff-no-rj',
          },
          {
            title: 'People say I’m the best sniper, and this is why | CODM Montage',
            date: '3 小時前 40 秒 觀看次數：99,283次',
            img: 'https://i.ytimg.com/vi/iPkit2Mr8FE/hq720.jpg?sqp=-oaymwEcCK4FEIIDSEbyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLD1Jw9GofLU6QG7UgW-8uJS9U5F-Q',
            time: '13:45',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLSV90zm99yyHkm_mgKbZP84ltjSo8mRDij9yXNilQ=s68-c-k-c0x00ffffff-no-rj',
          },
          {
            title: '【前端速成】Webpack5 快速入門｜布魯斯前端',
            date: '5 小時前 55 秒 觀看次數：76,283次',
            img: 'https://i.ytimg.com/vi/uP6KTupfyIw/hq720.jpg?sqp=-oaymwEcCK4FEIIDSEbyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAAZnKdP-QNxQasNOk1yv6onNm74g',
            time: '20:11',
            icon: 'https://yt3.ggpht.com/ytc/AKedOLQ_XCcQ3OvhEZ8-mHbVnYbNtJ-89d2e93EoUwAR=s68-c-k-c0x00ffffff-no-rj',
          },
        ],
      }
    }
  }
</script>

<style>
  main {
    width: 100%;
    position: absolute;
    top: 15%;
  }

  .main-img {
    width: 100%;
    height: auto;
    display: block;
    margin: auto;
    position: relative;
  }

  .row {
    margin: 0;
  }

  .ytm-thumbnail-overlay-time-status-renderer {
    position: absolute;
    right: 30px;
    bottom: 0;
    margin: 5px;
    padding: 1px 4px;
    border-radius: 2px;
    font-size: 1.2rem;
    color: #ffffff;
    background-color: black;
  }

  .yt-img-shadow {
    width: 50px;
    height: 50px;
    border-radius: 30px;
  }

  .img-title {
    max-width: 380px;
    margin: auto;
  }

  .img-date {
    max-height: 22px;
  }

  h5 {
    max-height: 90px;
    min-height: 90px;
  }

  @media (max-width:1800px) {
    .ytm-thumbnail-overlay-time-status-renderer {
      right: 20px;
    }
  }

  @media (max-width:1700px) {
    .ytm-thumbnail-overlay-time-status-renderer {
      right: 10px;
    }
  }

  @media (max-width:1600px) {
    .ytm-thumbnail-overlay-time-status-renderer {
      right: 0;
    }
  }

  @media (max-width:1500px) {
    .ytm-thumbnail-overlay-time-status-renderer {
      right: -25px;
    }
  }

  @media (max-width:1440px) {
    .main-img {
      width: 300px;
    }

    .col {
      max-width: 300px;
      min-width: 300px;
      margin: auto;
    }

    .img-title {
      max-width: 300px;
      min-width: 300px;
    }

    h5,
    .img-date {
      font-size: 15px;
    }

    h5 {
      line-height: 30px;
    }
  }

  @media (max-width:1100px) {
    .main-img {
      width: 280px;
    }

    .col {
      max-width: 280px;
      min-width: 280px;
      margin: auto;
    }

    .img-title {
      max-width: 280px;
      min-width: 280px;
    }

    h5,
    .img-date {
      font-size: 15px;
    }

    h5 {
      line-height: 25px;
    }
  }

  @media (max-width:765px) {
    .main-img {
      width: 340px;
    }

    .row {
      margin-right: 40px;
    }

    .col {
      max-width: 340px;
      min-width: 340px;
      margin-bottom: 30px;
    }

    .img-title {
      max-width: 340px;
      min-width: 340px;
    }

    h5,
    .img-date {
      font-size: 18px;
    }

    h5 {
      line-height: 25px;
    }
  }

  @media (max-width:680px) {
    .main-img {
      width: 620px;
    }

    .col {
      max-width: 620px;
      min-width: 620px;
    }

    .img-title {
      max-width: 620px;
      justify-content: space-between;
    }

    .yt-img-shadow {
      width: 100px;
      height: 100px;
    }

    h5,
    .img-date {
      font-size: 30px;
    }

    h5 {
      line-height: 50px;
      max-height: 150px;
      min-height: 150px;
    }
  }

  @media (max-width:375px) {
    .main-img {
      width: 100%;
    }

    .col {
      max-width: 100%;
      min-width: 100%;
    }

    .row {
      margin-right: 10px;
    }

    .img-title {
      max-width: 100%;
      justify-content: space-between;
    }

    .yt-img-shadow {
      width: 100px;
      height: 100px;
    }

    h5,
    .img-date {
      font-size: 20px;
    }

    h5 {
      line-height: 30px;
    }

    .ytm-thumbnail-overlay-time-status-renderer {
      right: -3px;
    }
  }
</style>