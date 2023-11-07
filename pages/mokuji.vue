<template>
  <div class="container">
     <h1 class="page-title">人気な犬の図鑑</h1>
    <ul>
      <li>
        1位<nuxt-link to="/dogs/toy-poodle">トイ・プードル</nuxt-link>
      </li>
      <li>
        2位<nuxt-link to="/dogs/chihuahua">チワワ</nuxt-link>
      </li>
      <li>
        3位<nuxt-link to="/dogs/shiba">柴(豆しばを含む)</nuxt-link>
      </li>
      <li>
        4位<nuxt-link to="/dogs/miniature-dachshund">ミニチュア・ダックスフンド</nuxt-link>
      </li>
      <li>
        5位<nuxt-link to="/dogs/pomeranian">ポメラニアン</nuxt-link>
      </li>
      <li>
        6位<nuxt-link to="/dogs/miniature-schnauzer">ミニチュア・シュナウザー</nuxt-link>
      </li>
      <li>
        7位<nuxt-link to="/dogs/french-bulldog">フレンチ・ブルドッグ</nuxt-link>
      </li>
      <li>
        8位<nuxt-link to="/dogs/yorkshire-terrier">ヨークシャー・テリア</nuxt-link>
      </li>
      <li>
        9位<nuxt-link to="/dogs/maltese">マルチーズ</nuxt-link>
      </li>
      <li>
        10位<nuxt-link to="/dogs/golden-retriever">ゴールデン・レトリバー</nuxt-link>
      </li>
    </ul>
  </div>
  <style>
   
    body {
      background-color: #f5f5dc;
    }
    .page-title {
    font-size: 48px;
    margin-top: 40px;
    }
  </style>
</template>
