---
layout: page
permalink: /repositories/  # 保持原路径，无需修改（若想改路径可改这里，比如/特长/）
title: 特长展示            # 页面标题改为“个人特长”
description: 我擅长用「摄影」定格时光，用「剪辑」编织故事；也热爱在「运动」中挥洒汗水，于羽毛球的跳跃中追逐风的方向，在排球的协作里感受团队的力量。动静之间，皆是热爱。
nav: true                  # 保留导航栏显示
nav_order: 3               # 保留原排序位置
---

<!-- 页面主标题 -->
<h1 style="margin-bottom: 2rem;">Renee的特长</h1>

<!-- 1. 摄影特长板块（修改为4张，两两排列） -->
## 📷 摄影
<p style="font-size: 1.1rem; line-height: 1.6;">
  热爱风光、人像摄影，擅长捕捉生活中的细节与氛围感，常用设备为索尼A7M4，擅长后期调色（Lightroom/Photoshop）。
</p>

<!-- 摄影图片展示（4张，两两排列：col-md-6 实现2列布局） -->
<div class="row" style="margin: 2rem 0; gap: 1.5rem;">
  <!-- 第一行第一张 -->
  <div class="col-md-6">
    <img src="{{ 'assets/img/摄影1.jpg' | relative_url }}" alt="摄影作品1" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);" loading="lazy">
    <p style="text-align: center; margin-top: 0.5rem; color: #666;">风光摄影 - 南京玄武湖</p>
  </div>
  <!-- 第一行第二张 -->
  <div class="col-md-6">
    <img src="{{ 'assets/img/摄影2.jpg' | relative_url }}" alt="摄影作品2" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);" loading="lazy">
    <p style="text-align: center; margin-top: 0.5rem; color: #666;">动态摄影 - 游乐园日常</p>
  </div>
  <!-- 第二行第一张 -->
  <div class="col-md-6" style="margin-top: 1.5rem;">
    <img src="{{ 'assets/img/摄影3.jpg' | relative_url }}" alt="摄影作品3" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);" loading="lazy">
    <p style="text-align: center; margin-top: 0.5rem; color: #666;">静物摄影 - 天安门</p>
  </div>
  <!-- 第二行第二张 -->
  <div class="col-md-6" style="margin-top: 1.5rem;">
    <img src="{{ 'assets/img/摄影4.jpg' | relative_url }}" alt="摄影作品4" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);" loading="lazy">
    <p style="text-align: center; margin-top: 0.5rem; color: #666;">人物摄影 - 幸福</p>
  </div>
</div>

--- <!-- 分割线 -->

<!-- 2. 剪辑特长板块（小红书视频：封面+跳转链接） -->
## ✂️ 剪辑
<p style="font-size: 1.1rem; line-height: 1.6;">
  熟练使用Premiere Pro、剪映等工具，擅长短视频、vlog、纪录片剪辑，风格偏向自然流畅，注重节奏与画面衔接。
</p>

<!-- 小红书视频展示：封面图+点击跳转链接 -->
<div style="margin: 2rem 0; text-align: center;">
  <!-- 小红书视频封面（建议截图视频封面上传，提升美观度） -->
  <a href="http://xhslink.com/o/5tHZZgtsVTZ" target="_blank" rel="noopener noreferrer" style="text-decoration: none;">
    <img src="{{ 'assets/img/小红书剪辑作品封面.jpg' | relative_url }}" alt="小红书剪辑作品封面" 
         style="width: 100%; max-width: 800px; border-radius: 8px; box-shadow: 0 2px 12px rgba(0,0,0,0.15); cursor: pointer;">
    <!-- 悬浮提示文字 -->
    <div style="margin-top: 1rem; font-size: 1.1rem; color: #ff2442; font-weight: 500;">
      👉 点击图片跳转小红书查看剪辑作品：In南京 | 在小西湖多巴胺一下！
    </div>
  </a>
  <p style="margin-top: 0.8rem; color: #666;">剪辑作品 - 南京小西湖街区vlog</p>
</div>

--- <!-- 分割线 -->

<!-- 3. 运动特长板块（羽毛球+排球） -->
## 🏃 运动（羽毛球/排球）
<p style="font-size: 1.1rem; line-height: 1.6;">
  长期参与羽毛球、排球运动，羽毛球主打双打（混双/女双），排球司职接应，曾参与校级联赛并获得团体奖项。
</p>

<!-- 运动图片展示 -->
<div class="row" style="margin: 2rem 0; gap: 1rem;">
  <!-- 羽毛球图片 -->
  <div class="col-md-6">
    <img src="{{ 'assets/img/运动2.jpg' | relative_url }}" alt="羽毛球" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);" loading="lazy">
    <p style="text-align: center; margin-top: 0.5rem; color: #666;">羽毛球院赛一等奖</p>
  </div>
  <!-- 排球图片 -->
  <div class="col-md-6">
    <img src="{{ 'assets/img/运动1.jpg' | relative_url }}" alt="排球" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);" loading="lazy">
    <p style="text-align: center; margin-top: 0.5rem; color: #666;">排球校赛荣誉</p>
  </div>
</div>
