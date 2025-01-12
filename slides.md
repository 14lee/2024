---
theme: seriph
background: https://cover.sli.dev
title: 2024年度总结
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
hideInToc: true
---

# 2024年度总结
演讲人: 李宇栋

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  next <carbon:arrow-right />
</div>


<div class="abs-br m-6 text-xl">
  <a href="https://github.com/14lee/2024.git" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
大家好,接下来由我来为大家分享2024年度总结.

注: 该ppt由slidev制作
 -->

---
layout: image-right
image: https://cover.sli.dev
backgroundSize: cover
transition: fade-out
hideInToc: true
---

# 目录

<Toc text-sm minDepth="1" maxDepth="2" />

---

# 主要工作

- 数字孪生平台功能开发
- 项目支撑
- SDK开发
- ai分享和实践应用
- 售前、运维工作

---
layout: two-cols
# image: /smartdbase.png
# backgroundSize: 100% auto
level: 2
---

# 数字孪生平台

<div class="text-sm">参与平台功能开发，工程化建设，日常文档维护。</div>
<br />
<div class="text-sm">
  <div class="">
    <span>底座平台:</span>
    <ul class="ml-4">
      <li>
        <span class="text-sky-300">
          埋点、意见反馈、帮助中心...
        </span>
      </li>
      <li>
        <span class="text-sky-300">
          整合各系统、cicd工程化、统一开发环境
        </span>
      </li>
    </ul>
  </div>
  <div class="mt-4">
    <span>智慧应用:</span>
    <ul class="ml-4">
      <li>
        <span class="text-sky-300">
          天气模拟、粒子特效、剖面分析、位置编辑、
          <br />
          倾斜压片、属性查询、自定义查询、测量功能、
          <br />
          图标库、场景管理...
        </span>
      </li>
    </ul>
  </div>
  <div class="mt-4">
    <span>
      物联网平台
    </span>
    <ul class="ml-4">
      <li>
        <span class="text-sky-300">
          设备管理、产品管理、监控概览、设备接入管理、
          <br />
          告警管理
        </span>
      </li>
    </ul>
  </div>
  <div class="mt-4">
    <span>
      数据中心
    </span>
    <ul class="ml-4">
      <li>
        <span class="text-sky-300">
          元数据模板、首页看板、服务发布、服务管理
        </span>
      </li>
    </ul>
  </div>
</div>


::right::

<img
  v-click
  class="absolute right-20 w-120 h-auto top-10 z-10"
  src="/smartdbase.png"
  alt=""
/>

<img
  v-click
  class="absolute right-15 w-120 h-auto top-30 z-11"
  src="/cicd.png"
  alt=""
/>

<img
  v-click
  class="absolute right-10 w-120 h-auto top-50 z-11"
  src="/changelog.png"
  alt=""
/>

---
layout: two-cols
---

# 项目支撑

<div class="text-sm">
  澄迈水务
</div>
<br />
<div class="text-sm">
  参与问题管网隐患、分析问题功能开发、同步数孪平台代码、
  <br />
  系统整合ai水务问答机器人
</div>

<img
  v-click
  class="absolute left-10 bottom-10 w-100 h-auto"
  src="/chengmai.png"
  alt=""
/>

::right::

<div class="text-sm top-25 absolute">
  南昌管网
</div>

<div class="text-sm top-35 absolute">
  参与售前阶段系统功能开发
</div>

<img
  v-click
  class="absolute right-22 bottom-10 w-100 h-auto"
  src="/nancang.png"
  alt=""
/>
