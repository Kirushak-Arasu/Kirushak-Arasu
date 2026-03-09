<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kirushak — GitHub Profile</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Fira+Code:wght@400;500&display=swap" rel="stylesheet">
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: #0d1117;
    color: #e6edf3;
    font-family: 'Inter', sans-serif;
    padding: 40px 20px 60px;
    line-height: 1.6;
  }

  .page {
    max-width: 700px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 28px;
  }

  /* ---- HEADER ---- */
  .header { text-align: center; }

  .gif-wrap {
    border-radius: 12px;
    overflow: hidden;
    margin-bottom: 20px;
    border: 1px solid #21262d;
  }
  .gif-wrap img { width: 100%; display: block; max-height: 220px; object-fit: cover; }

  h1 {
    font-size: 28px;
    font-weight: 700;
    color: #e6edf3;
    margin-bottom: 4px;
  }
  h1 .wave { display: inline-block; animation: wave 2.5s ease-in-out infinite; transform-origin: 70% 70%; }
  @keyframes wave { 0%,100%{transform:rotate(0)} 20%{transform:rotate(20deg)} 40%{transform:rotate(-8deg)} 60%{transform:rotate(16deg)} 80%{transform:rotate(-4deg)} }

  .subtitle { font-size: 15px; color: #8b949e; margin-bottom: 16px; }

  .badges { display: flex; justify-content: center; flex-wrap: wrap; gap: 8px; }
  .badge {
    display: flex; align-items: center; gap: 5px;
    padding: 5px 12px; border-radius: 6px;
    font-size: 12px; font-weight: 500;
    background: #161b22; border: 1px solid #21262d;
    color: #8b949e;
  }

  /* ---- DIVIDER ---- */
  hr { border: none; border-top: 1px solid #21262d; }

  /* ---- SECTION ---- */
  .section { display: flex; flex-direction: column; gap: 12px; }

  .section-title {
    font-size: 14px; font-weight: 600;
    color: #8b949e; text-transform: uppercase;
    letter-spacing: 1px;
    display: flex; align-items: center; gap: 8px;
  }
  .section-title::after {
    content: ''; flex: 1; height: 1px; background: #21262d;
  }

  /* ---- INFO BULLETS ---- */
  .info-list { display: flex; flex-direction: column; gap: 10px; }
  .info-item {
    display: flex; align-items: flex-start; gap: 12px;
    font-size: 14px; color: #c9d1d9;
  }
  .info-item .icon { font-size: 16px; flex-shrink: 0; margin-top: 1px; }
  .info-item a { color: #58a6ff; text-decoration: none; }
  .info-item a:hover { text-decoration: underline; }
  .info-item strong { color: #e6edf3; }

  /* ---- SOCIAL ICONS ---- */
  .social-row { display: flex; flex-wrap: wrap; gap: 10px; }
  .social-link {
    display: flex; align-items: center; justify-content: center;
    width: 38px; height: 38px;
    background: #161b22; border: 1px solid #21262d;
    border-radius: 8px;
    transition: border-color 0.15s, background 0.15s, transform 0.15s;
  }
  .social-link:hover { border-color: #58a6ff; background: #1f2937; transform: translateY(-2px); }
  .social-link img { width: 20px; height: 20px; filter: brightness(0) invert(0.7); }
  .social-link:hover img { filter: brightness(0) invert(0.9); }

  /* ---- TOOLS GRID ---- */
  .tools-grid { display: flex; flex-wrap: wrap; gap: 10px; }
  .tool {
    display: flex; align-items: center; gap: 8px;
    padding: 7px 14px;
    background: #161b22; border: 1px solid #21262d;
    border-radius: 8px;
    font-size: 13px; color: #c9d1d9;
    transition: border-color 0.15s, transform 0.15s;
    cursor: default;
  }
  .tool:hover { border-color: #388bfd; transform: translateY(-1px); }
  .tool img { width: 20px; height: 20px; object-fit: contain; }

  /* ---- STATS CARDS ---- */
  .stats-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }

  .stat-img-card {
    background: #161b22;
    border: 1px solid #21262d;
    border-radius: 10px;
    overflow: hidden;
    transition: border-color 0.15s;
  }
  .stat-img-card:hover { border-color: #388bfd; }
  .stat-img-card img { width: 100%; display: block; }
  .stat-img-card.full { grid-column: span 2; }

  /* ---- PROFILE VIEWS ---- */
  .meta-row { display: flex; align-items: center; gap: 12px; flex-wrap: wrap; }
  .views-badge img { height: 20px; }
  .trophy-wrap { overflow-x: auto; }
  .trophy-wrap img { height: 28px; }

  /* ---- FOOTER ---- */
  .footer {
    text-align: center;
    font-size: 13px; color: #8b949e;
    padding-top: 8px;
    font-family: 'Fira Code', monospace;
  }
  .footer span { color: #58a6ff; }
</style>
</head>
<body>
<div class="page">

  <!-- HEADER -->
  <div class="header">
    <div class="gif-wrap">
      <img src="https://images.squarespace-cdn.com/content/v1/5769fc401b631bab1addb2ab/1541580611624-TE64QGKRJG8SWAIUST7NS/ke17ZwdGBToddI8pDm48kPoswlzjSVMM-SxOp7CV59BZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZamWLI2zvYWH8K3-s_4yszcp2ryTI0HqTOaauohrI8PIo7CX57s699656XyhOc-1P2tlBrQVMkqp8N0iScJPaFo/coding-freak.gif" alt="coding gif">
    </div>
    <h1><span class="wave">👋</span> Hi, I'm Kirushak</h1>
    <p class="subtitle">A passionate frontend developer from India 🇮🇳</p>
    <div class="badges">
      <span class="badge">🎓 B.Tech CSE (AI/ML)</span>
      <span class="badge">🏫 SRM KTR University</span>
      <span class="badge">✍️ Tech Writer</span>
      <span class="badge">📍 India</span>
    </div>
  </div>

  <hr>

  <!-- ABOUT -->
  <div class="section">
    <div class="section-title">About</div>
    <div class="info-list">
      <div class="info-item">
        <span class="icon">🌱</span>
        <span>Currently learning <strong>B.Tech CSE (AI/ML)</strong> at SRM KTR University</span>
      </div>
      <div class="info-item">
        <span class="icon">📝</span>
        <span>I regularly write articles on <a href="https://medium.com/@kirushakkarasu2004" target="_blank">medium.com/@kirushakkarasu2004</a></span>
      </div>
      <div class="info-item">
        <span class="icon">📫</span>
        <span>Reach me at <a href="mailto:kirushakkarasu2004@gmail.com">kirushakkarasu2004@gmail.com</a></span>
      </div>
      <div class="info-item">
        <span class="icon">📄</span>
        <span>Know about my experiences — <a href="https://drive.google.com/file/d/1jz-tc8sejlkxsv9MDGufdxctIjNqUFNu/view?usp=sharing" target="_blank">View Resume</a></span>
      </div>
    </div>
  </div>

  <hr>

  <!-- CONNECT -->
  <div class="section">
    <div class="section-title">Connect with me</div>
    <div class="social-row">
      <a class="social-link" href="https://twitter.com/krishak_arasu" target="_blank" title="Twitter">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg">
      </a>
      <a class="social-link" href="https://linkedin.com/in/kirushak-kt" target="_blank" title="LinkedIn">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg">
      </a>
      <a class="social-link" href="https://instagram.com/kirushak_kt" target="_blank" title="Instagram">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg">
      </a>
      <a class="social-link" href="https://medium.com/@kirushakkarasu2004" target="_blank" title="Medium">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg">
      </a>
      <a class="social-link" href="https://www.hackerrank.com/kirushak" target="_blank" title="HackerRank">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg">
      </a>
      <a class="social-link" href="https://www.leetcode.com/kirushakkarasu_kt" target="_blank" title="LeetCode">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg">
      </a>
      <a class="social-link" href="https://dev.to/@kirushak_kt" target="_blank" title="dev.to">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/devto.svg">
      </a>
      <a class="social-link" href="https://hashnode.com/@kirushak" target="_blank" title="Hashnode">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hashnode.svg">
      </a>
      <a class="social-link" href="https://stackoverflow.com/users/kirushak-kt" target="_blank" title="Stack Overflow">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg">
      </a>
      <a class="social-link" href="https://kaggle.com/kirushakkarasukt" target="_blank" title="Kaggle">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg">
      </a>
    </div>
  </div>

  <hr>

  <!-- TOOLS -->
  <div class="section">
    <div class="section-title">Languages & Tools</div>
    <div class="tools-grid">
      <div class="tool"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">Python</div>
      <div class="tool"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg">C</div>
      <div class="tool"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg">C++</div>
      <div class="tool"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg">HTML5</div>
      <div class="tool"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg">CSS3</div>
      <div class="tool"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg">JavaScript</div>
      <div class="tool"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg">TensorFlow</div>
      <div class="tool"><img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg">Pandas</div>
      <div class="tool"><img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg">OpenCV</div>
      <div class="tool"><img src="https://cdn.worldvectorlogo.com/logos/django.svg" style="filter:invert(0.7)">Django</div>
      <div class="tool"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg">MySQL</div>
      <div class="tool"><img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg">SQLite</div>
      <div class="tool"><img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg">Flutter</div>
      <div class="tool"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swift/swift-original.svg">Swift</div>
      <div class="tool"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg">Linux</div>
      <div class="tool"><img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" style="filter:invert(0.7)">Arduino</div>
    </div>
  </div>

  <hr>

  <!-- GITHUB STATS -->
  <div class="section">
    <div class="section-title">GitHub Stats</div>
    <div class="stats-row">
      <div class="stat-img-card">
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=kirushak&show_icons=true&locale=en&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages">
      </div>
      <div class="stat-img-card">
        <img src="https://github-readme-stats.vercel.app/api?username=kirushak&show_icons=true&locale=en&theme=github_dark&hide_border=true" alt="GitHub Stats">
      </div>
      <div class="stat-img-card full">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=kirushak&theme=github-dark-blue&hide_border=true" alt="GitHub Streak">
      </div>
    </div>
  </div>

  <hr>

  <!-- TROPHIES -->
  <div class="section">
    <div class="section-title">Trophies</div>
    <div style="background:#161b22;border:1px solid #21262d;border-radius:10px;padding:16px;overflow-x:auto;">
      <img src="https://github-profile-trophy.vercel.app/?username=kirushak&theme=darkhub&no-frame=true&margin-w=8" alt="trophies" style="display:block;max-width:100%">
    </div>
  </div>

  <!-- FOOTER -->
  <div class="footer">
    <img src="https://komarev.com/ghpvc/?username=kirushak&label=Profile+views&color=0e75b6&style=flat" alt="views" style="margin-bottom:8px;display:block;margin-inline:auto">
    Made with <span>❤️</span> by Kirushak · <span>github.com/kirushak</span>
  </div>

</div>
</body>
</html>
