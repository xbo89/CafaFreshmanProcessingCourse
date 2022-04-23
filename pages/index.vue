<template>
  <div>
    <div class="flex items-center space-x-4">
      <span><a target="_blank" href="https://read.cv/wangwenbo.me">@wangwenbo.me</a> / </span>
      <time>2022-04-18</time>
      <iframe
        src="https://ghbtns.com/github-btn.html?user=xbo89&repo=CAFAFreshmanProcessingCourse&type=star&count=true"
        frameborder="0"
        scrolling="0"
        width="150"
        height="20"
        title="GitHub"
      />
    </div>

    <h2>课程介绍</h2>
    <blockquote>
      <p> 这是一门针对中央美术学院大一基础部同学的编程基础认知课程，本课程通过使用Processing 来帮助大家对编程有一定的基础了解，同时该课程后期包含了相对高级的编程思路介绍。适合同学后期自学成长使用。建立更深入的编程算法逻辑，以及创作更复杂的互动编程创意效果 </p>
    </blockquote>
    <p>
      本课程思路分为两大部分：
      <ul>
        <li>编程基础知识</li>
        <li>提高部分</li>
      </ul>
    </p>
    <hr>
    <h2>课程目录</h2>
    <ol>
      <h3>基础</h3>
      <li>
        <NuxtLink to="/unit01">
          第一课：初识编程
        </NuxtLink>
      </li>
      <ol class="text-base">
        <li>技术世界的建筑金字塔——你要成为金字塔顶端的人</li>
        <li>为什么学习编程</li>
        <li>艺术院校同学们学习编程的认知拓宽</li>
        <li>克服学习编程的恐惧感</li>
        <li>克服对编程语言的认知错误</li>
        <li>我们到底在编写的是什么</li>
        <li>各种编程语言我们是学不过来的——学会框架思路</li>
        <li>写一写，试一试</li>
        <li>Processing 整体了解</li>
        <li>课后思考</li>
      </ol>
      <li><a href="#">第二课：尝试编写 Processing（初）</a></li>
      <ol class="text-base">
        <li>编写你的第一个Processing程序</li>
        <li>绘制简单图形</li>
        <li>变量</li>
        <li>交互</li>
        <li>媒体</li>
      </ol>
      <li><a href="#">第三课：尝试编写 Processing（中）</a></li>
      <ol class="text-base">
        <li>运动</li>
        <li>函数</li>
        <li>对象</li>
        <li>数组</li>
        <li>Processing 3D</li>
      </ol>
      <li><a href="#">第四课：综合实践、知识点巩固与补充</a></li>

      <h3>学习源代码</h3>
      <li><a href="#">第五课：学习资源 & 代码拆分</a></li>

      <h3>赋予代码生命力（提升）</h3>
      <li><a href="#">第六课：基础知识</a></li>
      <li><a href="#">第七课：力的Processing表达</a></li>
      <li><a href="#">第八课：弹性运动</a></li>
      <li><a href="#">第九课：模拟世界中的物理运动</a></li>
    </ol>
    <hr>
    <h2>参考文献</h2>
    <ul class="prose prose-ul:text-xs dark:prose-invert">
      <li>《代码本色》：<a href="https://www.cafa.edu.cn/library/book/code-color">https://www.cafa.edu.cn/library/book/code-color</a></li>
      <li>《爱上Processing》：<a href="https://www.cafa.edu.cn/library/book/love-processing">https://www.cafa.edu.cn/library/book/love-processing</a></li>
      <li>Processing Doc：<a href="https://processing.org/">https://processing.org/</a></li>
      <li>The Coding Train：<a href="https://thecodingtrain.com/">https://thecodingtrain.com/</a></li>
    </ul>
    <p />
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  head: {
    title: '中央美术学院大一基础部开源编程——Processing实现'
  }
}
</script>
<style>
.haha{
  @apply text-xl font-bold;
}
</style>
