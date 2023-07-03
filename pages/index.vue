<template>
  <div class ="mt-3">
    <!--Header-->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">円卓決算</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link" href="#">各種設定</a>
        </li>
      </ul>
      <span class="navbar-text">
        Navbar text with an inline element
      </span>
    </div>
  </div>
</nav>

 <!-- main page-->
    <div class="card-group">
  <div class="card">
    <div class="card-body">
      <h5 class="card-title">各種入力</h5>
      <ul>
        <li><NuxtLink to ="pages/home">複合仕分入力</NuxtLink></li>
        <li><NuxtLink to ="a">元帳入力</NuxtLink></li>
        <li><NuxtLink to ="to">通帳入力</NuxtLink></li>
      </ul>
    </div>
  </div>


  <div class="card">
    <div class="card-body">
      <h5 class="card-title">各種出力</h5>
      <ul class="list-inline">
      <div class="col-7">
      <li><NuxtLink to ="a">仕分帳</NuxtLink></li>
      <li><NuxtLink to ="a">出納表</NuxtLink></li>
      <li><NuxtLink to ="a">仕分検索</NuxtLink></li>
      <li><NuxtLink to ="a">合計残高計算書</NuxtLink></li>
      <li><NuxtLink to ="a">補助検索合計残高表</NuxtLink></li>
      <li><NuxtLink to ="a">消費税課税区分別集計書</NuxtLink></li>
      <li><NuxtLink to ="a">総勘定元帳</NuxtLink></li>
      <li><NuxtLink to ="a">補助元帳</NuxtLink></li>
      <li><NuxtLink to ="a">月次比較財務書表</NuxtLink></li>
      <li><NuxtLink to ="a">個人出納表</NuxtLink></li>
      <li><NuxtLink to ="a">経費精算書</NuxtLink></li>
      <li><NuxtLink to ="a">経費生産承認</NuxtLink></li>
    </div>
  </ul>
    </div>

  </div>
  <div class="card">
    <div class="card-body">
      <h5 class="card-title">年次決算</h5>
      <ul class="list-inline">
      <div class="col-4">
      <li><NuxtLink to ="a">期末整理表</NuxtLink></li>
      <li><NuxtLink to ="a">年次繰越</NuxtLink></li>
      <li><NuxtLink to ="a">決算報告書表示設定</NuxtLink></li>
      <li><NuxtLink to ="a">変動利用設定</NuxtLink></li>
      <li><NuxtLink to ="a">決算報告書</NuxtLink></li>
    </div>
  </ul>
    </div>
 </div>

    <div class="card">
    <div class="card-body">
      <h5 class="card-title">各種設定</h5>
      <ul class="list-inline">
      <div class="col-4">
      <li><NuxtLink to ="a">仕分帳</NuxtLink></li>
      <li><NuxtLink to ="a">出納表</NuxtLink></li>
    </div>
  </ul>
    </div>
</div>
</div>
</div>
</template>
