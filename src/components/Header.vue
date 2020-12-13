<template>
    <div>
      <header class="w">
          <h1 class="logo fl">
            <a href="" title="品优购">品优购</a>
          </h1>
          <div class="search-wrap fl">
              <div class="search-box">
                <input type="text" placeholder="请输入内容">
                <button>搜索</button>
              </div>
              <div class="keywords">
                <ul>
                  <li><a href="" class="style-red">优惠购首发</a></li>
                  <li><a href="">亿元优惠</a></li>
                  <li><a href="">优惠活动</a></li>
                  <li><a href="">优惠活动</a></li>
                  <li><a href="">优惠活动</a></li>
                  <li><a href="">优惠活动</a></li>
                  <li><a href="">优惠活动</a></li>
                </ul>
              </div>
          </div>
          <div class="cart-wrap fr">
            <span class="icon iconfont">&#xe601;</span>我的购物车<span class="icon iconfont">&#xe60e;</span> <span class="sum">23</span>
          </div>
      </header>
    </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style>
  .style-red{
    color: #b1191a !important;
  }
  header {
    height: 105px;
  }
  header .logo {
    width: 175px;
    height: 56px;
    margin-top: 24px;
    overflow: hidden;
  }
  header .logo a {
    display: block;
    width: 175px;
    height: 56px;
    background: url("http://www.boyuanwl.com/img/logo.png") no-repeat;
    text-indent: -999em;
  }
  header .search-wrap {
    width: 550px;
    height: 60px;
    margin-left: 170px;
    margin-top: 25px;
  }
  header .cart-wrap {
    width: 140px;
    height: 39px;
    margin-top: 25px;
    background-color: #f7f7f7;
    border: 1px solid #dfdfdf;
    padding: 10px 18px ;
    font-size: 14px;
    color: #666;
    box-sizing: border-box;
    position: relative;
  }
  .cart-wrap .sum {
    display: inline-block;
    width: 20px;
    height: 20px;
    color: #fff;
    text-align: center;
    font-size: 12px;
    background: url("./../assets/sum.png") no-repeat;
    -webkit-background-size: 20px 20px;
    background-size: 20px 20px;
    line-height: 20px;
    position: absolute;
    left: 107px;
    top: -8px;
  }
  /*搜索框样式*/
  .search-box{
    overflow: hidden;
  }
  .search-box input {
    float: left;
    width: 457px;
    height: 35px;
    padding-left: 16px;
    border: 2px solid #b1191a ;
    box-sizing: border-box;
  }
  .search-box button {
    float: left;
    width: 82px;
    height: 35px;
    background-color: #b1191a;
    border: 2px solid #b1191a;
    color: #fff;
  }
  .keywords ul {
    overflow: hidden;
  }
  .keywords ul li {
    float: left;
    padding-right: 25px;
  }
  .keywords ul li a{
    color: #999;
    font-size: 12px;
  }
  .cart-wrap span:nth-child(1) {
    color: #da5555;
    font-size: 15px;
  }
  .cart-wrap span:nth-child(2) {
    color: #999;
    font-size: 8px;
    padding-left: 1px;
  }


</style>
