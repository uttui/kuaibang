<template>
  <view class="page">
    <view class="box">
      <view class="s-box on-box">
        <image class="img" src="/static/icon/转让.png" />
        <view class="text">生意转让</view>
      </view>
      <view class="s-box">
        <image class="img" src="/static/icon/房屋出租.png" />
        <view class="text">房屋出租</view>
      </view>
      <view class="s-box">
        <image class="img" src="/static/icon/求租.png" />
        <view class="text">求租</view>
      </view>
    </view>
    <view class="fenlei">
      <view class="fen-box">
        <view class="text">全合肥</view>
        <image class="icon" src="/static/icon/jiantou.png" />
      </view>
      <view class="fen-box">
        <view class="text">价格</view>
        <image class="icon" src="/static/icon/jiantou.png" />
      </view>
      <view class="fen-box">
        <view class="text">面积</view>
        <image class="icon" src="/static/icon/jiantou.png" />
      </view>
      <view class="fen-box">
        <view class="text">更多</view>
        <image class="icon" src="/static/icon/jiantou.png" />
      </view>
    </view>
    <view class="tuijian">
      <image class="img" src="/static/icon/tupian-3.png" />
      <view class="s-box">
        <view class="xiang">合租 | 地矿家园 3室2厅1卫</view>
        <view class="x-text">15平米 南 西客站</view>
        <view class="text">
          <view class="money"> 1458元/月 </view>
          <view class="riqi">2020.4.20</view>
        </view>
      </view>
    </view>
    <view class="tuijian">
      <image class="img" src="/static/icon/tupian-3.png" />
      <view class="s-box">
        <view class="xiang">合租 | 地矿家园 3室2厅1卫</view>
        <view class="x-text">15平米 南 西客站</view>
        <view class="text">
          <view class="money"> 1458元/月 </view>
          <view class="riqi">2020.4.20</view>
        </view>
      </view>
    </view>
    <view class="tuijian">
      <image class="img" src="/static/icon/tupian-3.png" />
      <view class="s-box">
        <view class="xiang">合租 | 地矿家园 3室2厅1卫</view>
        <view class="x-text">15平米 南 西客站</view>
        <view class="text">
          <view class="money"> 1458元/月 </view>
          <view class="riqi">2020.4.20</view>
        </view>
      </view>
    </view>
    <view class="tuijian">
      <image class="img" src="/static/icon/tupian-3.png" />
      <view class="s-box">
        <view class="xiang">合租 | 地矿家园 3室2厅1卫</view>
        <view class="x-text">15平米 南 西客站</view>
        <view class="text">
          <view class="money"> 1458元/月 </view>
          <view class="riqi">2020.4.20</view>
        </view>
      </view>
    </view>
    <view class="tuijian">
      <image class="img" src="/static/icon/tupian-3.png" />
      <view class="s-box">
        <view class="xiang">合租 | 地矿家园 3室2厅1卫</view>
        <view class="x-text">15平米 南 西客站</view>
        <view class="text">
          <view class="money"> 1458元/月 </view>
          <view class="riqi">2020.4.20</view>
        </view>
      </view>
    </view>
  </view>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.page {
  .box {
    margin-top: 20px;
    display: flex;
    justify-content: space-between;
    width: 80%;
    margin-left: 10%;
    height: 85px;

    .s-box {
      width: 60px;
      .img {
        margin-left: 5px;
        width: 48px;
        height: 48px;
      }
      .text {
        font-size: 12px;

        color: #666666;
        text-align: center;
      }
    }
    .on-box {
      width: 60px;

      border-bottom: #ff552e 1px solid;
      height: 85px;
      .text {
        color: #ff552e;
      }
    }
  }
  .fenlei {
    height: 34px;
    background: #f9f9f9;
    display: flex;
    border-top: #eeeeee 1px solid;
    justify-content: space-around;
    .fen-box {
      height: 18px;
      display: flex;
      align-self: center;
      .text {
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 18px;
      }
      .icon {
        width: 8px;
        height: 4px;
        align-self: center;
        margin-left: 3px;
      }
    }
  }
  .tuijian {
    width: 100%;
    height: 100px;
    margin-top: 10px;
    display: flex;
    .img {
      margin-left: 20px;
      margin-top: 10px;
      width: 40%;
      height: 80px;
    }
    .s-box {
      margin-left: 10px;
      margin-top: 15px;
      .xiang {
        font-size: 14px;
        font-weight: 500;
        color: #333333;
        line-height: 17px;
      }
      .x-text {
        margin-top: 5px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
      }
      .text {
        margin-top: 15px;
        justify-content: space-between;
        display: flex;
        .money {
          font-size: 14px;
          color: #ff552e;
        }
        .riqi {
          font-size: 12px;
          color: #999999;
        }
      }
    }
  }
}
</style>