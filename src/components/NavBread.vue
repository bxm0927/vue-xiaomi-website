<template>
  <section class="bread">
      <div class="bread-wrap">
          <nav>
              <a href="/">主页</a>
              <slot></slot>
          </nav>
      </div>
  </section>
</template>

<style>
  .bread{
      max-width: 1280px;
      width: 100%;
      height: 45px;
      line-height: 45px;
      background-color: #f5f7fc;
      margin: 0 auto;
  }
  .bread-wrap{
      padding: 0 10px;
      font-size: 14px;
      color: #a1a1a1;
  }
  .bread-wrap a{
    position: relative;
    margin-right: 20px;
  }
  .bread-wrap a:after{
      position: absolute;
      top: 0px;
      content:'/';
      height:20px;
      line-height: 20px;
      margin-left: 10px;
  }
  .bread-wrap span{
      color:#d1434a;
  }
</style>
