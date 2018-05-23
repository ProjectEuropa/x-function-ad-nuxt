<template>
    <div id="systems">
        <div class="container">
            <div class="section">
                <div class="row">
                    <div class="col center l12 video-top">
                        <div class="icon-block">
                            <div class="video-zone valign-wrapper">
                                <video src="~/assets/video/x-function-system.mp4" autoplay="" muted="muted"></video>
                                <div class="video-description col s12">
                                    <h2 class="center brown-text"><i class="material-icons">flash_on</i></h2>
                                    <h5 class="center description-title">自由自在のカスタマイズ</h5>
                                    <p class="light description-font" style="">ハードウェアとソフトウェアを自由自在に設計可能。<br>
                                    様々な特徴を持った武装を組み合わせ、ハードウェアだけでも無限の組み合わせが存在。<br>
                                    最大の特徴はソフトウェア構築。パズル感覚でプログラミングしながら自在に機体の動作が構築可能。</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="col center l12">
                        <div class="icon-block">
                            <div class="video-zone valign-wrapper">
                                <video src="~/assets/video/x-function-battle.mp4" class="video-play" autoplay="" muted="muted"></video>
                                <div class="video-description col s12">
                                    <h2 class="center brown-text"><i class="material-icons">settings</i></h2>
                                    <h5 class="center description-title">高速バトル</h5>
                                    <p class="light description-font">プログラミングによる自動操作で高速バトルを実現。<br>
                                    手動では再現できない圧倒的なスピード感によるバトルを体感せよ。
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>

<script>
</script>



<style lang="scss" scoped>
.video-top {
  margin-bottom: 40px;
}
.material-icons {
  font-size: 1em;
}
#systems {
  color: #ffffff;
  background-color: #1b2838;
  .video-zone {
    display: flex;
    justify-content: space-evenly;
    .description-title {
      font-size: 2em;
    }
    .description-font {
      font-size: 1.1em;
    }
  }
}

@media (max-width: 768px) {
  #systems {
    .video-zone {
      display: block;
      .description-title {
        font-size: 1.5em;
      }
    }
  }
}
</style>
