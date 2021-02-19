<template>
  <div id="header">
      <header>
        <div class="header_nav">
            <a class="logo"></a>
            <ul class="nav-dev fl">
            <li class="fl">
                <a href="javascript:;">在线商城</a>
            </li>
            <li class="fl">
                <a href="javascript:;">坚果Pro</a>
            </li>
            <li class="fl">
                <a href="javascript:;">Smartisan M1 / M1L</a>
            </li>
            <li class="fl">
                <a href="javascript:;">Smartisan OS</a>
            </li>
            <li class="fl">
                <a href="javascript:;">欢喜云</a>
            </li>
            <li class="fl">
                <a href="javascript:;">应用下载</a>
            </li>
            <li class="fl">
                <a href="javascript:;">官方论坛</a>
            </li>
            </ul>
            <span class="line">|</span>
            <a href="javascript:;" class="user"></a>
            <a href="javascript:;" class="cart"><span class="cart-num">0</span></a>
        </div>
      
    </header>
    <nav class="nav">
      <ul>
        <li>
          <a href="javascript:;">首页</a>
        </li>
        <li>
          <a href="javascript:;">手机</a>
        </li>
        <li>
          <a href="javascript:;">"足迹系列"手感膜</a>
        </li>
        <li>
          <a href="javascript:;">官方配件</a>
        </li>
        <li>
          <a href="javascript:;">周边产品</a>
        </li>
        <li>
          <a href="javascript:;">第三方配件</a>
        </li>
        <li>
          <a href="javascript:;">全部商品</a>
        </li>
        <li>
          <a href="javascript:;">服务</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="less">
header{
  width: 100%;
  background-color: black;
  height: 100px;
  .header_nav{
    width: 1220px;
    margin: 0 auto;
    height: 100px;
    .logo{
      display: block;
      background: url("../assets/img/global-logo.png") no-repeat;
      width: 50px;
      height: 50px;
      transform: translateY(25px);
    }
    .nav-dev{
      margin-left: 210px;
      height: 50px;
      margin-top: -25px;
      line-height: 50px;
      a{
        display: block;
        padding: 0 25px;
        color: #c8c8c8;
      }
    }
    .line{
      width: 1px;
      height: 100px;
      line-height: 100px;
      display: inline-block;
      font-size: 25px;
      transform: translateY(-52px);
      margin: 0 50px 0 25px;
    }
    .user{
      display: inline-block;
      background: url("../assets/img/account-icon.png") no-repeat;
      background-position-x: -63px;
      width: 20px;
      height: 20px;
      transform: translateY(-48px);
    }
    .cart{
      display: inline-block;
      width: 65px;
      height: 20px;
      transform: translateY(-48px);
      margin-left: 5px;
      .cart-num{
        display: inline-block;
        background-color: #666;
        position: relative;
        width: 20px;
        height: 20px;
        border-radius: 50%;
        transform: translatex(20px) translateY(-4px);
        text-align: center;
        line-height: 20px;
        color: white;
        font-size: 13px;
      }
    }
    .cart::before{
      content: '';
      display: inline-block;
      background: url("../assets/img/account-icon.png") no-repeat;
      background-position: -60px -21px;
      width: 30px;
      height: 20px;
      transform: translatex(20px);
    }
    
  }
}
</style>