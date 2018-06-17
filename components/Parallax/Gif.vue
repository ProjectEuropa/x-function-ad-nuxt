<template>
    <div>
        <div id="index-banner" class="parallax-container">
            <div class="container">
                <nav class="transparent z-depth-0 ">
                    <div class="nav-wrapper">
                        <div class="row">
                            <div class="col s12">
                                <a href="#" id="menu-button" data-activates="mobile-demo" class="button-collapse show-on-large btn waves-effect waves-light button-collapse">メニュー</a>
                            </div>
                        </div>
                        <ul class="side-nav" id="mobile-demo">
                            <li><a href="https://twitter.com/Unana2048" target="_blank">Twitter</a></li>
                            <li><a class="modal-trigger" href="#modal-notify">News</a></li>
                            <li><a href="hhttps://progressxfunction.wordpress.com/" target="_blank">Blog</a></li>
                            <li><a class="modal-trigger" href="#modal-notify">Links</a></li>
                        </ul>
                    </div>
                </nav>
            </div>
            <div class="section no-pad-bot">
                    <div class="container">
                        <br><br>
                        <h1 class="header center" id="main-logo"><img class="responsive-img" src="~/assets/image/logo.png"></h1>
                        <div class="row center">
                            <h5 class="header col s12 center" id="game-content">プログラミングロボットバトルシミュレーションゲーム.</h5>
                        </div>
                        <div class="row center">
                            <a href="#" id="comming-soon-button" class="btn-large waves-effect waves-light">X-FUNCTION Comming Soon</a>
                        </div>
                        <br><br>
                    </div>
            </div>
            <div class="parallax"><img src="~/assets/image/carnagelike-gif.gif" alt="carnagelike" style="display: block; transform: translate3d(-50%, 351px, 0px);"></div>
        </div>
        <div id="modal-notify" class="modal">
            <div class="modal-content">
                <p>LinksおよびNewsは準備中です。しばらくお待ちください。</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    mounted() {
        $('.modal').modal();
    }
}
</script>


<style lang="scss" scoped>
$thick-blue-color: #376d91;

#index-banner {
  box-shadow: inset 0 0 0 2000px rgba(55, 57, 58, 0.58);
  h5 {
    color: #ffffff;
  }
  #comming-soon-button,
  #menu-button {
    background-color: $thick-blue-color;
  }
  #menu-button {
    opacity: 0.3;
    margin-left: 0px;
  }
  #navs {
    height: 50px;
    background-color: $thick-blue-color;
  }
  #mobile-demo {
    background-color: #000;
    li {
      a {
        color: #ffffff;
      }
    }
  }
}
#modal-notify {
    color: #fff;
    background-color: $thick-blue-color;
}
</style>

