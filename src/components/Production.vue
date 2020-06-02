<template>
  <div>
    <div class="container" style="padding: 30px 0; max-height: 1800px;">
      <div class="row">
        <div class="col-sm" style="height: 390px;">
          <div class="card" style="width: 18rem; margin: auto;">
            <img class="bd-placeholder-img card-img-top" width="100%" height="180" src="../assets/Chat-space.png" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image cap"><title>Placeholder</title><rect width="100%" height="100%" fill="#868e96"/>
            <div class="card-body">
              <a style="text-decoration: none; color: rgb(240, 148, 148);" href="http://18.180.47.55"><h5 class="card-title">Chat Space</h5></a>
                <div class="sub-title">
                  <ul>
                    <li><p class="card-text">TECHCAMPのカリキュラム内で作成したチャットアプリです。初めてデプロイした作品です。</p></li>
                    <li><p class="card-text">2020/02/Rails</p></li>
                    <li><a href="https://github.com/shouta-nakashima/chat-space"><img class="github" src="../assets/GitHub.jpeg"></a></li>
                  </ul>
                </div>
            </div>
          </div>
        </div>
        <div class="col-sm" style="height: 390px;">
         <div class="card" style="width: 18rem; margin: auto;">
            <img class="bd-placeholder-img card-img-top" width="100%" height="180" src="../assets/furima.jpg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image cap"><title>Placeholder</title><rect width="100%" height="100%" fill="#868e96"/>
            <div class="card-body">
              <a style="text-decoration: none; color: skyblue;" href=" http://18.177.42.233/"><h5 class="card-title">Furima</h5></a>
                <div class="sub-title">
                  <ul>
                    <li><p class="card-text">TECHCAMP最終課題でチーム開発を行いました。フリマアプリのコピーサイトです。</p></li>
                    <li><p class="card-text">2020/03/Rails</p></li>
                    <li><a href="https://github.com/shouta-nakashima/freemarket_sample_70d"><img class="github" src="../assets/GitHub.jpeg"></a></li>
                  </ul>
                </div>
            </div>
          </div>
        </div>
        <div class="col-sm" style="height: 390px;">
         <div class="card" style="width: 18rem; margin: auto; ">
            <img class="bd-placeholder-img card-img-top" width="100%" height="180" src="../assets/thanks-board.png" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image cap"><title>Placeholder</title><rect width="100%" height="100%" fill="#868e96"/>
            <div class="card-body">
              <a style="text-decoration: none; color: orange;" href="http://18.177.93.163/"><h5 class="card-title">ThanksBoard</h5></a>
                <div class="sub-title">
                  <ul>
                    <li><p class="card-text">TECHCAMP同期とチーム開発を行いました。医療従事者の方へ感謝を伝えるサイトです。</p></li>
                    <li><p class="card-text">2020/05/Rails</p></li>
                    <li><a href="https://github.com/shouta-nakashima/thanksboard"><img class="github" src="../assets/GitHub.jpeg"></a></li>
                  </ul>
                </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div style="max-height: 1800px;" class="container">
      <div class="row">
        <div class="col-sm" style="height: 380px;">
          <div class="card" style="width: 18rem; margin: auto;">
            <img class="bd-placeholder-img card-img-top" width="100%" height="180" src="../assets/photosactive.jpg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image cap"><title>Placeholder</title><rect width="100%" height="100%" fill="#868e96"/>
            <div class="card-body">
              <a style="text-decoration: none; color: rgb(136, 74, 148);" href="http://photos-active.herokuapp.com/"><h5 class="card-title">Photo's Active</h5></a>
                <div class="sub-title">
                  <ul>
                    <li><p class="card-text">家族の共有アルバムをテーマに作成しました。ユーザー登録をすると写真の投稿が出来ます。</p></li>
                    <li><p class="card-text">2020/05/Laravel/PHP</p></li>
                    <li><a href="https://github.com/shouta-nakashima/Photos-active"><img class="github" src="../assets/GitHub.jpeg"></a></li>
                  </ul>
                </div>
            </div>
          </div>
        </div>
        <div class="col-sm" style="height: 380px;">
          <div class="card" style="width: 18rem; margin: auto;">
            <img class="bd-placeholder-img card-img-top" width="100%" height="180" src="../assets/portfolio.png" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image cap"><title>Placeholder</title><rect width="100%" height="100%" fill="#868e96"/>
            <div class="card-body">
              <h5 class="card-title" style="text-decoration: none; color: rgb(49, 185, 144);">Myportfolio</h5>
                <div class="sub-title">
                  <ul>
                    <li><p class="card-text">現在のサイトです。初めてVueJSでSPAを作成しました。自身のポートフォリオ サイトになります。</p></li>
                    <li><p class="card-text">2020/05/VueJS</p></li>
                    <li><a href="https://github.com/shouta-nakashima/myportfolio"><img class="github" src="../assets/GitHub.jpeg"></a></li>
                  </ul>
                </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

.sub-title {
  position: relative;
  display: none;
}

.sub-title > ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.sub-title > ul > li > a {
  text-decoration: none;
}

.card {
  box-shadow: 4px 4px 5px grey;
}

.card:hover .sub-title {
  display: inline-block;
}

.card-title {
  transition: all 0.3s ease 0s;
  cursor: pointer;
}

.card-title:hover {
  transform: translateY(-0.1875em);
  font-size: 25px;
}

.card-text {
  color: black;
}

.github {
  border-radius: 5px;
  box-shadow: 0 0 3px 0 rgba(0, 0, 0, 0.25);
  cursor: pointer;
  transition: all 0.3s ease 0s;
}

.github:hover {
  box-shadow: 0 3px 6px 0 rgba(0, 0, 0, 0.25);
  transform: translateY(-0.1875em);
}

</style>
