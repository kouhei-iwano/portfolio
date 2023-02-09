<template>
    <div>
        <h1 class="content-title"><font-awesome-icon icon="user-circle" class="icon"/> About</h1>
        <div>
            <div class="about">
              <div class="me">
                <h2><font-awesome-icon icon="pen" class="icon"/> Name</h2>
                <p class="text">Kohei Iwano</p>
              </div>

              <div class="me">
                <h2><font-awesome-icon icon="school" class="icon"/> School</h2>
                <p class="text">Hosei University</p>
              </div>

              <div class="me">
                <h2><font-awesome-icon icon="birthday-cake" class="icon"/> Birthday</h2>
                <p class="text">1999-05-28</p>
              </div>
            </div>
            

            <h2><font-awesome-icon icon="search" class="icon resent"/> Recent interests</h2>
            <p class="text">
              機械学習、Webアプリケーションの設計に興味があります。<br>
              ユーザー目線で開発業務を行えるバックエンドエンジニアを目指しています。
            </p>
        </div>
    </div>
</template>


<style scoped>
.about{
    display:inline-flex;
    padding-left: 5%;
    padding-right: 5%;
    
}

.resent{
  margin-top: 50px;
}

.me{
    margin:0 50px;
}

.text{
  font-weight: 300;
}


@media screen and (max-width: 768px){
	.about {
		flex-direction: column;
	}

	.me {
    margin: 0 auto;
	}
}
</style>