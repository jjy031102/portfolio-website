<template>
  <div class="min-h-screen bg-gray-50 text-gray-800">
    <!-- 导航栏 -->
    <nav class="fixed w-full bg-white shadow-md z-10">
      <div class="container mx-auto px-4 py-4 flex justify-between items-center">
        <h1 class="text-xl font-bold text-blue-600">我的作品集</h1>
        <div class="space-x-6">
          <a href="#home" class="hover:text-blue-500 transition">首页</a>
          <a href="#project" class="hover:text-blue-500 transition">作品</a>
          <a href="#skill" class="hover:text-blue-500 transition">技能</a>
          <a href="#contact" class="hover:text-blue-500 transition">联系我</a>
        </div>
      </div>
    </nav>

    <!-- 首页区域 -->
    <section id="home" class="pt-32 pb-20 container mx-auto px-4">
      <div class="flex flex-col md:flex-row items-center justify-center gap-10">
        <div class="w-40 h-40 rounded-full bg-blue-200 flex items-center justify-center text-5xl">
          👨‍💻
        </div>
        <div>
          <h2 class="text-3xl font-bold mb-4">你好，我是前端开发应届生</h2>
          <p class="text-gray-600 mb-6 max-w-lg">
            计算机应用技术专业大专毕业生，熟练使用 HTML/CSS/JavaScript/Vue3，同时掌握 PHP + MySQL 基础全栈开发。
            热爱编程，积极学习，希望寻找前端相关岗位。
          </p>
          <button class="bg-blue-600 text-white px-6 py-2 rounded-lg hover:bg-blue-700 transition">
            下载简历
          </button>
        </div>
      </div>
    </section>

    <!-- 项目作品 -->
    <section id="project" class="py-20 bg-white">
      <div class="container mx-auto px-4">
        <h2 class="text-2xl font-bold text-center mb-12">项目作品</h2>
        <div class="grid md:grid-cols-3 gap-8">
          <!-- 项目卡片1 -->
          <div class="shadow-lg rounded-xl overflow-hidden hover:scale-105 transition">
            <div class="h-40 bg-blue-100 flex items-center justify-center">项目截图</div>
            <div class="p-4">
              <h3 class="font-bold text-lg mb-2">学生管理系统</h3>
              <p class="text-sm text-gray-500 mb-3">技术：PHP + MySQL + HTML + CSS</p>
              <p class="text-sm">课程毕设，实现学生信息增删改查、数据管理功能</p>
              <a href="https://github.com/你的账号" target="_blank" class="inline-block mt-4 text-blue-600">查看源码 →</a>
            </div>
          </div>
          <!-- 项目卡片2 -->
          <div class="shadow-lg rounded-xl overflow-hidden hover:scale-105 transition">
            <div class="h-40 bg-green-100 flex items-center justify-center">项目截图</div>
            <div class="p-4">
              <h3 class="font-bold text-lg mb-2">Vue3 简易后台</h3>
              <p class="text-sm text-gray-500 mb-3">技术：Vue3 + Vite + Element Plus</p>
              <p class="text-sm">包含登录、数据面板、用户管理等基础后台功能</p>
              <a href="https://github.com/你的账号" target="_blank" class="inline-block mt-4 text-blue-600">查看源码 →</a>
            </div>
          </div>
          <!-- 项目卡片3 -->
          <div class="shadow-lg rounded-xl overflow-hidden hover:scale-105 transition">
            <div class="h-40 bg-orange-100 flex items-center justify-center">项目截图</div>
            <div class="p-4">
              <h3 class="font-bold text-lg mb-2">前端特效合集</h3>
              <p class="text-sm text-gray-500 mb-3">技术：原生 JS + CSS3</p>
              <p class="text-sm">轮播、动画、表单验证等常用前端效果汇总</p>
              <a href="https://github.com/你的账号" target="_blank" class="inline-block mt-4 text-blue-600">查看源码 →</a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- 技能栈 -->
    <section id="skill" class="py-20 container mx-auto px-4">
      <h2 class="text-2xl font-bold text-center mb-12">技能掌握</h2>
      <div class="max-w-2xl mx-auto space-y-6">
        <div>
          <div class="flex justify-between mb-1">
            <span>HTML / CSS</span>
            <span>90%</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full h-2">
            <div class="bg-blue-600 h-2 rounded-full" style="width: 90%"></div>
          </div>
        </div>
        <div>
          <div class="flex justify-between mb-1">
            <span>JavaScript</span>
            <span>85%</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full h-2">
            <div class="bg-blue-600 h-2 rounded-full" style="width: 85%"></div>
          </div>
        </div>
        <div>
          <div class="flex justify-between mb-1">
            <span>Vue3</span>
            <span>80%</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full h-2">
            <div class="bg-blue-600 h-2 rounded-full" style="width: 80%"></div>
          </div>
        </div>
        <div>
          <div class="flex justify-between mb-1">
            <span>PHP + MySQL</span>
            <span>70%</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full h-2">
            <div class="bg-blue-600 h-2 rounded-full" style="width: 70%"></div>
          </div>
        </div>
      </div>
    </section>

    <!-- 联系我 -->
    <section id="contact" class="py-20 bg-white">
      <div class="container mx-auto px-4 text-center">
        <h2 class="text-2xl font-bold mb-6">联系我</h2>
        <p class="mb-2">GitHub：<a href="https://github.com/你的账号" class="text-blue-600">github.com/你的账号</a></p>
        <p class="mb-2">求职意向：前端开发 / 前端实习生</p>
      </div>
    </section>

    <!-- 页脚 -->
    <footer class="bg-gray-800 text-white py-6 text-center">
      <p>© 2026 前端应届生作品集 | All Rights Reserved</p>
    </footer>
  </div>
</template>

<script setup>
// 无需额外逻辑，纯静态展示
</script>