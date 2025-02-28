<template>
  <div class="introduction">
    <header class="intro-header">
      <div class="intro-content">
        <div class="intro-text">
          <h2>自我介紹</h2>
          <p>
            我是李聿宸，目前就讀清大資工大二，對於前後端開發、機器學習、專案設計很有興趣，因此想要在開發部中累積實務經驗，並向各位電神學習。
            我平常喜好寫個人小專案、寫題目、練電吉他、打羽球等等。
            有時我會自己寫一些專題，上網刷LeetCode或是CSES。在團隊專題中，我能擔任組長或組員的責任，並且能夠與其他組員良好溝通，共同完成專案。
            我期待能加入黑客松開發部，共同將天碼行空的點子化為現實！
          </p>
        </div>
        <div class="profile-image">
          <img src="/src/images/intro.jpg" alt="李聿宸的照片">
        </div>
      </div>
      <div class="contact-section">
      <a href="eason.yuchen.lee@gmail.com" class="contact-button">
        <i class="fas fa-envelope"></i>
        聯絡我
      </a>
    </div>
    </header>
    <section class="about-section">
      <h3>個人資訊補充</h3>
      <h4>個人Projects</h4>
      <ul>
        <li>Bird Vocalization Generation Using Diffusion Models
          <ul>
            <li>Implemented Diffusion and GAN models</li>
            <li>Trained on a self-collected dataset of bird vocalizations</li>
            <li>Achieved realistic bird vocalization generation with a Streamlit web app</li>
            <li>
              <a href="https://github.com/Windmill10/ML_diffusion" class="link" target="_blank">GitHub Repository</a>
            </li>
            <li>
              <a href="https://mldiffusion.streamlit.app/" class="link" target="_blank">Streamlit Web App</a>
            </li>
          </ul>
        </li>
        <li>Spotify CLI
          <ul>
            <li>Written in Rust from scratch</li>
            <li>Utilized Spotify API to create a CLI for daily Spotify usage</li>
            <li>Features include:
              <ul>
                <li>Search for songs and add to playlists</li>
                <li>Play, pause, skip, and rewind songs</li>
              </ul>
            </li>
            <li>Used on a daily basis</li>
            <li><a href="https://github.com/Windmill10/Spotify_API_2" class="link">GitHub Repository</a></li>
          </ul>
        </li>
      </ul>
      <h4>課業表現</h4>
      <ul>
        <li>
          <ul>
            <li>A+ in Introduction to Programming II and Competitive Programming</li>
            <li>A in Logic Design, Data Structures, Machine Learning</li>
            <li>Always fond of course projects and assignments</li>
          </ul>
        </li>
      </ul>
      <h4>技術專長</h4>
      <ul>
        <li>
          <ul>
            <li>Python</li>
            <li>C/C++</li>
            <li>Rust(basic)</li>
            <li>HTML/CSS(basic)</li>
            <li>Verilog(basic)</li>
          </ul>
        </li>
      </ul>
    </section>
  </div>
</template>

<style scoped>

.introduction {
  padding: 40px 20px;
  max-width: 1000px;
  margin: 0 auto;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  color: #333;
  background-color: #fafafa;
  border-radius: 15px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
}

.intro-header {
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
  padding: 40px;
  border-radius: 12px;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
  border-left: 5px solid #6c757d;
}

.intro-content {
  display: flex;
  flex-direction: row;
  gap: 30px;
  align-items: center;
}

.profile-image {
  flex: 0 0 auto;
  width: 200px;
  height: 200px;
  border-radius: 70%;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  border: 4px solid white;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  margin-top: 40px;
}

.profile-image:hover {
  transform: scale(1.03);
  box-shadow: 0 6px 15px rgba(0, 0, 0, 0.15);
}

.profile-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center 20%;
}


.intro-header h2 {
  font-size: 2.2rem;
  color: #343a40;
  margin-bottom: 20px;
  font-weight: 600;
  border-bottom: 2px solid #dee2e6;
  padding-bottom: 10px;
}

.intro-header p {
  font-size: 1.1rem;
  line-height: 1.7;
  color: #495057;
}

.contact-section {
  display: flex;
  align-items: center;
  margin-top: 30px;
  flex-wrap: wrap;
  gap: 20px;
}

.contact-button {
  display: flex;
  align-items: center;
  padding: 12px 24px;
  background: linear-gradient(135deg, #4b6cb7 0%, #182848 100%);
  border: none;
  border-radius: 30px;
  color: white;
  font-size: 1rem;
  cursor: pointer;
  font-weight: 600;
  transition: all 0.3s ease;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.contact-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
  background: linear-gradient(135deg, #5d7dcb 0%, #25395f 100%);
}


.about-section {
  margin-top: 40px;
  padding: 30px 40px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #ffffff;
  border-radius: 12px;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.05);
}

.about-section h3 {
  font-size: 1.8rem;
  margin: 10px 0 20px;
  color: #343a40;
  font-weight: 6000;
  border-bottom: 2px solid #e9ecef;
  padding-bottom: 8px;
}

.about-section h4 {
  font-size: 1.4rem;
  margin: 25px 0 15px;
  color: #495057;
  font-weight: 600;
  position: relative;
  padding-left: 15px;
}

.about-section h4::before {
  content: "";
  position: absolute;
  left: 0;
  top: 50%;
  transform: translateY(-50%);
  width: 8px;
  height: 20px;
  background-color: #6c757d;
  border-radius: 4px;
}

.about-section p {
  font-size: 1.05rem;
  line-height: 1.7;
  color: #495057;
}

.about-section ul {
  list-style-type: none;
  padding-left: 0;
  margin-bottom: 25px;
}

.about-section > ul > li {
  font-weight: 600;
  font-size: 1.2rem;
  margin: 25px 0 15px;
  color: #495057;
  background-color: #f8f9fa;
  padding: 12px 18px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
  border-left: 4px solid #6c757d;
}

.about-section > ul > ul,
.about-section ul ul {
  padding-left: 25px;
  margin: 15px 0;
}

.about-section ul ul li {
  font-weight: normal;
  font-size: 1.05rem;
  margin: 10px 0;
  position: relative;
  padding-left: 5px;
  color: #495057;
  transition: transform 0.2s ease;
}

.about-section ul ul li:hover {
  transform: translateX(3px);
}

.about-section ul ul li::before {
  content: "•";
  position: absolute;
  left: -15px;
  color: #6c757d;
  font-size: 1.2rem;
}

.about-section .link {
  color: #3a86ff;
  text-decoration: none;
  position: relative;
  font-weight: 500;
  transition: all 0.2s ease;
}

.about-section .link:hover {
  color: #0056b3;
}

.about-section .link::after {
  content: "";
  position: absolute;
  width: 0;
  height: 2px;
  bottom: -2px;
  left: 0;
  background-color: #3a86ff;
  transition: width 0.3s ease;
}

.about-section .link:hover::after {
  width: 100%;
}
</style>

