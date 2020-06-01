<template>
  <div>
    <div class="card mb-3" style="max-width: 1000px; max-height: 1000px; margin: auto">
      <div class="row no-gutters">
        <div class="col-md-6">
        <div class="card-body">
          <h5 class="card-title" style="font-size: 25px; padding-bottom: 20px;">/Skills</h5>
          
            <h5 class="titled">FrontEnd</h5>
            <p style="color: black; ">
              <ul style=" list-style: none; padding: 0;">
                <li class="line">◆HTML5/CSS3</li>
                <li class="line">◆JavaScript/Jquery</li>
                <br>
                <li class="line">◆VueJS/NuxtJS</li>
              </ul>
            </p>
            <h5 class="titled" style="padding-top: 15px;">ServerSide</h5>
            <p style="color: black; ">
              <ul style=" list-style: none;">
                <li class="line">◆Ruby/Rails</li>
                <li class="line">◆PHP/Laravel</li>
              </ul>
            </p>
            <h5 class="titled" style="padding-top: 15px;">Others</h5>
            <p style="color: black; ">
              <ul style=" list-style: none;">
                <li class="line">◆GitHub</li>
                <li class="line">◆Slack</li>
              </ul>
            </p>
      </div>
        </div>
        <div class="col-md-6">
          <div class="card-body">
            <h5 class="card-title" style="font-size: 25px; padding-bottom: 50px;">/Explain</h5>
            <p style="text-align: left; padding-bottom: 5px;" class="card-text">
              2020/01よりTECHCAMPに入校しRuby/Railsを中心に学習してきました。最終課題ではチーム開発を経験し、フリマアプリを制作しました。Railsを使ったアプリケーションの開発を行うことが出来ます。<br>また、現在独学ではありますが、PHP/Laravel、VueJS/NuxtJSを学習しています。その成果としてアプリケーションの開発を行いました。実践的なスキルに関してはまだまだですが、一通りの学習のを通しての成果を形にする事ができました。<br><br>今後も自身のスキルアップを測っていくと同時に、実践的な技術の習得に努めていきたいと考えています。
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card.mb-3 {
  box-shadow: 4px 4px 5px grey;
  display: flex;
  
}
.card-title,
.card-text {
  color: black;
  
}

.titled {
  padding-bottom: 2px;
  color: darkgray;
}

.name {
  padding-bottom: 5px;
}

.line {
  display: inline;
  padding: 0 20px 0 0;
  font-weight: bold;
 
}
</style>