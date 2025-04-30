<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <!-- 重要SEO設定 -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>太空國際 X JIB | 官方網站</title>
    <meta name="description" content="太空國際 X JIB 官方入口，提供太空科技研發、國際合作項目與最新動態">
    <meta name="keywords" content="太空國際,JIB,太空科技,國際合作,航天工程">
    <meta name="robots" content="index, follow">
    <!-- 預設開啟Google搜索索引 -->

    <!-- 開放圖譜協議（分享到社群時顯示的資訊） -->
    <meta property="og:title" content="太空國際 X JIB">
    <meta property="og:description" content="探索太空科技與國際合作的新邊界">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://TaiKong-GuoJi-X-JIB.github.io">
    <!-- 替換為你的實際網址 -->

    <style>
        /* 太空主題配色 */
        :root {
            --space-blue: #0a1a2f;
            --star-white: #e6f1ff;
            --planet-orange: #ff7e33;
            --nebula-purple: #8a2be2;
        }
        
        body {
            font-family: 'Segoe UI', 'Microsoft JhengHei', sans-serif;
            background-color: var(--space-blue);
            color: var(--star-white);
            margin: 0;
            line-height: 1.6;
            background-image: 
                radial-gradient(circle at 10% 20%, rgba(138, 43, 226, 0.1) 0%, transparent 20%),
                radial-gradient(circle at 90% 80%, rgba(255, 126, 51, 0.1) 0%, transparent 20%);
        }
        
        header {
            text-align: center;
            padding: 3rem 1rem;
            background: linear-gradient(135deg, var(--space-blue) 0%, #162a47 100%);
            border-bottom: 1px solid rgba(230, 241, 255, 0.1);
        }
        
        h1 {
            font-size: 2.8rem;
            margin: 0;
            background: linear-gradient(90deg, var(--star-white) 45%, var(--planet-orange) 55%);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            letter-spacing: 2px;
        }
        
        h1 span.x-symbol {
            color: var(--planet-orange);
            font-weight: 900;
            padding: 0 0.5rem;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.8;
            margin-top: 1rem;
        }
        
        nav {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 1rem;
            padding: 1.5rem;
            background-color: rgba(10, 26, 47, 0.8);
            backdrop-filter: blur(5px);
        }
        
        nav a {
            color: var(--star-white);
            text-decoration: none;
            padding: 0.5rem 1.2rem;
            border: 1px solid var(--nebula-purple);
            border-radius: 50px;
            transition: all 0.3s ease;
        }
        
        nav a:hover {
            background-color: var(--nebula-purple);
            transform: translateY(-2px);
        }
        
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        
        .mission-card {
            background: rgba(230, 241, 255, 0.05);
            border-radius: 10px;
            padding: 2rem;
            margin-bottom: 2rem;
            border: 1px solid rgba(138, 43, 226, 0.3);
            transition: transform 0.3s ease;
        }
        
        .mission-card:hover {
            transform: translateY(-5px);
            border-color: var(--planet-orange);
        }
        
        footer {
            text-align: center;
            padding: 2rem;
            background-color: rgba(0, 0, 0, 0.2);
            margin-top: 3rem;
        }
        
        /* 響應式設計 */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            nav {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <!-- 導航欄 -->
    <nav>
        <a href="#about">關於我們</a>
        <a href="#projects">太空項目</a>
        <a href="#technology">核心技術</a>
        <a href="#contact">國際合作</a>
    </nav>

    <!-- 主標題區 -->
    <header>
        <h1>太空國際 <span class="x-symbol">✧</span> JIB</h1>
        <p class="subtitle">探索宇宙邊疆 · 連結地球智慧</p>
    </header>

    <!-- 內容區 -->
    <div class="container">
        <section id="about" class="mission-card">
            <h2>關於太空國際 X JIB</h2>
            <p>我們是由國際航天工程師與科學家組成的先鋒團隊，專注於跨國界太空技術研發與應用，推動人類文明邁向星際時代。</p>
        </section>

        <section id="projects" class="mission-card">
            <h2>當前項目</h2>
            <ul>
                <li>「星際橋梁」低軌道衛星網絡</li>
                <li>月球資源探勘計劃 (LREP)</li>
                <li>國際太空站擴建模組</li>
            </ul>
        </section>

        <section id="technology" class="mission-card">
            <h2>核心技術</h2>
            <p>自主研發的量子推進系統、太空材料科學、AI導航控制技術，以及突破性的生命支持系統。</p>
        </section>
    </div>

    <!-- 頁尾 -->
    <footer>
        <p>© 2025 <strong>太空國際 X JIB</strong> 版權所有</p>
        <p>網站更新日期：2025年5月</p>
    </footer>

    <!-- 微數據標記（增強SEO） -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Organization",
      "name": "太空國際 X JIB",
      "url": "https://TaiKong-GuoJi-X-JIB.github.io",
      "logo": "https://TaiKong-GuoJi-X-JIB.github.io/logo.png",
      "description": "國際太空科技研發與合作組織",
      "foundingDate": "2025"
    }
    </script>
</body>
</html>
