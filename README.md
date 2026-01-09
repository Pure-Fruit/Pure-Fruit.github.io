# Pure-Fruit.github.io
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的个人主页</title>
    <link rel="stylesheet" href="style.css">
    <!-- Font Awesome 图标库 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- 导航栏 -->
    <nav class="navbar">
        <div class="nav-brand">我的主页</div>
        <ul class="nav-links">
            <li><a href="#about">关于</a></li>
            <li><a href="#projects">项目</a></li>
            <li><a href="#contact">联系</a></li>
        </ul>
    </nav>

    <!-- 主页横幅 -->
    <header class="hero">
        <h1>你好，我是 [你的名字]</h1>
        <p>这里是一段简短的自我介绍</p>
        
        <!-- 社交媒体图标链接 -->
        <div class="social-icons">
            <a href="https://github.com/你的用户名" target="_blank" title="GitHub">
                <i class="fab fa-github"></i>
            </a>
            <a href="https://linkedin.com/in/你的用户名" target="_blank" title="LinkedIn">
                <i class="fab fa-linkedin"></i>
            </a>
            <a href="mailto:your.email@example.com" title="Email">
                <i class="fas fa-envelope"></i>
            </a>
            <a href="https://twitter.com/你的用户名" target="_blank" title="Twitter">
                <i class="fab fa-twitter"></i>
            </a>
        </div>
    </header>

    <!-- 关于我 -->
    <section id="about" class="section">
        <h2>关于我</h2>
        <p>在这里写一些关于你自己的介绍。可以包括你的背景、兴趣爱好、专业技能等。</p>
        <p>支持多段落文本，你可以自由添加内容。</p>
    </section>

    <!-- 项目展示 -->
    <section id="projects" class="section">
        <h2>我的项目</h2>
        <div class="project-grid">
            <!-- 项目卡片 1 -->
            <div class="project-card">
                <h3>项目名称 1</h3>
                <p>项目简介描述</p>
                <a href="https://github.com/你的仓库链接" target="_blank" class="btn">
                    <i class="fab fa-github"></i> 查看代码
                </a>
            </div>
            
            <!-- 项目卡片 2 -->
            <div class="project-card">
                <h3>项目名称 2</h3>
                <p>项目简介描述</p>
                <a href="https://项目演示链接" target="_blank" class="btn">
                    <i class="fas fa-external-link-alt"></i> 在线演示
                </a>
            </div>
            
            <!-- 项目卡片 3 -->
            <div class="project-card">
                <h3>项目名称 3</h3>
                <p>项目简介描述</p>
                <a href="#" class="btn">
                    <i class="fas fa-file-pdf"></i> 查看论文
                </a>
            </div>
        </div>
    </section>

    <!-- 联系方式 -->
    <section id="contact" class="section">
        <h2>联系我</h2>
        <p>如果你想联系我，可以通过以下方式：</p>
        <ul class="contact-list">
            <li><i class="fas fa-envelope"></i> Email: <a href="mailto:your.email@example.com">your.email@example.com</a></li>
            <li><i class="fab fa-github"></i> GitHub: <a href="https://github.com/你的用户名" target="_blank">github.com/你的用户名</a></li>
        </ul>
    </section>

    <!-- 页脚 -->
    <footer>
        <p>&copy; 2026 [你的名字]. All rights reserved.</p>
    </footer>
</body>
</html>
