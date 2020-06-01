<template>
  <div class="container" style="padding-top: 30px;">
    <div class="row" style="margin: auto;">
      <div class="col-sm">
        <div class="card border-secondary mb-3" style="max-width: 18rem; margin: auto;">
            <img class="bd-placeholder-img card-img-top" width="100%" height="180" src="../assets/html-css.jpg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image cap"><title>Placeholder</title><rect width="100%" height="100%" fill="#868e96"/>
            <div class="mask">  
            <h2>HTML/CSS</h2>
            <p>★★★★☆</p>  
            <p>マークアップ言語は開発において必ず必要<br>になるので、それなりに理解はしています。<br>RailsではHamlやSassを使い開発をしています。</p>  
            </div>
        </div>
      </div>
      <div class="col-sm">
        <div class="card border-secondary mb-3" style="max-width: 18rem; margin: auto;">
          <img class="bd-placeholder-img card-img-top" width="100%" height="180" src="../assets/javascript.png" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image cap"><title>Placeholder</title><rect width="100%" height="100%" fill="#868e96"/>
          <div class="mask">  
          <h2>JavaScript</h2>
          <p>★★☆☆☆</p>  
          <p>TECHCAMPにて基礎を学習してきました。<br>今後も使用する頻度は高いので、しっかり<br>とスキルアップしていこうと思います。</p>  
          </div>
        </div>
      </div>
    </div>
    <div class="row" style="margin: auto;">
      <div class="col-sm">
        <div class="card border-secondary mb-3" style="max-width: 18rem; margin: auto;">
          <img class="bd-placeholder-img card-img-top" width="100%" height="180" src="../assets/ruby-rails.jpg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image cap"><title>Placeholder</title><rect width="100%" height="100%" fill="#868e96"/>
          <div class="mask">  
          <h2>Ruby on Rails</h2>
          <p>★★★☆☆</p>  
          <p>現段階では一番理解している言語で、開発<br>実績も一番あります。TECHCAMPの学習の<br>中でメインで使用する言語です。</p>  
          </div> 
        </div>
      </div>
      <div class="col-sm">
        <div class="card border-secondary mb-3" style="max-width: 18rem; margin: auto;">
          <img class="bd-placeholder-img card-img-top" width="100%" height="180" src="../assets/vue.png" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image cap"><title>Placeholder</title><rect width="100%" height="100%" fill="#868e96"/>
          <div class="mask">  
          <h2>VueJS</h2>
          <p>★★☆☆☆</p>  
          <p>まだまだ理解不足な事も多いため、開発<br>していく中で、しっかりとスキルアップ<br>していきたいです。今後RailsやLaravel等と<br>併用して開発を行う予定です。</p>  
          </div> 
        </div>
      </div>
    </div>
    <div class="row" style="margin: auto;">
      <div class="col-sm">
        <div class="card border-secondary mb-3" style="max-width: 18rem; margin: auto;">
          <img class="bd-placeholder-img card-img-top" width="100%" height="180" src="../assets/laravel.png" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image cap"><title>Placeholder</title><rect width="100%" height="100%" fill="#868e96"/>
          <div class="mask">  
          <h2>Laravel 6.0~</h2> 
          <p>★★☆☆☆</p> 
          <p>PHPのフレームワークとして学習しています。<br>Udemyの教材や、参考書、公式サイトを利用<br>してアプリケーションの開発を行っています。<br>スキルアップしてより良い開発を行いたいです。</p>  
          </div> 
        </div>
      </div>
      <div class="col-sm">
        <div class="card border-secondary mb-3" style="max-width: 18rem; margin: auto;">
          <img class="bd-placeholder-img card-img-top" width="100%" height="180" src="../assets/php.jpg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image cap"><title>Placeholder</title><rect width="100%" height="100%" fill="#868e96"/>
          <div class="mask">  
          <h2 >PHP 7.0~</h2>
          <p >★★☆☆☆</p>  
          <p >基本的な構文は理解していますが、まだ勉<br>強を始めて日が浅いので今後も勉強して理解<br>を深めたいです。基本的にはLaravelをを使用<br>してアプリケーションの開発をしています。</p>  
          </div> 
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

.mask {
  color: black;
}
.card.border-secondary.mb-3 {
  width: 300px;
  height: 170px;
  overflow: hidden;
  position: relative;
  box-shadow: 4px 4px 5px grey;
}

.card.border-secondary.mb-3  .mask, .card.border-secondary.mb-3 .content {
    width: 300px;
    height: 170px;
    position: absolute;
    overflow: hidden;
    top: 0;
    left: 0;
    
    
}
.card.border-secondary.mb-3 img {
	transition: all 0.2s ease-in; 
  display: block;
  position: relative;
}
.card.border-secondary.mb-3 .mask { 
	opacity: 0;
    background-color: rgba(250, 251, 252, 0.7); 
    transition: all 0.4s ease-in-out;
}
.card.border-secondary.mb-3 h2{
    transform: translateY(-100px);
    opacity: 0;
    transition: all 0.2s ease-in-out;
}
.card.border-secondary.mb-3 p{
    transform: translateY(100px);
    font-size: 13px;
    opacity: 0;
	transition: all 0.2s linear;
}
.card.border-secondary a.info{
    opacity: 0;
	transition: all 0.2s ease-in-out;
}

.card.border-secondary.mb-3:hover .mask { 
	opacity: 1;
}						
.card.border-secondary.mb-3:hover img { 
	transform: scale(1.1);
}
.card.border-secondary.mb-3:hover h2,
.card.border-secondary.mb-3:hover p,
.card.border-secondary.mb-3:hover a.info {
    opacity: 1;
    transform: translateY(0px);
}
.card.border-secondary.mb-3:hover a.info {
    transition-delay: 0.2s;
}
</style>