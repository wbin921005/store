<style lang="less">
    @import './zhihu_css.less';
</style>
<template>
  <html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport"
      content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link href="https://cdn.bootcss.com/bulma/0.6.1/css/bulma.min.css" rel="stylesheet">
  <link href="https://cdn.bootcss.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
  <link rel="stylesheet" href="zhihu_css.less">
  <title>Document</title>
</head>
<body>
<div class="navbar has-shadow">
  <div class="container">
    <div class="navbar-menu">
      <div class="navbar-start">
        <a class="navbar-item">首页</a>
        <a class="navbar-item">发现</a>
        <a class="navbar-item">话题</a>
        <div class="navbar-item">
          <div class="field is-grouped">
            <div class="control has-icons-right">
              <input type="text" class="input" style="width: 20rem;" placeholder="搜索你感兴趣的内容...">
              <span class="icon is-right">
              <i class="fa fa-search"></i>
            </span>
            </div>
            <div class="control">
              <input type="submit" class="button is-info" value="提问">
            </div>
          </div>
        </div>
      </div>
      <div class="navbar-end">
        <a href="#" class="navbar-item">
          <i class="fa fa-15 fa-bell"></i>
        </a>
        <a href="#" class="navbar-item">
          <i class="fa fa-15 fa-comments"></i>
        </a>
        <a href="#" class="navbar-item">
          <img src="https://bulma.io/images/placeholders/128x128.png" alt="">
        </a>
      </div>
    </div>
  </div>
</div>
<div class="navbar has-shadow" style="position: relative; top: 1px;">
  <div class="container">
    <div class="navbar-tabs">
      <a href="#" class="navbar-item is-tab is-active">综合</a>
      <a href="#" class="navbar-item is-tab">用户</a>
      <a href="#" class="navbar-item is-tab">话题</a>
      <a href="#" class="navbar-item is-tab">专栏</a>
      <a href="#" class="navbar-item is-tab">Live</a>
      <a href="#" class="navbar-item is-tab">私家课</a>
      <a href="#" class="navbar-item is-tab">电子书</a>
    </div>
  </div>
