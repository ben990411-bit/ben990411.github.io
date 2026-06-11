/* --- 基礎設定 --- */
:root {
  --primary-color: #00d4ff;    /* 霓虹藍：代表科技與遊戲感 */
  --accent-color: #ff007a;     /* 霓虹粉：用於強調重點 */
  --bg-dark: #0b0e14;          /* 深黑色背景 */
  --card-bg: #1a1f26;          /* 卡片深灰色 */
  --text-color: #e0e6ed;       /* 淺灰色文字 */
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Microsoft JhengHei", "PingFang TC", sans-serif;
}

body {
  background-color: var(--bg-dark);
  color: var(--text-color);
  line-height: 1.6;
  scroll-behavior: smooth; /* 點選導覽列時平滑滾動 */
}

/* --- 導覽列美化 --- */
nav {
  background: rgba(11, 14, 20, 0.95);
  padding: 15px 5%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: sticky;
  top: 0;
  z-index: 1000;
  border-bottom: 2px solid var(--primary-color);
}

nav .logo {
  font-size: 1.5rem;
  font-weight: bold;
  color: var(--primary-color);
  text-shadow: 0 0 10px var(--primary-color);
}

nav ul {
  display: flex;
  list-style: none;
}

nav ul li { margin-left: 20px; }

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
  transition: 0.3s;
}

nav ul li a:hover {
  color: var(--primary-color);
}

/* --- 主視覺區塊 (Header) --- */
header {
  height: 60vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
              url('https://images.unsplash.com/photo-1542751371-adc38448a05e?auto=format&fit=crop&w=1200&q=80');
  background-size: cover;
  background-position: center;
}

header h1 {
  font-size: 3.5rem;
  color: #fff;
  margin-bottom: 15px;
  letter-spacing: 3px;
}

header p {
  font-size: 1.2rem;
  color: var(--primary-color);
  max-width: 600px;
}

/* --- 內容容器與區塊標題 --- */
.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 60px 20px;
}

.section-title {
  text-align: center;
  font-size: 2.2rem;
  margin-bottom: 40px;
  color: #fff;
  position: relative;
}

.section-title::after {
  content: "";
  display: block;
  width: 60px;
  height: 4px;
  background: var(--primary-color);
  margin: 10px auto;
}

/* --- 遊戲種類卡片排版 --- */
.game-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 25px;
}

.game-card {
  background: var(--card-bg);
  padding: 30px;
  border-radius: 15px;
  text-align: center;
  transition: 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  border: 1px solid rgba(255,255,255,0.05);
}

.game-card:hover {
  transform: translateY(-10px);
  border-color: var(--primary-color);
  box-shadow: 0 10px 30px rgba(0, 212, 255, 0.2);
}

.game-card .icon {
  font-size: 3rem;
  margin-bottom: 15px;
  display: block;
}

.game-card h3 {
  color: #fff;
  margin-bottom: 10px;
}

.keyword-tag {
  display: inline-block;
  margin-top: 15px;
  background: rgba(0, 212, 255, 0.1);
  color: var(--primary-color);
  padding: 4px 12px;
  border-radius: 20px;
  font-size: 0.85rem;
}

/* --- 作者與下載區塊 --- */
.info-box {
  background: linear-gradient(135deg, #1a1f26 0%, #0b0e14 100%);
  padding: 40px;
  border-radius: 15px;
  border-left: 5px solid var(--accent-color);
  margin-bottom: 40px;
}

.info-box h3 {
  margin-bottom: 15px;
  color: var(--accent-color);
}

/* --- 頁尾與聯絡資訊 --- */
footer {
  text-align: center;
  padding: 50px 20px;
  background-color: #05070a;
  color: #666;
  border-top: 1px solid #222;
}

footer .contact {
  color: var(--text-color);
  margin-bottom: 10px;
}

footer .seo-tags {
  font-size: 0.8rem;
  margin-top: 10px;
}
