<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Rahul Sharma Banner</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #f5f7fb;
    }

    .banner {
      width: 100%;
      height: 260px;
      background: #ffffff;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 30px 60px;
      box-sizing: border-box;
      box-shadow: 0 4px 18px rgba(0, 0, 0, 0.05);
    }

    /* Left side: name + details */
    .banner-left {
      flex: 1.4;
    }

    .name {
      font-size: 34px;
      letter-spacing: 3px;
      font-weight: 700;
      color: #1775d1;
      margin-bottom: 8px;
      text-transform: uppercase;
    }

    .title {
      font-size: 18px;
      color: #333333;
      margin-bottom: 20px;
    }

    .info-item {
      display: flex;
      align-items: center;
      margin: 6px 0;
      color: #555555;
      font-size: 14px;
    }

    .info-icon {
      width: 20px;
      height: 20px;
      border-radius: 50%;
      border: 2px solid #1775d1;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      color: #1775d1;
      font-size: 11px;
      margin-right: 10px;
    }

    a {
      color: #1775d1;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Right side: photo placeholder + shapes */
    .banner-right {
      flex: 1;
      display: flex;
      justify-content: flex-end;
      align-items: center;
      position: relative;
    }

    .photo-circle {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      overflow: hidden;
      border: 6px solid #f0f3ff;
      display: flex;
      align-items: center;
      justify-content: center;
      background: #e2ebff;
      position: relative;
      z-index: 2;
    }

    .photo-circle span {
      font-size: 14px;
      color: #555555;
    }

    .ring {
      position: absolute;
      border-radius: 50%;
      border: 3px solid #f5c85b;
    }

    .ring.r1 {
      width: 190px;
      height: 190px;
      right: 40px;
      z-index: 1;
    }

    .ring.r2 {
      width: 220px;
      height: 220px;
      right: 25px;
      opacity: 0.6;
    }

    /* Simple hexagon-like background shape */
    .hex {
      position: absolute;
      width: 70px;
      height: 70px;
      background: #1775d1;
      clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
      opacity: 0.85;
    }

    .hex.h1 {
      top: 40px;
      left: 40px;
    }

    .hex.h2 {
      bottom: 30px;
      left: 200px;
      background: #0f417b;
    }

    .hex.h3 {
      top: 20px;
      right: 260px;
      background: #0f417b;
    }
  </style>
</head>
<body>
  <div class="banner">
    <!-- Decorative hexagons -->
    <div class="hex h1"></div>
    <div class="hex h2"></div>
    <div class="hex h3"></div>

    <!-- Left content -->
    <div class="banner-left">
      <div class="name">RAHUL SHARMA</div>
      <div class="title">Data Science Enthusiast</div>

      <div class="info-item">
        <div class="info-icon">@</div>
        <a href="mailto:rahulsharmanooty@gmail.com">rahulsharmanooty@gmail.com</a>
      </div>

      <div class="info-item">
        <div class="info-icon">📍</div>
        <span>Ghaziabad, India</span>
      </div>
    </div>

    <!-- Right content (photo placeholder) -->
    <div class="banner-right">
      <div class="ring r1"></div>
      <div class="ring r2"></div>
      <div class="photo-circle">
        <!-- You can replace this span with an <img> tag -->
        <!-- <img src="your-photo.jpg" alt="Rahul Sharma" style="width:100%;height:100%;object-fit:cover;" /> -->
        <span>Your Photo</span>
      </div>
    </div>
  </div>
</body>
</html>

# 💫 About Me:
🔭 I'm currently working on: Building a COVID-19 case tracker using Python to practice data ingestion from an API and create simple time-series plots.<br><br>🤝 I'm looking to collaborate on: Introductory Kaggle competitions, specifically those focused on data cleaning and feature engineering.<br><br>💛 I'm looking for help with: Optimizing my SQL queries, particularly mastering joins and subqueries—any efficient tips are welcome!<br><br>💡 I'm currently learning: The fundamentals of Descriptive Statistics (mean, median, standard deviation) and intermediate Python concepts like object-oriented programming.<br><br>💬 Ask me about: The best way to manage dependencies in Python projects, or my recommendations for documentary films on AI ethics.<br><br>⚡ Fun fact: I can't look at a spreadsheet without immediately checking the number of unique values in every column.<br><br>


## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/ig_user_1509) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/rahul-sharma-86748b395) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/@RK_sharma_3745) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:rahulsharmanooty@gmail.com) 

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=rk3745&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=rk3745&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=rk3745&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=rk3745&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
