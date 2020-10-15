<template>
  <view class="page">
    <view class="sousuo">
      <view class="dizhi">合肥</view>
      <image class="icon" src="/static/jiantou.png" />
      <view class="wrap">
        <image class="icon" src="/static/icon/sousuo.png" />
        <input type="text" class="input" placeholder="找工作找房子" />
      </view>
    </view>
    <view class="fenlei">
      <view class="s-xiao">
        <view class="zhaodian">
          <image class="icon" src="/static/icon/zhaodian.png" />
          <view class="text">免费找店</view>
        </view>
        <view class="zhaodian">
          <image class="icon" src="/static/icon/fangchang.png" />
          <view class="text">房产</view>
        </view>
        <view class="zhaodian">
          <image class="icon" src="/static/icon/ping.png" />
          <view class="text">招聘</view>
        </view>
        <view class="zhaodian">
          <image class="icon" src="/static/icon/qiuzhi.png" />
          <view class="text">求职</view>
        </view>
      </view>
      <view class="s-xiao">
        <view class="zhaodian">
          <image class="icon" src="/static/icon/bang.png" />
          <view class="text">万能帮</view>
        </view>
        <view class="zhaodian">
          <image class="icon" src="/static/icon/ershou.png" />
          <view class="text">二手交易</view>
        </view>
        <view class="zhaodian">
          <image class="icon" src="/static/icon/kuaigou.png" />
          <view class="text">快购</view>
        </view>
        <view class="zhaodian">
          <image class="icon" src="/static/icon/aixin.png" />
          <view class="text">爱心公益</view>
        </view>
      </view>
    </view>
    <view class="l-icon">
      <view class="m-icon">
        <view class="s-icon"></view>
        <view class="s-icon"></view>
        <view class="s-icon"></view>
      </view>
    </view>
    <view class="title">
      <view class="shengyi">生意转让</view>
      <view class="chuzu">房屋出租</view>
      <view class="chuzu">房屋求租</view>
    </view>
    <view class="tuijian">
      <image class="icon" src="/static/icon/tupian-3.png" />
      <view class="s-box">
        <view class="s-title">业主直转！淮河路步行街旺铺餐馆</view>
        <view class="text">庐阳-淮河路步行街 | 经营中</view>
        <view class="text">刘先生 张震牛面馆</view>
      </view>
    </view>
    <view class="tuijian">
      <image class="icon" src="/static/icon/tupian-3.png" />
      <view class="s-box">
        <view class="s-title">业主直转！淮河路步行街旺铺餐馆</view>
        <view class="text">庐阳-淮河路步行街 | 经营中</view>
        <view class="text">刘先生 张震牛面馆</view>
      </view>
    </view>
  </view>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.page {
  .sousuo {
    margin-top: 10px;
    margin-left: 20px;
    display: flex;
    .dizhi {
      font-size: 12px;
      font-weight: 400;
      color: #333333;
      line-height: 17px;
      align-self: center;
    }
    .icon {
      margin-left: 5px;
      width: 11px;
      height: 6px;
      align-self: center;
    }
    .wrap {
      margin-left: 59px;
      height: 30px;
      background: #f9f9f9;
      border-radius: 15px;
      display: flex;
      .icon {
        margin-left: 20px;
        width: 16px;
        height: 16px;
        align-self: center;
      }
      .input {
        margin-left: 10px;
        font-size: 12px;
        color: #cccccc;
        align-self: center;
      }
    }
  }
  .fenlei {
    .s-xiao {
      margin-top: 26px;
      display: flex;
      justify-content: space-around;
      .zhaodian {
        width: 48px;
        height: 52px;
        .icon {
          margin-left: 8px;
          width: 32px;
          height: 32px;
        }
        .text {
          text-align: center;
          font-size: 12px;
          font-weight: 400;
          color: #666666;
          line-height: 17px;
        }
      }
    }
  }
  .l-icon {
    margin-top: 20px;
    margin-left: 5%;
    width: 90%;
    height: 80px;
    background: #f8e71c;
    border-radius: 40px;

    .m-icon {
      margin-left: 37%;
      .s-icon {
        float: left;
        width: 8px;
        height: 8px;
        background: #ffffff;
        opacity: 0.7;
        margin-top: 70px;
        margin-left: 10px;
        border-radius: 50%;
        cursor: pointer;
      }
    }
  }
  .title {
    display: flex;
    margin-top: 20px;
    border-bottom: #eeeeee 1px solid;

    .shengyi {
      width: 48px;
      height: 27px;
      font-size: 12px;
      font-weight: 500;
      color: #ff552e;
      line-height: 17px;
      margin-left: 20px;
      border-bottom: #ff552e 1px solid;
    }
    .chuzu {
      width: 48px;
      height: 17px;
      font-size: 12px;
      font-weight: 400;
      color: #0e8ed8;
      line-height: 17px;
      margin-left: 20px;
    }
  }
  .tuijian {
    margin-top: 10px;
    display: flex;
    .icon {
      margin-left: 20px;
      width: 150px;
      height: 80px;
    }
    .s-box {
      margin-left: 10px;
      .s-title {
        width: 175px;
        font-size: 12px;
        font-weight: 500;
        color: #333333;
        line-height: 17px;
      }
      .text {
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 17px;
        margin-top: 5px;
      }
    }
  }
}
</style>