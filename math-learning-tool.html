<!DOCTYPE html>
<html lang="zh-CN">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>趣味学科题生成器</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primary: '#4F46E5',
            secondary: '#EC4899',
            accent: '#10B981',
            neutral: '#F3F4F6',
            dark: '#1F2937',
            // 新增学科颜色
            chinese: '#EF4444',
            english: '#F59E0B',
            science: '#3B82F6',
            history: '#8B5CF6',
            geography: '#14B8A6',
            music: '#EC4899',
            art: '#F97316',
            pe: '#84CC16'
          },
          fontFamily: {
            comic: ['Comic Sans MS', 'cursive', 'sans-serif'],
            inter: ['Inter', 'sans-serif']
          },
        },
      }
    }
  </script>
  <style type="text/tailwindcss">
    @layer utilities {
      .content-auto {
        content-visibility: auto;
      }
      .math-card {
        @apply bg-white rounded-xl shadow-lg p-6 transition-all duration-300 hover:shadow-xl border-2 border-transparent hover:border-primary/30;
      }
      .btn-primary {
        @apply bg-primary hover:bg-primary/90 text-white font-bold py-3 px-6 rounded-lg transition-all duration-300 transform hover:scale-105 active:scale-95 shadow-md hover:shadow-lg;
      }
      .btn-secondary {
        @apply bg-secondary hover:bg-secondary/90 text-white font-bold py-3 px-6 rounded-lg transition-all duration-300 transform hover:scale-105 active:scale-95 shadow-md hover:shadow-lg;
      }
      .btn-accent {
        @apply bg-accent hover:bg-accent/90 text-white font-bold py-3 px-6 rounded-lg transition-all duration-300 transform hover:scale-105 active:scale-95 shadow-md hover:shadow-lg;
      }
      .input-field {
        @apply border-2 border-gray-300 rounded-lg px-4 py-3 w-full focus:outline-none focus:border-primary transition-all duration-300;
      }
      .option-card {
        @apply border-2 border-gray-200 rounded-lg p-4 cursor-pointer transition-all duration-300 hover:border-primary hover:bg-primary/5;
      }
      .option-card.active {
        @apply border-primary bg-primary/10;
      }
      .animated-bg {
        background-size: 400% 400%;
        animation: gradient 15s ease infinite;
      }
      @keyframes gradient {
        0% {
          background-position: 0% 50%;
        }
        50% {
          background-position: 100% 50%;
        }
        100% {
          background-position: 0% 50%;
        }
      }
      .bounce-in {
        animation: bounce-in 0.6s ease-out;
      }
      @keyframes bounce-in {
        0% {
          transform: scale(0.8);
          opacity: 0;
        }
        70% {
          transform: scale(1.05);
          opacity: 1;
        }
        100% {
          transform: scale(1);
        }
      }
      .float {
        animation: float 3s ease-in-out infinite;
      }
      @keyframes float {
        0% {
          transform: translateY(0px);
        }
        50% {
          transform: translateY(-10px);
        }
        100% {
          transform: translateY(0px);
        }
      }
      /* 新增学科图标样式 */
      .subject-icon {
        @apply w-12 h-12 rounded-full flex items-center justify-center text-white text-xl mb-3;
      }
      .chinese-icon {
        @apply subject-icon bg-chinese/80;
      }
      .math-icon {
        @apply subject-icon bg-primary/80;
      }
      .english-icon {
        @apply subject-icon bg-english/80;
      }
      .science-icon {
        @apply subject-icon bg-science/80;
      }
      .history-icon {
        @apply subject-icon bg-history/80;
      }
      .geography-icon {
        @apply subject-icon bg-geography/80;
      }
      .music-icon {
        @apply subject-icon bg-music/80;
      }
      .art-icon {
        @apply subject-icon bg-art/80;
      }
      .pe-icon {
        @apply subject-icon bg-pe/80;
      }
    }
  </style>
</head>

