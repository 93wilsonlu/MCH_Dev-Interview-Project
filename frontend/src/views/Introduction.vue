<template>
  <div class="introduction">
    <header class="intro-header">
      <img class="profile-image" src="../assets/profile.jpeg" alt="">
      <div class="intro-text">
        <h2>自我介紹</h2>
        <p>
          我是山羊，目前是一名大學生，過去玩過演算法、資訊安全，曾接觸 Flutter, React, Bootstrap 等網頁開發技術。
        </p>
        <p>
          儘管不一定符合開發組的需求，但憑藉在資安打滾多年的自學經驗，我相信我能快速上手必要的知識。
        </p>
        <p>
          平時喜歡研究資安技術，有時看動畫，最近著迷於把 kernel 打爆。
        </p>
        <button class="contact-button">聯絡我們</button>
      </div>


    </header>
    <section class="about-section">

      <h3>參與黑客松開發部的理由</h3>
      <p>提升前後端實作能力，學習團隊合作，認識新朋友！</p>

      <h3>專長與興趣</h3>
      <ul>
        <li>
          <p>程式安全</p>
          <p>利用程式撰寫不當產生的記憶體漏洞，達成遠端程式執行、權限提升、沙盒逃逸等目的。</p>
        </li>
        <li>
          <p>逆向工程</p>
          <p>透過了解目標執行檔、行為或部分程式碼，獲取關鍵資訊或發現漏洞。</p>
        </li>
        <li>中醫內科</li>
        <li>動畫</li>
      </ul>

      <h3>經歷</h3>
      <ul>
        <li>HPC-AI Competition 第一名</li>
        <li>AIS3 2024 最佳專題</li>
        <li>AIS3 Pre-exam rk.7</li>
        <li>金盾獎、EOF、神盾、CGGC 等多項決賽</li>
        <li>Global Cybersecurity Camp 2025 學員</li>
        <li>SCAICT 2023 寒訓講師</li>
        <li>113 行政院網路攻防演練攻擊手</li>
      </ul>

      <h3>做過的專案</h3>
      <ul>
        <li><a href="https://github.com/93wilsonlu/three_topic_story">三題故事寫作網站</a>
          <p>靈感來自《文學少女》，使用者可創建帳號，透過系統給的隨機字詞撰寫故事，發佈到網站。</p>
        </li>
        <li>
          <a href="https://github.com/93wilsonlu/cp-problem-manager">競程題目管理</a>
          <p>Google 外掛管理待處理題目的狀態</p>
        </li>
        <li>
          <a href="https://github.com/93wilsonlu/expiring_food_reminder">過期食物提醒 Linebot</a>
          <p>使用者可輸入食物保存期限，Linebot 在當天提醒。</p>
        </li>
        <li>
          <a href="https://github.com/93wilsonlu/ResistanceCalculator">電阻計算器</a>
          <p>透過 React 構建的簡單電阻計算器。</p>
        </li>
      </ul>

      <h3>正在進行</h3>
      <ul>
        <li>kernel 安全研究</li>
        <li>2025 ISC 超級電腦大賽</li>
        <li>讀傷寒論</li>
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

.about-section li {
  margin-bottom: 10px;
}
</style>
