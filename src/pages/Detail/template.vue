<template>
  <div id="detail">
    <section class="user-info">
      <img class="avatar" src="https://cn.gravatar.com/avatar/3?s=128&d=identicon" alt="">
      <h3>CSS学习指南</h3>
      <p><rouer-link to="/user">西柚</rouer-link> 发布于3天前</p>
    </section>

    <section class="article">
      <h1>CSS网课布局学习指南</h1>
      <p>CSS 网格布局学习指南 CSS 网格布局(Grid Layout) 是CSS中最强大的布局系统。 这是一个二维系统，这意味着它可以同时处理列和行，不像 flexbox 那样主要是一维系统。 你可以通过将CSS规则应用于父元素（成为网格容器）和该元素的子元素（网格元素），来使用网格布局。</p>
      <p>引言 CSS网格布局（又名“网格”）是一个二维的基于网格的布局系统，其目的只在于完全改变我们设计基于网格的用户界面的方式。 CSS一直用来布局网页，但一直都不完美。 一开始我们使用table 做布局，然后转向浮动、定位以及inline-block，但所有这些方法本质上都是 Hack 的方式，并且遗漏了很多重要的功能（例如垂直居中）。 Flexbox的出现在一定程度上解决了这个问题，但是它的目的是为了更简单的一维布局，而不是复杂的二维布局（Flexbox和Grid实际上一起工作得很好）。 只要我们一直在制作网站，我们就一直在为解决布局问题不断探索， 而Grid是第一个专门为解决布局问题而生的CSS模块。</p>
      <p>有两个东西，启发我写这篇指南。 第一个是雷切尔·安德鲁（Rachel Andrew）的书为CSS Grid布局准备。 这本书对网格布局做了彻底、清晰的介绍，也是是整篇文章的基础，我强烈建议你购买并阅读他的书。 我的另一个重要灵感是Chris Coyier的Flexbox完全指南，当需要查阅 flexbox 的一切资料时我就会找这篇文章。 这篇文章帮助了很多人学习 Flex 布局，也是 Google 上搜索“flexbox”关键字排名第一的文章。你会发现他的文章和我的很多相似之处，有最好的范例在那放着为什么咱不偷师学着写呢？</p>
    </section>
  </div>
</template>

<script src="./template.js"></script>

<style scoped lang="less" src="./template.less"></style>
