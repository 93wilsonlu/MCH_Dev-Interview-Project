<template>
  <div class="introduction">
    <header class="intro-header">
      <img class="profile-image" src="../assets/profile.jpeg" alt="">
      <div class="intro-text">
        <h2>自我介紹</h2>
        <p>
          我是山羊，目前是一名大學生，過去玩過演算法、資訊安全。
        </p>
        <p>
          平時喜歡研究資安技術，也喜歡看動畫，最近著迷於把 kernel 打爆。
        </p>
        <button class="contact-button">聯絡我們</button>
      </div>


    </header>
    <section class="about-section">
      <h3>專長與興趣</h3>
      <ul>
        <li>二進制安全</li>
        <li>逆向工程</li>
        <li>中醫內科</li>
        <li>動畫</li>
      </ul>

      <h3>做過的垃圾</h3>
      <ul>
        <li><a href="https://github.com/93wilsonlu/three_topic_story">三題故事寫作網站</a></li>
        <li><a href="https://github.com/93wilsonlu/cp-problem-manager">競程題目管理</a></li>
        <li><a href="https://github.com/93wilsonlu/expiring_food_reminder">過期食物提醒 Linebot</a></li>
        <li><a href="https://github.com/93wilsonlu/ResistanceCalculator">電阻計算器</a></li>
      </ul>

      <h3>目前正在做</h3>
      <ul>
        <li>kernel 安全</li>
        <li>讀傷寒論</li>
        <li>ISC 超級電腦大賽</li>
      </ul>
    </section>
  </div>
</template>


<style scoped>
.introduction {
  padding: 40px 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.intro-header {
  background-color: #f5f5f5;
  padding: 40px;
  border-radius: 10px;
  display: flex;
}

.profile-image {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  margin-right: 40px;
}


.intro-text h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.intro-text p {
  font-size: 1.1rem;
  margin-bottom: 20px;
}

.contact-button {
  padding: 10px 20px;
  background-color: #656d73;
  border: none;
  border-radius: 5px;
  color: #fff;
  cursor: pointer;
}

.contact-button:hover {
  background-color: #36383a;
}

.about-section {
  margin-top: 40px;
  padding: 0 40px;
}

.about-section h3 {
  font-size: 1.6rem;
  margin-top: 20px;
  margin-bottom: 10px;
}

.about-section p {
  font-size: 1rem;
  line-height: 1.6;
}

.about-section a {
  color: #656d73;
}

.about-section a:hover {
  color: #36383a;
}
</style>
