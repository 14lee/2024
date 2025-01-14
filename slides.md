---
highlighter: shiki
css: unocss
colorSchema: dark
transition: fade-out
class: text-center
title: 李宇栋2024年度总结
layout: center
glowSeed: 4
lang: zh-CN
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
hideInToc: true
---

# 目录

<Toc text-sm minDepth="1" maxDepth="2" />

---
layout: iframe-right
url: https://n4ie0yx1rk.feishu.cn/share/base/dashboard/shrcnN57BMRiFumhfAUWw47KDwg
---

# 主要工作

- 数字孪生平台功能开发
- 项目支撑
- SDK开发
- 售前、运维工作
- ai分享和实践应用

---
layout: two-cols
level: 2
---

# 数字孪生平台

<div class="text-sm">参与平台功能开发，工程化建设，日常文档维护。</div>
<br />
<div class="text-sm">
  <div class="">
    <span v-click>底座平台:</span>
    <ul class="ml-4" v-click>
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
    <span v-click>智慧应用:</span>
    <ul class="ml-4" v-click>
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
    <span v-click>
      物联网平台
    </span>
    <ul class="ml-4" v-click>
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
    <span v-click>
      数据中心
    </span>
    <ul class="ml-4" v-click>
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
level: 2
---

# 项目支撑

<div class="text-sm">
  澄迈水务
</div>
<br />
<div class="text-sm text-sky-300">
  参与管网隐患、分析问题功能开发、同步数孪平台代码、
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

<div class="text-sm top-35 absolute text-sky-300">
  参与售前阶段完整系统功能开发
</div>

<img
  v-click
  class="absolute right-22 bottom-10 w-100 h-auto"
  src="/nancang.png"
  alt=""
/>

---
layout: two-cols
level: 2
---

# SDK开发

<!-- <section class="flex start"> -->
<div class="text-sm text-sky-300">
  测量功能封装到SDK中, 并支持二次编辑，实时编辑、实时顶点拾取等功能。
</div>
<br />
<SlidevVideo v-click autoplay controls>
  <source src="/measure-sdk.mp4" type="video/mp4" />
  <p>
    你的浏览器不支持播放该视频，请点击
    <a href="/measure-sdk.mp4">此处</a>
    下载。
  </p>
</SlidevVideo>

::right::
<section class="ml-10" v-click>
  <h1>售前、售后</h1>
  <div class="text-sm">
    昆明水文项目、星沙供水
  </div>
  <br />
  <div class="text-sm text-sky-300">
    协助完成项目要求开发、底图对接、流域提取、坐标转换等问题
  </div>
</section>

---

# ai分享与实践

<div class="text-sm">
  今年9月份在林子胜和宋紫璇的带领下，有幸的参与了ai分享会，从中学习到了不少ai相关的基础知识与实战经验。
</div>
<br />
<div class="text-sm" v-click>
  日常工作中将ai作为一个得力助手，发挥ai的能力，做到 <span class="text-sky-300 font-bold text-lg">1 + 1 > 2</span> 的效果
</div>

<img
  v-click
  class="absolute left-5 bottom-2 w-auto h-90"
  src="/ai.png"
  alt=""
/>

<img
  v-click
  class="absolute left-20 bottom-2 w-auto h-90"
  src="/cursor.png"
  alt=""
/>

<img
  v-click
  class="absolute left-35 bottom-2 w-auto h-90"
  src="/kimi.png"
  alt=""
/>

<img
  v-click
  class="absolute left-60 bottom-2 w-auto h-90"
  src="/zetly.png"
  alt=""
/>

<!--
1. ai现阶段并不是为了取代开发者，ai存在的不确定性就导致了一定需要人为的介入去判断ai给出的答案是否正确。

2. 当然也不是满目去生成代码而不去验证是否正确，还是要人为的去判断

3. ai是个很好的快速学习知识的途径，相比于以前的ai能力，现在ai联网搜索能力和准确性都有很大的提升，替代一个传统的搜索引擎，所以现在获取知识的效率和准确性来说是大大提升的。
-->

---

# 拓展学习

<section class="flex">
  <section class="w-40%">
    <div class="text-sm">
      1. 学习vue、vueuse等优秀开源项目源码，并运用到项目、产品实践中。💻
    </div>
    <br />
    <div class="text-sm" v-click>
      2. 对科技、gis行业、编程、ai等最新咨询保持关注。🔥
    </div>
    <br />
    <div class="text-sm" v-click>
      3. 业余时间折腾diy nas, 拓展工程化能力
      <br />（<span class="text-red-500 text-lg font-bold">all in boom</span> 💥👉💀）
    </div>
  </section>

  <section class="w-80% relative">
    <img
      v-click
      class="absolute left-0 -top-20 w-full h-auto"
      src="/vue3.png"
      alt=""
    />
    <img
      v-click
      class="absolute left-2 -top-10 w-full h-auto"
      src="/follow.png"
      alt=""
    />
    <img
      v-click
      class="absolute left-4 top-0 w-full h-auto"
      src="/github-trending.png"
      alt=""
    />
    <img
      v-click
      class="absolute left-6 top-10 w-full h-auto"
      src="/koala.png"
      alt=""
    />
    <img
      v-click
      class="absolute left-8 top-30 w-full h-auto"
      src="/nas.jpg"
      alt=""
    />
  </section>
</section>

<!--
1. 平时也会学习一些优秀的开源项目，并且将学习到的知识运用到平台项目中

2. 今年也折腾了一些其他好玩的东西，例如自己组装一台diy nas，搭建自己的个人服务器，从买硬件到刷pve系统，到安装各种系统,一点点踩坑学习终最终也是搭建成功，从中也是学习到不少网络、服务器相关知识，这些方面虽然不是直接的体现在项目上，但对于提升综合能力方面还是很有用的。
-->

---

# 进步与不足

<ProsCons
  :pros="[
    '沟通交流',
    '工程化能力有所进步',
    'ai基础知识有所提升'
  ]"
  :cons="[
    '没有很好将自己想法真正实践落地',
    '缺少推动事情进展的能力',
    '技术广度、深度还有待提高',
  ]"
/>

---

# 展望未来

<div v-click class="slidev-vclick-target mb-5" :class="$clicks === 1 ? 'text-cyan-400' : ''">
  <div i-ph-target-bold text-cyan-400 inline-block translate-y-2px />
  持续深入数孪平台产品开发，提高平台的可用性、稳定性、易用性
</div>

<div v-click class="slidev-vclick-target mb-5" :class="$clicks === 2 ? 'text-cyan-400' : ''">
  <div i-ph-target-bold text-cyan-400 inline-block translate-y-2px />
  加强ai方面的实践应用。
</div>

<div v-click class="slidev-vclick-target mb-5" :class="$clicks === 3 ? 'text-cyan-400' : ''">
  <div i-ph-target-bold text-cyan-400 inline-block translate-y-2px />
  与他人保持良好的沟通交流，保持团队协作
</div>

<div v-click class="slidev-vclick-target mb-5" :class="$clicks === 4 ? 'text-cyan-400' : ''">
  <div i-ph-target-bold text-cyan-400 inline-block translate-y-2px />
  继续保持对技术的渴望，保持学习，保持进步
</div>


---
hideInToc: true
layout: end
---

# 感谢聆听

<Confetti />

