<template>
  <view class="page">
    <view class="head">
      <image class="touxiang" src="/static/touxiang.png" />
      <view class="name">LIUHAIBING</view>
      <view class="box">
        <view class="xinxi">
          <image class="icon" src="/static/icon/信息@3x.png" />
          <view class="text">我的信息</view>
        </view>
        <view class="fabu">
          <image class="icon" src="/static/icon/发布@3x.png" />
          <view class="text">发布</view>
        </view>
      </view>
    </view>
    <view class="title-text"> 我发布的 </view>
    <view class="fenlei">
      <view class="text on-text">房产</view>
      <view class="text">招聘</view>
      <view class="text">求职</view>
      <view class="text">二手</view>
      <view class="text">万能帮</view>
      <view class="text">快购</view>
      <image class="icon" src="/static/icon/jiantou-2.png" />
    </view>
    <view class="title-box">
      <image class="icon" src="/static/icon/tupian-3.png" />
      <view class="box">
        <view class="box-title">业主直转！淮河路步行街旺铺餐馆，接手即赚</view>
        <view class="s-box">
          <view class="riqi">2020.04.15</view>
          <view class="bianji">
            <view class="text">编辑</view>
          </view>
          <view class="chakan">
            <view class="text">查看详情</view>
          </view>
        </view>
      </view>
    </view>
    <view class="title-box">
      <image class="icon" src="/static/icon/tupian-3.png" />
      <view class="box">
        <view class="box-title">业主直转！淮河路步行街旺铺餐馆，接手即赚</view>
        <view class="s-box">
          <view class="riqi">2020.04.15</view>
          <view class="bianji">
            <view class="text">编辑</view>
          </view>
          <view class="chakan">
            <view class="text">查看详情</view>
          </view>
        </view>
      </view>
    </view>
    <view class="title-box">
      <image class="icon" src="/static/icon/tupian-3.png" />
      <view class="box">
        <view class="box-title">业主直转！淮河路步行街旺铺餐馆，接手即赚</view>
        <view class="s-box">
          <view class="riqi">2020.04.15</view>
          <view class="bianji">
            <view class="text">编辑</view>
          </view>
          <view class="chakan">
            <view class="text">查看详情</view>
          </view>
        </view>
      </view>
    </view>
    <view class="jiewei"> 
        <view class="box">
            <view class="text">意见反馈</view>
            <image class="icon" src="/static/icon/jiantou-2.png">
        </view>
        <view class="box">
            <view class="text">联系客服</view>
            <image class="icon" src="/static/icon/jiantou-2.png">
        </view>
    </view>
  </view>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.page {
  .head {
    height: 117px;
    background: #ff9d87;
    display: flex;
    position: relative;
    .touxiang {
      margin-top: 20px;
      margin-left: 50px;
      width: 50px;
      height: 50px;
    }
    .name {
      margin-top: 28px;
      margin-left: 20px;
      font-size: 24px;
      font-weight: 400;
      color: #ffffff;
      line-height: 33px;
    }
    .box {
      margin-left: 7%;
      width: 85%;
      height: 55px;
      background: #ffffff;
      border-radius: 10px;
      border: 1px solid #eeeeee;
      position: absolute;
      top: 85px;
      display: flex;
      justify-content: space-around;
      .xinxi {
        margin-top: 20px;
        width: 50%;
        height: 21px;
        display: flex;
        border-right: #eeeeee 1px solid;
        
        .icon {
          margin-left: 25%;
          width: 24px;
          height: 20px;
        }
        .text {
          margin-left: 10px;
          align-self: center;
          width: 56px;
          height: 20px;
          font-size: 14px;
          font-weight: 400;
          color: #333333;
          line-height: 20px;
        }
      }
      .fabu {
        margin-right: auto;
        margin-top: 20px;
        width: 50%;
        height: 21px;
        display: flex;
        .icon {
          margin-left: 25%;
          width: 24px;
          height: 20px;
        }
        .text {
          margin-left: 10px;
          align-self: center;
          width: 56px;
          height: 20px;
          font-size: 14px;
          font-weight: 400;
          color: #333333;
          line-height: 20px;
        }
      }
    }
  }
  .title-text {
    margin-top: 50px;
    margin-left: 20px;
    font-size: 16px;
    font-weight: 500;
    color: #333333;
    line-height: 22px;
  }
  .fenlei {
    height: 30px;
    margin-top: 11px;
    border-bottom: #eeeeee 1px solid;
    display: flex;
    margin-bottom: 10px;
    justify-content: space-between;
    margin-right: 10px;
    .text{
      height: 30px;
      width: 60px;
      text-align: center;
      font-size: 14px;
      color: #333333;
    }
    .on-text{
      height: 30px;
      width: 60px;
      text-align: center;
      font-size: 14px;
      font-weight: 400;
      color: #ff552e;
      line-height: 20px;
      border-bottom: #ff552e 1px solid;
    }
    .icon{
      width: 14px;
      height: 7px;
      background: #0e8ed8;
      top: 23%;
    }
    // .fangchan {
    //   height: 30px;
    //   width: 60px;
    //   text-align: center;
    //   font-size: 14px;
    //   font-weight: 400;
    //   color: #ff552e;
    //   line-height: 20px;
    //   border-bottom: #ff552e 1px solid;
    // }
    // .zhaopin {
    //   height: 30px;
    //   width: 60px;
    //   text-align: center;
    //   font-size: 14px;
    //   font-weight: 400;
    //   color: #333333;
    //   line-height: 20px;
    // }
    // .icon {
    //   width: 14px;
    //   height: 7px;
    //   background: #0e8ed8;
    //   margin-left: 5px;
    //   margin-top: 7px;
    //   margin-right: 3px;
    // }
  }
  .title-box {
    display: flex;
    margin-left: 10px;
    height: 100px;
    border-bottom: #eeeeee 1px solid;
    .icon {
      margin-top: 10px;
      margin-left: 10px;
      width: 43%;
      height: 80px;
      background: #ff9d87;
    }
    .box {
      .box-title {
        margin-top: 10px;
        margin-left: 10px;
        font-size: 14px;
        font-weight: 400;
        color: #333333;
        line-height: 20px;
      }
      .s-box {
        margin-top: 10px;
        margin-left: 10px;
        display: flex;
      }
      .riqi {
        margin-top: 5px;
        font-size: 10px;
        font-weight: 400;
        color: #666666;
        line-height: 14px;
      }
      .bianji {
        margin-left: 20px;
        width: 52px;
        height: 24px;
        background: #ffffff;
        border-radius: 12px;
        border: 1px solid #0e8ed8;
        .text {
          margin-top: 5px;
          text-align: center;
          font-size: 10px;
          font-weight: 500;
          color: #0e8ed8;
          line-height: 14px;
        }
      }
      .chakan {
        margin-left: 5px;
        width: 62px;
        height: 24px;
        background: #ffffff;
        border-radius: 12px;
        border: 1px solid #ff552e;
        .text {
          margin-top: 5px;
          text-align: center;
          font-size: 10px;
          font-weight: 400;
          color: #ff552e;
          line-height: 14px;
        }
      }
    }
  }
  .jiewei {
    margin-top: 20px;
    margin-left: 20px;
    margin-right: 20px;
    margin-bottom: 40px;
    .box{
      margin-top: 10px;
      display: flex;
      justify-content: space-between;
      .text{
        font-size: 14px;
        font-weight: 400;
        color: #333333;
        line-height: 20px;
      }
      .icon{
        margin-top: 3px;
        width: 8px;
        height: 15px;
      }
    }
    // .yijian {
    //   display: flex;
    //   .text {
    //     font-size: 14px;
    //     font-weight: 400;
    //     color: #333333;
    //     line-height: 20px;
    //   }
    //   .yi-icon {
    //     margin-top: 3px;
    //     margin-left: 80%;
    //     width: 8px;
    //     height: 15px;
    //   }
    // }
    // .lianxi {
    //   display: flex;
    //   margin-top: 10px;

    //   .text {
    //     font-size: 14px;
    //     font-weight: 400;
    //     color: #333333;
    //     line-height: 20px;
    //   }
    //   .lian-icon {
    //     margin-top: 3px;
    //     margin-left: 80%;
    //     width: 8px;
    //     height: 15px;
    //   }
    // }
  }
}
</style>