<template>
  <div class="nav">
    <div class="w">
      <div class="dropdown fl">
          <div class="dl">全部商品分类</div>
          <div class="dt">
            <ul>
              <li><a href="">家用电器</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
              <li><a href="">手机 、 数码 、 通信</a> <span class="icon iconfont">&#xe60e;</span></li>
            </ul>
          </div>
      </div>
      <div class="nav-tabs fr">
        <ul>
          <li><a href="" class="style-red">服装城</a></li>
          <li><a href="">服装城</a></li>
          <li><a href="">服装城</a></li>
          <li><a href="">服装城</a></li>
          <li><a href="">服装城</a></li>
          <li><a href="">服装城</a></li>
          <li><a href="">服装城</a></li>
          <li><a href="">服装城</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Nav"
}
</script>

<style>
.nav{
  height: 50px;
  line-height: 50px;
  text-align: center;
  border-bottom: 3px solid #c81623;
}
.nav .dropdown{
  width: 210px;
  height: 50px;
  background-color: #b1191a;
  line-height: 50px;
  color: #fff;
}
.dropdown .dl{
  width: 210px;
  height: 50px;
  background-color: #b1191a;
}
.dropdown .dt{
  width: 210px;
  height: 467px;
  padding: 0 10px;
  background-color: #c81623;
  box-sizing: border-box;
}
.dropdown .dt ul li{
    height: 33px;
    font-size: 12px;
    line-height: 33px;
}
.dropdown .dt ul li a{
  float: left;
  color: #fff;
}
.dropdown .dt ul li span{
  font-size: 8px;
  float: right;
}
.nav-tabs ul{
  overflow: hidden;
}
.nav-tabs{
  width: 990px;
  height: 50px;
}
.nav-tabs ul li{
  float: left;
  font-size: 16px;
}
.nav-tabs ul li a{
  padding: 0 20px;
}
</style>
