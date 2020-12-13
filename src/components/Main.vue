<template>
    <div>
        <section class="w">
          <div class="main">
            <div class="slider">
              <ul>
                <li><a href=""><img src="http://www.boyuanwl.com/upload/focus.jpg" alt=""></a></li>

              </ul>
              <span class="icon iconfont left-arrow">&#xec5b;</span>
              <span class="icon iconfont right-arrow">&#xe60e;</span>
              <ul class="circle">
                <li><a href="" class="style-hs"></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
              </ul>
            </div>
            <div class="col-right">
              <dl>
                <dt>
                  <h2 class="fl">品优购快报</h2>
                  <a class="fr" href="">更多<span class="icon iconfont">&#xe60e;</span></a>
                </dt>
                <dd class="first-dd">【特惠】爆款耳机5折秒！</dd>
                <dd>【特惠】爆款耳机5折秒！</dd>
                <dd>【特惠】爆款耳机5折秒！</dd>
                <dd>【特惠】爆款耳机5折秒！</dd>
                <dd>【特惠】爆款耳机5折秒！</dd>
              </dl>
            </div>
          </div>
        </section>
    </div>
</template>

<script>
export default {
name: "Main"
}
</script>

<style>
.style-hs{
  background: #fff !important;
  border: 2px solid #fff !important;
}

.col-right{
  float: left;
  margin-left: 10px;
  width: 240px;
  height: 454px;
  border: 1px solid #ccc;
  font-size: 12px;
  color: #666;
}

.col-right dl{
  border-bottom: 1px dashed #ccc;
}
.col-right dl h2{
  font-size: 14px;
}
.col-right dl dt{
  border-bottom: 1px solid transparent;
  height: 33px;
  line-height: 33px;
  padding: 0 8px;
}
.col-right dl dd{
  height: 23px;
  line-height: 23px;
  padding-left: 8px;
  box-sizing: border-box;
}
.col-right dd:first-child{
  margin-top: 8px !important;
}
.col-right dd:last-child{
  margin-bottom: 8px !important;
}

.main{
  width: 980px;
  height: 468px;
  padding:10px 0;
  margin-left: 219px;
  box-sizing: border-box;
  border: 1px solid transparent;
}
.slider{
  width: 723px;
  height: 454px;
  float: left;
  position: relative;
}
.slider ul li img{
  width: 723px;
  height: 454px;
}
.slider ul li a{
  display: block;
}
.slider span{
  display: inline-block;
  position: absolute;
  width: 41px;
  height: 69px;
  font-size: 40px;
  line-height: 69px;
  top: 183px;
}
.slider span:hover{
  background-color: rgba(0,0,0,0.5);
}
.left-arrow{
  left: 0;
  cursor: pointer;
}
.right-arrow{
  right: 0;
  cursor: pointer;
}
.slider .circle{
  border: 1px solid transparent;
  position: absolute;
  left: 58px;
  top: 413px;
}
.slider .circle li{
  float: left;
  padding: 0 5px;

}
.slider .circle li a{
  display: inline-block;
  width: 10px;
  height: 10px;
  border: 2px solid #999;
  border-radius: 50%;
}
</style>