<body class="bg-gradient-to-br from-indigo-50 to-purple-50 min-h-screen font-inter text-dark">
  <!-- 导航栏 -->
  <nav class="bg-white shadow-md fixed w-full z-50 transition-all duration-300" id="navbar">
    <div class="container mx-auto px-4 py-3 flex justify-between items-center">
      <div class="flex items-center space-x-2">
        <i class="fa fa-book text-primary text-2xl float"></i>
        <h1 class="text-xl md:text-2xl font-bold text-primary">趣味学科题生成器</h1>
      </div>
      <div class="hidden md:flex items-center space-x-6">
        <a href="#home" class="text-gray-700 hover:text-primary transition-colors duration-300">首页</a>
        <a href="#settings" class="text-gray-700 hover:text-primary transition-colors duration-300">题目设置</a>
        <a href="#generated-problems" class="text-gray-700 hover:text-primary transition-colors duration-300">生成题目</a>
        <a href="#about" class="text-gray-700 hover:text-primary transition-colors duration-300">关于我们</a>
      </div>
      <button class="md:hidden text-gray-700 focus:outline-none" id="menu-toggle">
        <i class="fa fa-bars text-xl"></i>
      </button>
    </div>
    <!-- 移动端菜单 -->
    <div class="md:hidden hidden bg-white w-full border-t" id="mobile-menu">
      <div class="container mx-auto px-4 py-2 flex flex-col space-y-3">
        <a href="#home" class="text-gray-700 hover:text-primary py-2 transition-colors duration-300">首页</a>
        <a href="#settings" class="text-gray-700 hover:text-primary py-2 transition-colors duration-300">题目设置</a>
        <a href="#generated-problems" class="text-gray-700 hover:text-primary py-2 transition-colors duration-300">生成题目</a>
        <a href="#about" class="text-gray-700 hover:text-primary py-2 transition-colors duration-300">关于我们</a>
      </div>
    </div>
  </nav>

  <!-- 主要内容 -->
  <main class="container mx-auto px-4 pt-24 pb-16">
    <!-- 欢迎部分 -->
    <section id="home" class="mb-16">
      <div class="flex flex-col md:flex-row items-center gap-8">
        <div class="w-full md:w-1/2 bounce-in">
          <h2 class="text-[clamp(2rem,5vw,3.5rem)] font-bold text-dark leading-tight mb-4">
            让学习变得<br><span class="text-primary">有趣</span>
          </h2>
          <p class="text-gray-600 text-lg mb-8">
            为幼小衔接及小学低年级学生设计的趣味学科题生成工具，让孩子在游戏中爱上学习！
          </p>
          <div class="flex flex-wrap gap-4">
            <button id="generate-btn" class="btn-primary flex items-center gap-2">
              <i class="fa fa-refresh"></i> 生成题目
            </button>
            <button id="download-btn" class="btn-secondary flex items-center gap-2">
              <i class="fa fa-download"></i> 下载题库
            </button>
          </div>
        </div>
        <div class="w-full md:w-1/2 relative">
          <div class="bg-white rounded-2xl shadow-xl p-8 relative z-10 math-card">
            <div class="absolute -top-4 -right-4 bg-primary text-white rounded-full w-12 h-12 flex items-center justify-center font-bold text-xl">
              1
            </div>
            <div class="flex items-center justify-center mb-6">
              <div class="math-icon">
                <i class="fa fa-calculator"></i>
              </div>
            </div>
            <div class="text-center mb-6">
              <h3 class="text-2xl font-bold mb-2">24 + 18 = ?</h3>
              <p class="text-gray-500">加法题 - 一年级</p>
            </div>
            <div class="grid grid-cols-2 gap-4 mb-6">
              <div class="option-card">
                <p class="text-center text-lg font-medium">42</p>
              </div>
              <div class="option-card">
                <p class="text-center text-lg font-medium">32</p>
              </div>
              <div class="option-card">
                <p class="text-center text-lg font-medium">41</p>
              </div>
              <div class="option-card">
                <p class="text-center text-lg font-medium">31</p>
              </div>
            </div>
            <div class="flex justify-between items-center">
              <div class="flex items-center gap-2">
                <i class="fa fa-clock-o text-gray-400"></i>
                <span class="text-gray-500">00:30</span>
              </div>
              <button class="btn-accent">
                提交答案
              </button>
            </div>
          </div>
          <!-- 装饰元素 -->
          <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-full h-full bg-primary/20 rounded-2xl transform rotate-3 scale-105 z-0"></div>
          <div class="absolute -bottom-6 -right-6 w-24 h-24 bg-secondary/20 rounded-full z-0 float"></div>
          <div class="absolute -top-6 -left-6 w-16 h-16 bg-accent/20 rounded-full z-0 float" style="animation-delay: 1s"></div>
        </div>
      </div>
    </section>

    <!-- 学科选择部分 -->
    <section id="subjects" class="mb-16">
      <div class="bg-white rounded-2xl shadow-lg p-8 math-card">
        <h2 class="text-2xl font-bold mb-6 flex items-center">
          <i class="fa fa-th text-primary mr-2"></i> 选择学科
        </h2>

        <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-6">
          <div class="text-center p-4 hover:bg-primary/5 rounded-lg transition-all duration-300 cursor-pointer subject-card"
            data-subject="math">
            <div class="math-icon mx-auto">
              <i class="fa fa-calculator"></i>
            </div>
            <h3 class="font-semibold mt-2">数学</h3>
          </div>
          <div class="text-center p-4 hover:bg-chinese/5 rounded-lg transition-all duration-300 cursor-pointer subject-card"
            data-subject="chinese">
            <div class="chinese-icon mx-auto">
              <i class="fa fa-book"></i>
            </div>
            <h3 class="font-semibold mt-2">语文</h3>
          </div>
          <div class="text-center p-4 hover:bg-english/5 rounded-lg transition-all duration-300 cursor-pointer subject-card"
            data-subject="english">
            <div class="english-icon mx-auto">
              <i class="fa fa-language"></i>
            </div>
            <h3 class="font-semibold mt-2">英语</h3>
          </div>
          <div class="text-center p-4 hover:bg-science/5 rounded-lg transition-all duration-300 cursor-pointer subject-card"
            data-subject="science">
            <div class="science-icon mx-auto">
              <i class="fa fa-flask"></i>
            </div>
            <h3 class="font-semibold mt-2">科学</h3>
          </div>
          <div class="text-center p-4 hover:bg-history/5 rounded-lg transition-all duration-300 cursor-pointer subject-card"
            data-subject="history">
            <div class="history-icon mx-auto">
              <i class="fa fa-university"></i>
            </div>
            <h3 class="font-semibold mt-2">历史</h3>
          </div>
        </div>
      </div>
    </section>

    <!-- 题目设置部分 -->
    <section id="settings" class="mb-16">
      <div class="bg-white rounded-2xl shadow-lg p-8 math-card">
        <h2 class="text-2xl font-bold mb-6 flex items-center">
          <i class="fa fa-cog text-primary mr-2"></i> 题目设置
        </h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <div>
            <h3 class="text-lg font-semibold mb-4">难度级别</h3>
            <div class="grid grid-cols-2 md:grid-cols-3 gap-4">
              <div class="option-card difficulty-card" data-level="kindergarten">
                <div class="flex items-center gap-3">
                  <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary">
                    <i class="fa fa-child"></i>
                  </div>
                  <div>
                    <h4 class="font-medium">幼小衔接</h4>
                    <p class="text-sm text-gray-500">基础认知</p>
                  </div>
                </div>
              </div>
              <div class="option-card difficulty-card" data-level="grade1">
                <div class="flex items-center gap-3">
                  <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary">
                    <i class="fa fa-graduation-cap"></i>
                  </div>
                  <div>
                    <h4 class="font-medium">一年级</h4>
                    <p class="text-sm text-gray-500">初级知识</p>
                  </div>
                </div>
              </div>
              <div class="option-card difficulty-card" data-level="grade2">
                <div class="flex items-center gap-3">
                  <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary">
                    <i class="fa fa-book"></i>
                  </div>
                  <div>
                    <h4 class="font-medium">二年级</h4>
                    <p class="text-sm text-gray-500">基础应用</p>
                  </div>
                </div>
              </div>
              <div class="option-card difficulty-card" data-level="grade3">
                <div class="flex items-center gap-3">
                  <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary">
                    <i class="fa fa-calculator"></i>
                  </div>
                  <div>
                    <h4 class="font-medium">三年级</h4>
                    <p class="text-sm text-gray-500">中级应用</p>
                  </div>
                </div>
              </div>
              <div class="option-card difficulty-card" data-level="grade4">
                <div class="flex items-center gap-3">
                  <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary">
                    <i class="fa fa-line-chart"></i>
                  </div>
                  <div>
                    <h4 class="font-medium">四年级</h4>
                    <p class="text-sm text-gray-500">中级进阶</p>
                  </div>
                </div>
              </div>
              <div class="option-card difficulty-card" data-level="grade5">
                <div class="flex items-center gap-3">
                  <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary">
                    <i class="fa fa-cubes"></i>
                  </div>
                  <div>
                    <h4 class="font-medium">五年级</h4>
                    <p class="text-sm text-gray-500">高级应用</p>
                  </div>
                </div>
              </div>
              <div class="option-card difficulty-card" data-level="grade6">
                <div class="flex items-center gap-3">
                  <div class="w-10 h-10 rounded-full bg-primary/10 flex items-center justify-center text-primary">
                    <i class="fa fa-flask"></i>
                  </div>
                  <div>
                    <h4 class="font-medium">六年级</h4>
                    <p class="text-sm text-gray-500">小学毕业</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div id="subject-specific-settings">
            <h3 class="text-lg font-semibold mb-4">题目类型</h3>
            <div class="space-y-4">
              <!-- 数学题目类型 -->
              <div id="math-types" class="space-y-4">
                <div class="flex items-center gap-3 p-4 border-2 border-gray-200 rounded-lg cursor-pointer hover:border-primary hover:bg-primary/5 transition-all duration-300">
                  <input type="checkbox" id="math-add" class="w-5 h-5 accent-primary" checked="">
                  <label for="math-add" class="font-medium">加法题</label>
                </div>
                <div class="flex items-center gap-3 p-4 border-2 border-gray-200 rounded-lg cursor-pointer hover:border-primary hover:bg-primary/5 transition-all duration-300">
                  <input type="checkbox" id="math-subtract" class="w-5 h-5 accent-primary" checked="">
                  <label for="math-subtract" class="font-medium">减法题</label>
                </div>
                <div class="flex items-center gap-3 p-4 border-2 border-gray-200 rounded-lg cursor-pointer hover:border-primary hover:bg-primary/5 transition-all duration-300">
                  <input type="checkbox" id="math-multiply" class="w-5 h-5 accent-primary">
                  <label for="math-multiply" class="font-medium">乘法题</label>
                </div>
                <div class="flex items-center gap-3 p-4 border-2 border-gray-200 rounded-lg cursor-pointer hover:border-primary hover:bg-primary/5 transition-all duration-300">
                  <input type="checkbox" id="math-divide" class="w-5 h-5 accent-primary">
                  <label for="math-divide" class="font-medium">除法题</label>
                </div>
                <div class="flex items-center gap-3 p-4 border-2 border-gray-200 rounded-lg cursor-pointer hover:border-primary hover:bg-primary/5 transition-all duration-300">
                  <input type="checkbox" id="math-fraction" class="w-5 h-5 accent-primary">
                  <label for="math-fraction" class="font-medium">分数运算</label>
                </div>
                <div class="flex items-center gap-3 p-4 border-2 border-gray-200 rounded-lg cursor-pointer hover:border-primary hover:bg-primary/5 transition-all duration-300">
                  <input type="checkbox" id="math-decimal" class="w-5 h-5 accent-primary">
                  <label for="math-decimal" class="font-medium">小数运算</label>
                </div>
                <div class="flex items-center gap-3 p-4 border-2 border-gray-200 rounded-lg cursor-pointer hover:border-primary hover:bg-primary/5 transition-all duration-300">
                  <input type="checkbox" id="math-geometry" class="w-5 h-5 accent-primary">
                  <label for="math-geometry" class="font-medium">几何问题</label>
                </div>
              </div>

              <!-- 语文题目类型 -->
              <div id="chinese-types" class="space-y-4 hidden">
                <div class="flex items-center gap-3 p-4 border-2 border-gray-200 rounded-lg cursor-pointer hover:border-chinese hover:bg-chinese/5 transition-all duration-300">
                  <input type="checkbox" id="chinese-character" class="w-5 h-5 accent-chinese" checked="">
                  <label for="chinese-character" class="font-medium">汉字书写</label>
                </div>
                <div class="flex items-center gap-3 p-4 border-2 border-gray-200 rounded-lg cursor-pointer hover:border-chinese hover:bg-chinese/5 transition-all duration-300">
                  <input type="checkbox" id="chinese-vocabulary" class="w-5 h-5 accent-chinese" checked="">
                  <label for="chinese-vocabulary" class="font-medium">词语辨析</label>
                </div>
                <div class="flex items-center gap-3 p-4 border-2 border-gray-200 rounded-lg cursor-pointer hover:border-chinese hover:bg-chinese/5 transition-all duration-300">
                  <input type="checkbox" id="chinese-sentence" class="w-5 h-5 accent-chinese" checked="">
                  <label for="chinese-sentence" class="font-medium">句子排序</label>
                </div>
                <div class="flex items-center gap-3 p-4 border-2 border-gray-200 rounded-lg cursor-pointer hover:border-chinese hover:bg-chinese/5 transition-all duration-300">
                  <input type="checkbox" id="chinese-composition" class="w-5 h-5 accent-chinese">
                  <label for="chinese-composition" class="font-medium">作文写作</label>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>

  <script>
    // 移动端菜单切换
    const menuToggle = document.getElementById('menu-toggle');
    const mobileMenu = document.getElementById('mobile-menu');

    menuToggle.addEventListener('click', function () {
      mobileMenu.classList.toggle('hidden');
    });

    // 答案选项点击
    const optionCards = document.querySelectorAll('.option-card');
    optionCards.forEach(function (card) {
      card.addEventListener('click', function () {
        optionCards.forEach(function (c) {
          c.classList.remove('active');
        });
        this.classList.add('active');
      });
    });

    // 生成题目按钮点击
    const generateBtn = document.getElementById('generate-btn');
    generateBtn.addEventListener('click', function () {
      alert('正在生成题目，请稍候...');
    });

    // 下载题库按钮点击
    const downloadBtn = document.getElementById('download-btn');
    downloadBtn.addEventListener('click', function () {
      alert('开始下载题库...');
    });

    // 导航栏滚动样式变化
    window.addEventListener('scroll', function () {
      const navbar = document.getElementById('navbar');
      if (window.scrollY > 50) {
        navbar.classList.add('bg-opacity-90');
      } else {
        navbar.classList.remove('bg-opacity-90');
      }
    });
  </script>
</body>

</html>
