<template>
  <view class="page">
    <view class="title">请选择发布类别</view>
    <view class="box">
      <view class="s-box">
        <image class="icon" src="/static/icon/zhaodian.png" />
        <view class="biaoqian">房产</view>
      </view>
      <view class="text">
        <view class="text-title">商铺转让，招租求租</view>
        <view class="s-text">线上线下，渠道全覆盖</view>
      </view>
      <image class="jiantou" src="/static/icon/jiantou-2.png" />
    </view>
    <view class="box">
      <view class="s-box">
        <image class="icon" src="/static/icon/ping.png" />
        <view class="biaoqian">招聘</view>
      </view>
      <view class="text">
        <view class="text-title">帮我招聘</view>
        <view class="s-text">人才全聚集，招人好轻松</view>
      </view>
      <image class="jiantou" src="/static/icon/jiantou-2.png" />
    </view>
    <view class="box">
      <view class="s-box">
        <image class="icon" src="/static/icon/qiuzhi.png" />
        <view class="biaoqian">求职</view>
      </view>
      <view class="text">
        <view class="text-title">想找工作</view>
        <view class="s-text">找我就对了</view>
      </view>
      <image class="jiantou" src="/static/icon/jiantou-2.png" />
    </view>
    <view class="box">
      <view class="s-box">
        <image class="icon" src="/static/icon/bang.png" />
        <view class="biaoqian">万能帮</view>
      </view>
      <view class="text">
        <view class="text-title">便民服务</view>
        <view class="s-text">体贴您的服务</view>
      </view>
      <image class="jiantou" src="/static/icon/jiantou-2.png" />
    </view>
    <view class="box">
      <view class="s-box">
        <image class="icon" src="/static/icon/ershou.png" />
        <view class="biaoqian">二手交易</view>
      </view>
      <view class="text">
        <view class="text-title">立马变现</view>
        <view class="s-text">线上线下，样样我在行</view>
      </view>
      <image class="jiantou" src="/static/icon/jiantou-2.png" />
    </view>
    <view class="box">
      <view class="s-box">
        <image class="icon" src="/static/icon/kuaigou.png" />
        <view class="biaoqian">快购</view>
      </view>
      <view class="text">
        <view class="text-title">买东西，急急急</view>
        <view class="s-text">便宜快捷，为您服务</view>
      </view>
      <image class="jiantou" src="/static/icon/jiantou-2.png" />
    </view>
    <view class="box">
      <view class="s-box">
        <image class="icon" src="/static/icon/aixin.png" />
        <view class="biaoqian">爱心公益</view>
      </view>
      <view class="text">
        <view class="text-title">上善若水</view>
        <view class="s-text">勿以善小而不为</view>
      </view>
      <image class="jiantou" src="/static/icon/jiantou-2.png" />
    </view>
  </view>
</template>


<style lang="scss" scoped>
.page {
  margin-top: 10px;
  .title {
    margin-left: 30px;
    font-size: 14px;
    font-weight: 400;
    color: #333333;
    line-height: 20px;
  }
  .box {
    justify-content: space-between;
    margin-left: 7%;
    display: flex;
    height: 80px;
    width: 85%;
    border-bottom: #eeeeee 1px solid;
    align-items: center;
    .s-box {
      
      .icon {
        margin-top: 5%;
        width: 32px;
        height: 32px;
      }
      .biaoqian {
        margin-top: 3px;
        text-align: center;
        font-size: 12px;
        color: #666666;
      }
    }
    .text {
      width: 70%;
      .text-title {
        font-size: 14px;
        font-weight: bold;
        color: #333333;
      }
      .s-text {
        font-size: 12px;
        color: #999999;
      }
    }
    .jiantou {
      width: 8px;
      height: 15px;
    }
  }
}
</style>