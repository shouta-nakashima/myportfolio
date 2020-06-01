<template>
  <div class="card mb-3" style="max-width: 1000px; max-height: 1000px; margin: auto">
    <div class="row no-gutters">
      <div class="col-md-4">
        <img style="border-radius: 50%; margin: 20px 0; border: solid 1px black;" class="bd-placeholder-img" width="200" height="200" src="../assets/nakaji.jpg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img" aria-label="Placeholder: Image"><rect width="100%" height="100%" fill="#868e96"/>
        <h3 style="color: black;">Contact</h3>
        <a style="text-decoration: none; color: 1da1f2;" href="https://twitter.com/shota_nakaji"><h5 class="twitter">Twitter</h5></a>
        <p style="color: black; font-weight: bold;">E-mail:<br>fantajista5.6nakaji.s@gmail.com</p>
      </div>
      <div class="col-md-8">
        <div class="card-body">
          <h5 class="card-title" style="font-size: 30px;">中嶋 翔太</h5>
          <p style=" display: flex; justify-content: center;" class="card-text">
            <ul style="list-style: none; text-align: left;">
              <li class="titled">Birth</li>
              <li class="titled">High school</li>
              <li class="titled">Residence</li>
              <li class="titled">Hobby</li>
            </ul>
            <ul style="list-style: none; text-align: left;">
              <li class="name">1986/05/06</li>
              <li class="name">三井高等学校 スポーツ健康コース卒</li>
              <li class="name">福岡県 大野城市</li>
              <li class="name">バス釣り 野球</li>
            </ul>
          </p>
          <h5 class="titled">Work history</h5>
            <p style="color: black; ">陸上自衛隊(2005/04~2009/03)〜<br><br>JR西日本新幹線テクノス(2009/04~2019/12)</p>
        </div>
      </div>
    </div>  
  </div>
</template>

<script>


export default {
  
}
</script>

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
  padding-bottom: 5px;
  color: darkgray;
}

.name {
  padding-bottom: 5px;
}
</style>