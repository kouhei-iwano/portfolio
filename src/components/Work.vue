<template>
    <div>
        <h1 class="content-title"><font-awesome-icon icon="hammer" class="icon"/> Works</h1>
        
        <ul class="works">
          <li class="card">
            <img class="card-img" src="../assets/work/fpailab.webp" alt="">
            <div class="card-content">
              <h1 class="card-title jp">未来植物AI研究所のサイト</h1>
              <p class="card-text">きゅうり病害画像自動診断Webアプリのデモ公開</p>
              <p class="card-lang">Language : HTML,CSS,JavaScript</p>
              <br>
              <a href="https://kouhei-iwano.github.io/future-plant-ai-lab/" class="card-link">Website</a>
              <a href="https://github.com/kouhei-iwano/future-plant-ai-lab" class="card-link github-link">Github</a>
            </div>
          </li>
          <li class="card">
            <img class="card-img" src="../assets/work/cucumber-ios-app.webp" alt="">
            <div class="card-content">
              <h1 class="card-title jp">画像分類 iOS機械学習アプリ</h1>
              <p class="card-text">きゅうり病害画像自動診断iOSアプリ作成</p>
              <p class="card-lang">Language : Swift</p>
              <br>
              <a href="https://github.com/kouhei-iwano/portfolio" class="card-link github-link">Github</a>
            </div>
          </li>
          <li class="card">
            <img class="card-img" src="../assets/work/ipjs2022.webp" alt="">
            <div class="card-content">
              <h1 class="card-title jp">IPJS 2022年度全国大会<br>学生奨励賞受賞</h1>
              <p class="card-text">物体検出・認識技術を効果的に組み合わせた<br>2段階の植物病害診断法の検討</p>
              <br>
              <a href="https://www.ipsj.or.jp/event/taikai/84/ipsj_web2022/data/pdf/4U-06.html" class="card-link">Abstract</a>
              <a href="chrome-extension://oemmndcbldboiebfnladdacbdfmadadm/https://ipsj.ixsq.nii.ac.jp/ej/?action=repository_action_common_download&item_id=221047&item_no=1&attribute_id=1&file_no=1" class="card-link github-link">PDF</a>
            </div>
          </li>
          <li class="card">
            <img class="card-img" src="../assets/work/this.webp" alt="">
            <div class="card-content">
              <h1 class="card-title">This site</h1>
              <p class="card-text">私のプロフィールサイト</p>
              <p class="card-lang">Language : JavaScript(Vue.js)</p>
              <br>
              <a href="https://github.com/kouhei-iwano/portfolio" class="card-link github-link">Github</a>
            </div>
          </li>
        </ul>
    </div>
</template>




<style>
.works{
  list-style-type: none;
  padding-left: 0;
  text-align: center;
  padding-left: 15%;
  padding-right: 15%;
}

.jp{
  font-weight: 100;
}

.card-lang{
  font-weight: 500;
}

.card {
  display: inline-block;
  margin: 30px 60px;
  width: 350px;
  background: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px #ccc;
}
.card-img {
  border-radius: 5px 5px 0 0;
  width: 100%;
  height: 200px;
  object-fit: contain;
}
.card-content {
  padding: 20px;
}
.card-title {
  font-size: 20px;
  margin-bottom: 20px;
  text-align: center;
  color: #333;
}
.card-text {
  color: #777;
  font-size: 14px;
  line-height: 1.5;
}

.card-link{
  border: 2px solid #00aaff;
  text-decoration: none;
  color: #00aaff;
  margin: 0 10px;
  padding: 5px 10px;
  border-radius: 5px;
  transition: 0.4s;
  font-weight: bold;
}
.card-link:hover {
  background-color: #00aaff;
  color: white;
}

.github-link{
  border-color: #171515;
  color: #171515;
}
.github-link:hover {
  background-color: #171515;
  color: white;
}



/*.work-content{
	width: 350px;
	padding: 10px;
	margin: 30px 60px;
  display: inline-block;
}

.work-content:hover{
  background-color: rgba(50, 50, 100, 0.3);
}

.works-image{
    width: 100%;
}*/

@media screen and (max-width: 768px){
  .works{
      padding-left: 1%;
      padding-right: 1%;
  }

  .card-link{
    border: 2px solid #00aaff;
    background-color: #00aaff;
    text-decoration: none;
    color: white;
    margin: 0 10px;
    padding: 5px 10px;
    border-radius: 5px;

    font-weight: bold;
  }

  .github-link{
    background-color: #171515;
    border-color: #171515;
  }
}

@media screen and (max-width: 550px){
  .card{
    width: 280px;
    margin: 30px 0;
  }

  
}
</style>