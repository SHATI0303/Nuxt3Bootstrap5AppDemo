<template>
  <div class="container">
     <Mycomponent title="人気な犬図鑑" />

     <ul style="list-style: none; display: flex; flex-direction: row; justify-content: center; align-items: center; gap: 2cm;">
  <li>
    <div style="text-align: center;">
  <nuxt-link to="/dogs/toy-poodle">
    <img class="photo" src="~/assets/toy.jpg" 
      alt="トイプードル"
      style="border-radius: 50%;"
      width="129"
      height="129"
    >
    <br>
    1位トイ・プードル
  </nuxt-link>
</div>
  </li>
  <li>
    <div style="text-align: center;">
  <nuxt-link to="/dogs/chihuahua">
    <img class="photo" src="~/assets/tiwawa.jpg" 
      alt="チワワ"
      style="border-radius: 50%;"
      width="129"
      height="129"
    >
    <br>
    2位チワワ
  </nuxt-link>
</div>

  </li>
  <li>
    <div style="text-align: center;">
      <nuxt-link to="/dogs/shiba">
      <img class="photo" src="~/assets/shiba.jpg" 
        alt="柴犬"
        style="border-radius: 50%;"
        width="129"
        height="129"
      >
      <br>
      3位柴(豆しばを含む)
     </nuxt-link>
    </div>
  </li>
</ul>


<ul style="list-style: none; display: flex; flex-direction: row; justify-content: center; align-items: center; gap: 2cm;">
  <li>
    <div style="text-align: center;"><nuxt-link to="/dogs/miniature-dachshund">
      <img class="photo" src="~/assets/miniature-dachshund.jpg" 
        alt="ミニチュア・ダックスフンド"
        style="border-radius: 50%;"
        width="129"
        height="129"
      >
      <br>
    4位ミニチュア・ダックスフンド
  </nuxt-link>
    </div>
  </li>
  <li>
    <div style="text-align: center;"><nuxt-link to="/dogs/pomeranian">
      <img class="photo" src="~/assets/pomeranian.jpg" 
        alt="ポメラニアン"
        style="border-radius: 50%;"
        width="129"
        height="129"
      >
      <br>
    5位ポメラニアン
  </nuxt-link>
    </div>
  </li>
  <li>
    <div style="text-align: center;">
      <nuxt-link to="/dogs/miniature-schnauzer">
      <img class="photo" src="~/assets/min.jpeg" 
        alt="ミニチュア・シュナウザー"
        style="border-radius: 50%;"
        width="129"
        height="129"
      >
      <br>
    6位ミニチュア・シュナウザー
  </nuxt-link>
    </div>
  </li>
</ul>
<ul style="list-style: none; display: flex; flex-direction: row; justify-content: center; align-items: center; gap: 2cm;">
      <li>
        <div style="text-align: center;">
          <nuxt-link to="/dogs/french-bulldog">
      <img class="photo" src="~/assets/french.jpg"
        alt="フレンチ・ブルドッグ"
        style="border-radius: 50%;"
        width="129"
        height="129"
      >
      <br>
        7位フレンチ・ブルドッグ
      </nuxt-link>
        </div>
      </li>
      <li>
        <div style="text-align: center;">
          <nuxt-link to="/dogs/yorkshire-terrier">
      <img class="photo" src="~/assets/yo-ku.jpg" 
        alt="ヨークシャー・テリア"
        style="border-radius: 50%;"
        width="129"
        height="129"
      >
      <br>
        8位ヨークシャー・テリア
      </nuxt-link>
        </div>
      </li>
      <li>
        <div style="text-align: center;">
          <nuxt-link to="/dogs/golden-retriever">
         <img class="photo" src="~/assets/golden.jpg" 
         alt="ゴールデン・レトリバー"
         style="border-radius: 50%;"
         width="129"
         height="129"
       >
        <br>
      9位ゴールデン・レトリバー
    
  </nuxt-link>
      </div>
      </li>
    </ul>
  </div>
  </template>
   
  <style>
   

    .page-title {
    font-size: 48px;
    margin-top: 40px;
    }
  </style>


