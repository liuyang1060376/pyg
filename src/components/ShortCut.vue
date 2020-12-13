<template>
  <div>
    <div class="shortcut">
      <div class="w">
        <div class="fl">
          <ul>
            <li>品优购欢迎您</li>
            <li><a href="">请登录</a>&nbsp<a href="" class="style-red">免费注册</a></li>
          </ul>
        </div>
        <div class="fr">
          <ul>
            <li><a href="">我的订单</a></li>
            <li class="spacer">|</li>
            <li><a href="">我的品优购<span class="icon iconfont">&#xe60a;</span></a></li>
            <li class="spacer">|</li>
            <li><a href="">品优购会员</a></li>
            <li class="spacer">|</li>
            <li><a href="">企业采购<span class="icon iconfont">&#xe60a;</span></a></li>
            <li class="spacer">|</li>
            <li><a href="">关注品优购</a></li>
            <li class="spacer">|</li>
            <li><a href="">客户服务<span class="icon iconfont">&#xe60a;</span></a></li>
            <li class="spacer">|</li>
            <li><a href="">网站导航</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ShortCut"
}
</script>

<style>

.style-red {
  color: #c81623;
}

.shortcut {
  height: 31px;
  background-color: #f1f1f1;
  font-size: 12px;
  color: #666;
  line-height: 31px;
}
.shortcut .fl ul li {
  padding-left: 5px;
  float: left;
}
.shortcut .fr ul li {
  float: left;
}
.shortcut .fr ul li a span {
  display: inline-block;
  padding: 0 1px;
  font-size: 6px;
}
.shortcut .fr ul .spacer {
  padding: 0 5px;
}


</style>