</div>
<div class="section">
  <div class="container">
    <div class="tile">
      <div class="tile is-vertical is-parent is-8">
        <div class="box">
          <div class="media">
            <div class="media-left">
              <figure class="image is-64x64">
                <img src="https://bulma.io/images/placeholders/128x128.png" alt="">
              </figure>
            </div>
            <div class="media-content lh-20">
              <p><strong>协程</strong> <span class="tag is-lightblue">话题</span></p>
              <p>
                380关注 | 68 问题 | 69精华内容
                <button class="button is-info is-pulled-right">关注话题</button>
              </p>
              <p><a href="#">查看更多 [话题] 搜索结果</a></p>
            </div>
          </div>
        </div>
        <div class="box">
          <div class="media">
            <div class="media-content">
              <div class="content">
                <p><strong>协程的好处有哪些？</strong></p>
                <p><strong>阿猫：</strong>没有啥复杂的东西，考虑清楚需求，就可以很自然的衍生出这些解决方案。</p>
                <p>
                  <a class="tag is-medium is-lightblue has-addons">
                    <i class="fa fa-caret-up"></i>
                    <span class="icon is-medium">763</span>
                  </a>
                  <a class="tag is-medium is-lightblue">
                    <i class="fa fa-caret-down"></i>
                  </a>
                  <a href="#" class="ml-10">
                    <i class="fa fa-comment"></i>
                    <span>38 条评论</span>
                  </a>
                </p>
              </div>
            </div>
          </div>
          <div class="media">
            <div class="media-content">
              <div class="content">
                <p><strong>协程的好处有哪些？</strong></p>
                <p><strong>阿猫：</strong>没有啥复杂的东西，考虑清楚需求，就可以很自然的衍生出这些解决方案。</p>
                <p>
                  <a class="tag is-medium is-lightblue has-addons">
                    <i class="fa fa-caret-up"></i>
                    <span class="icon is-medium">763</span>
                  </a>
                  <a class="tag is-medium is-lightblue">
                    <i class="fa fa-caret-down"></i>
                  </a>
                  <a href="#" class="ml-10">
                    <i class="fa fa-comment"></i>
                    <span>38 条评论</span>
                  </a>
                </p>
              </div>
            </div>
          </div>
          <div class="media">
            <div class="media-content">
              <div class="content">
                <p><strong>协程的好处有哪些？</strong></p>
                <p><strong>阿猫：</strong>没有啥复杂的东西，考虑清楚需求，就可以很自然的衍生出这些解决方案。</p>
                <p>
                  <a class="tag is-medium is-lightblue has-addons">
                    <i class="fa fa-caret-up"></i>
                    <span class="icon is-medium">763</span>
                  </a>
                  <a class="tag is-medium is-lightblue">
                    <i class="fa fa-caret-down"></i>
                  </a>
                  <a href="#" class="ml-10">
                    <i class="fa fa-comment"></i>
                    <span>38 条评论</span>
                  </a>
                </p>
              </div>
            </div>
          </div>
          <div class="media">
            <div class="media-content">
              <div class="content">
                <p><strong>协程的好处有哪些？</strong></p>
                <p><strong>阿猫：</strong>没有啥复杂的东西，考虑清楚需求，就可以很自然的衍生出这些解决方案。</p>
                <p>
                  <a class="tag is-medium is-lightblue has-addons">
                    <i class="fa fa-caret-up"></i>
                    <span class="icon is-medium">763</span>
                  </a>
                  <a class="tag is-medium is-lightblue">
                    <i class="fa fa-caret-down"></i>
                  </a>
                  <a href="#" class="ml-10">
                    <i class="fa fa-comment"></i>
                    <span>38 条评论</span>
                  </a>
                </p>
              </div>
            </div>
          </div>
          <div class="media">
            <div class="media-content">
              <div class="content">
                <p><strong>协程的好处有哪些？</strong></p>
                <p><strong>阿猫：</strong>没有啥复杂的东西，考虑清楚需求，就可以很自然的衍生出这些解决方案。</p>
                <p>
                  <a class="tag is-medium is-lightblue has-addons">
                    <i class="fa fa-caret-up"></i>
                    <span class="icon is-medium">763</span>
                  </a>
                  <a class="tag is-medium is-lightblue">
                    <i class="fa fa-caret-down"></i>
                  </a>
                  <a href="#" class="ml-10">
                    <i class="fa fa-comment"></i>
                    <span>38 条评论</span>
                  </a>
                </p>
              </div>
            </div>
          </div>
          <div class="media">
            <div class="media-content">
              <div class="content">
                <p><strong>协程的好处有哪些？</strong></p>
                <p><strong>阿猫：</strong>没有啥复杂的东西，考虑清楚需求，就可以很自然的衍生出这些解决方案。</p>
                <p>
                  <a class="tag is-medium is-lightblue has-addons">
                    <i class="fa fa-caret-up"></i>
                    <span class="icon is-medium">763</span>
                  </a>
                  <a class="tag is-medium is-lightblue">
                    <i class="fa fa-caret-down"></i>
                  </a>
                  <a href="#" class="ml-10">
                    <i class="fa fa-comment"></i>
                    <span>38 条评论</span>
                  </a>
                </p>
              </div>
            </div>
          </div>
          <div class="media">
            <div class="media-content">
              <div class="content">
                <p><strong>协程的好处有哪些？</strong></p>
                <p><strong>阿猫：</strong>没有啥复杂的东西，考虑清楚需求，就可以很自然的衍生出这些解决方案。</p>
                <p>
                  <a class="tag is-medium is-lightblue has-addons">
                    <i class="fa fa-caret-up"></i>
                    <span class="icon is-medium">763</span>
                  </a>
                  <a class="tag is-medium is-lightblue">
                    <i class="fa fa-caret-down"></i>
                  </a>
                  <a href="#" class="ml-10">
                    <i class="fa fa-comment"></i>
                    <span>38 条评论</span>
                  </a>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="tile is-vertical is-parent">
        <div class="card">
          <div class="card-header">
            <p class="card-header-title">相关结果</p>
          </div>
          <div class="card-content">
            <div class="media">
              <div class="media-left">
                <figure class="image is-64x64">
                  <img src="https://bulma.io/images/placeholders/128x128.png" alt="">
                </figure>
              </div>
              <div class="media-content">
                <p>
                  <strong>线程内上下文切换</strong>
                  <span class="tag is-gray">专栏</span></p>
                <p>
                  1.6K 关注 | 12 篇文章
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-header">
            <p class="card-header-title">知乎热搜</p>
          </div>
          <div class="card-content">
            <ul class="lh-20">
              <li><a href="#">演员的诞生第十期</a><i class="fa fa-fire"></i></li>
              <li><a href="#">北航陈小武</a><i class="fa fa-fire"></i></li>
              <li><a href="#">微信跳一跳</a><i class="fa fa-fire"></i></li>
              <li><a href="#">解忧杂货店</a></li>
              <li><a href="#">前任3</a></li>
              <li><a href="#">妖猫传</a></li>
              <li><a href="#">琅琊榜2</a></li>
              <li><a href="#">刘昊然</a></li>
              <li><a href="#">黄轩</a></li>
              <li><a href="#">比特币</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div><!-- container -->
</div>
</body>
</html>
</template>
<script>
      export default {
          data() {
              return {
                 //v1:'',
                 //v2:''
              }
          },
          /*components:{
              add
          },*/
          methods:{
              
          } 
      }
</script>
