<template>
  <view class="page">
    <view class="a-img">
      <image class="img" src="/static/1.jpg" />
      <view class="box">
        <view class="a-biao"></view>
        <view class="a-biao"></view>
        <view class="a-biao"></view>
      </view>
    </view>
    <view class="text-title"
      >(出租) 开发商直租成熟社区底商学校周边商业街零售小吃招租
      <view class="fen"></view>
    </view>
    <view class="xiang">
      <view class="box">
        <view class="text">面积</view>
        <view class="num">600平米</view>
      </view>
      <view class="box">
        <view class="text">租金(元/月)</view>
        <view class="num">12000</view>
      </view>
      <view class="box">
        <view class="text">转让费</view>
        <view class="num">55万</view>
      </view>
    </view>
    <view class="jiben">
      <view class="xinxi-title">
        <view class="xin-text">基本信息</view>
      </view>
      <view class="fen-b">
        <view class="fen-box">
          <view class="fen-title">可否空转：</view>
          <view class="fen-xinxi">不可空转</view>
        </view>
        <view class="fen-box">
          <view class="fen-title">店铺状态：</view>
          <view class="fen-xinxi">营业中</view>
        </view>
        <view class="fen-box">
          <view class="fen-title">所在区域：</view>
          <view class="fen-xinxi">蜀山-望江西路</view>
        </view>
        <view class="fen-box">
          <view class="fen-title">详细地址：</view>
          <view class="fen-xinxi">望江西路与香樟大道交叉口</view>
        </view>
      </view>
      <view class="xiang-box">
        <view class="box">
          <view class="xin-text">门框:</view>
          <view class="xi-text">未填写</view>
        </view>
        <view class="box">
          <view class="xin-text">层高:</view>
          <view class="xi-text">未填写</view>
        </view>
      </view>
      <view class="xiang-box">
        <view class="box">
          <view class="xin-text">进深:</view>
          <view class="xi-text">未填写</view>
        </view>
        <view class="box">
          <view class="xin-text">楼层类型:</view>
          <view class="xi-text">单层</view>
        </view>
      </view>
      <view class="xiang-box">
        <view class="box">
          <view class="xin-text">楼层:</view>
          <view class="xi-text">1层</view>
        </view>
      </view>
    </view>
    <view class="box-xiang">
      <view class="title">
        <view class="xin-text">配套设置</view>
      </view>
      <view class="box">
        <view class="xiangxi">货梯</view>
        <view class="xiangxi">中央空调</view>
        <view class="xiangxi">停车位</view>
        <view class="xiangxi">天然气</view>
        <view class="xiangxi">网络</view>
      </view>
    </view>
    <view class="box-xiang">
      <view class="title">
        <view class="xin-text">店铺详情</view>
      </view>
      <view class="jieshao">
        店铺位于蜀山区望江西路广汇广场一楼，面积107平米，送阁楼60平，租金6200元/月。地理位置优越，成熟商圈，旁边就是老乡鸡和肯德基。大型购物中心有写字楼，高档社区，人流量秘籍，客源稳定，本人因其他生意，故转让。有意者可实地考察。看店勿扰客。
      </view>
    </view>
    <view class="geren-box">
      <view class="geren">
        <view class="lianxi">联系人:</view>
        <view class="name">刘先生</view>
      </view>
      <view class="ne-box">
        <view class="tu-box">
          <image class="icon" src="/static/icon/sousuo.png" />
        <view class="ne">138****8986</view>
        </view>
      </view>
    </view>
  </view>
</template>

<style lang="scss" scoped>
.page {
  .a-img {
    .img {
      width: 100%;
      height: 150px;
      position: relative;
    }
    .box {
      display: flex;
      width: 15%;
      position: absolute;
      top: 130px;
      left: 45%;
      .a-biao {
        width: 8px;
        height: 8px;
        background: #ffffff;
        opacity: 0.7;
        margin-right: 5px;
        border-radius: 50%;
      }
    }
  }
  .text-title {
    margin-top: 20px;
    width: 80%;
    margin-right: auto;
    margin-left: auto;
    text-align: center;
    font-size: 16px;
    font-weight: 500;
    color: #333333;
    line-height: 22px;
    .fen {
      border: 1px solid #eeeeee;
      width: 35%;
      margin-top: 20px;
      margin-right: auto;
      margin-left: auto;
    }
  }
  .xiang {
    margin-top: 15px;
    width: 100%;
    display: flex;
    justify-content: space-around;
    height: 55px;
    border-bottom: 5px solid #eeeeee;
    .box {
      width: 22%;
      height: 40px;
      .text {
        text-align: center;
        font-size: 12px;
        color: #666666;
      }
      .num {
        text-align: center;
        font-size: 14px;
        color: #ff552e;
      }
    }
  }
  .jiben {
    margin-top: 15px;
    border-bottom: 5px solid #f9f9f9;
    .xinxi-title {
      margin-left: 10px;
      width: 60px;
      border-left: 2px solid #ff552e;
      height: 18px;
      .xin-text {
        float: right;
        font-size: 14px;
        color: #333333;
      }
    }
    .fen-b {
      margin-top: 5px;
      margin-left: 12px;
      border-bottom: 1px solid #f9f9f9;
      height: 100px;
      .fen-box {
        margin-top: 5px;
        display: flex;
        .fen-title {
          font-size: 12px;
          color: #999999;
        }
        .fen-xinxi {
          font-size: 12px;
          color: #333333;
        }
      }
    }
    .xiang-box {
      margin-left: 12px;
      margin-top: 10px;
      display: flex;
      margin-bottom: 15px;
      .box {
        width: 50%;
        display: flex;
        .xin-text {
          font-size: 12px;
          color: #999999;
        }
        .xi-text {
          margin-left: 10px;
          font-size: 12px;
          color: #333333;
        }
      }
    }
  }
  .box-xiang {
    margin-top: 10px;
    margin-left: 10px;
    margin-right: 10px;
    .title {
      width: 60px;
      border-left: 2px solid #ff552e;
      height: 18px;
      .xin-text {
        float: right;
        font-size: 14px;
        color: #333333;
      }
    }
    .box {
      display: flex;
      width: 100%;
      border-bottom: 5px solid #f9f9f9;
      .xiangxi {
        margin-left: 5px;
        width: 45px;
        text-align: center;
        height: 17px;
        margin-top: 15px;
        margin-bottom: 15px;
        font-size: 12px;
        color: #666666;
        border-right: 2px solid #cccccc;
      }
    }
    .jieshao {
      margin-top: 10px;
      font-size: 12px;
      color: #666666;
      margin-bottom: 20px;
    }
  }
  .geren-box {
    display: flex;
    margin-right: 10px;
    margin-left: 10px;
    .geren {
      display: flex;
      .lianxi {
      font-size: 14px;
color: #999999;
      }
      .name {
        font-size: 14px;
        color: #333333;
        margin-left: 10px;
      }
    }
    .ne-box {
      display: flex;
      width: 60%;
      margin-left: auto;
      height: 34px;
      background: #ff552e;
      border-radius: 17px;
      .tu-box{
        margin-left: auto;
        margin-right: auto;
        display: flex;
        .icon {
        align-self: center;
        width: 15px;
        height: 15px;
      }
      .ne {
        align-self: center;
        font-size: 18px;
        color: #ffffff;
      }
      }
    }
  }
}
</style>