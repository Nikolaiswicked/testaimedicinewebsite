---
title: 全部风险评估工具
author: Nikola
date: '2023-07-15'
slug: test-risk-tool
categories:
  - features
tags:
  - editor
weight: 1
resImgTeaser: ~
icon: ~
toc: no
description: ~
---

<style>
/* 自定义按钮样式 */
.custom-button {
  font-size: 16px; /* 调整字体大小 */
  font-weight: bold; /* 加粗字体 */
  display: flex; /* 使用弹性布局 */
  flex-direction: column; /* 设置垂直布局 */
  align-items: center; /* 居中对齐 */
  margin-bottom: 10px; /* 按钮之间添加一些间距 */
  position: relative; /* 使用相对定位 */
  color: #fff; /* 设置按钮文字颜色为白色 */
  padding: 10px 20px; /* 设置按钮内边距 */
  border: none; /* 去掉按钮边框 */
  border-radius: 5px; /* 设置按钮圆角 */
  text-decoration: none; /* 去掉文字下划线 */
}

/* 在按钮右侧添加文字 */
.custom-button::after {
  content: attr(data-text); /* 使用 data-text 属性作为文字内容 */
  font-size: 12px; /* 调整文字大小 */
  margin-left: 10px; /* 文字与按钮的间距 */
}

/* 对应不同按钮的文字内容 */
.custom-button[data-text="tool1"]::after {
  content: "该工具能够实现AKI的预测"; /* 修改按钮1的文字内容 */
}

.custom-button[data-text="tool2"]::after {
  content: "该工具能够实现肥胖的预测"; /* 修改按钮2的文字内容 */
}

.custom-button[data-text="tool3"]::after {
  content: "该工具能够实现糖尿病的预测"; /* 修改按钮的文字内容 */
}

.custom-button[data-text="tool4"]::after {
  content: "该工具能够实现耳聋的预测"; /* 修改按钮2的文字内容 */
}

.custom-button[data-text="tool5"]::after {
  content: "该工具能够实现脑卒中的预测"; /* 修改按钮2的文字内容 */
}

.custom-button[data-text="tool6"]::after {
  content: "该工具能够实现中风的预测"; /* 修改按钮2的文字内容 */
}
</style>

<!-- AKI风险评估工具按钮 -->
<a href=" https://nikolalu.shinyapps.io/test-predict-web/" target="_blank" class="custom-button" data-text="tool1">
  <button>AKI风险评估工具</button>
</a>

<!-- 肥胖风险评估工具按钮 -->
<a href="/test-predict-web/test-tool1" target="_blank" class="custom-button" data-text="tool2">
  <button>肥胖风险评估工具</button>
</a>

<!-- 糖尿病风险评估工具按钮 -->
<a href="https://nikolalu.shinyapps.io/test-risk-tool/" target="_blank" class="custom-button" data-text="tool3">
  <button>糖尿病风险评估工具</button>
</a>

<!-- 耳聋风险评估工具按钮 -->
<a href="https://nikolalu.shinyapps.io/test-risk-tool/" target="_blank" class="custom-button" data-text="tool4">
  <button>耳聋风险评估工具</button>
</a>

<!-- 脑卒中风险评估工具按钮 -->
<a href="https://nikolalu.shinyapps.io/test-risk-tool/" target="_blank" class="custom-button" data-text="tool5">
  <button>脑卒中风险评估工具</button>
</a>

<!-- 中风风险评估工具按钮 -->
<a href="https://nikolalu.shinyapps.io/test-risk-tool/" target="_blank" class="custom-button" data-text="tool6">
  <button>中风风险评估工具</button>
</a>
