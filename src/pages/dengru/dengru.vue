<template>
  <view class="page">
    <view class="title">快帮网</view>
    <view class="s-title">干啥都行，干啥都快</view>
    <view class="shouji">
      <view class="wrap">
        <image class="icon" src="/static/shouji.png" />
        <input type="text" class="input" placeholder="手机号码" />
      </view>
    </view>
    <view class="yanzheng">
      <view class="wrap">
        <view class="left">
          <image class="icon" src="/static/duanxin.png" />
          <input type="text" class="input" placeholder="短信验证码" />
        </view>
        <view class="btn">获取动态码</view>
      </view>
    </view>
    <view class="btn-dengru">
      <view class="btn">登入</view>
    </view>
    <view class="btn-zhuce">
      <view class="btn">立即注册</view>
    </view>
  </view>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.page {
  .title {
    text-align: center;
    margin-top: 100px;

    height: 33px;
    font-size: 24px;

    font-weight: 500;
    color: #ff552e;
    line-height: 33px;
  }
  .s-title {
    text-align: center;
    margin-top: 10px;
    height: 20px;
    font-size: 14px;
    font-weight: 400;
    color: #ff552e;
    line-height: 20px;
  }
  .shouji {
    margin-top: 40px;

    .wrap {
      width: 80%;
      height: 44px;
      margin-left: auto;
      margin-right: auto;
      display: flex;
      border-radius: 22px;
      border: 3px solid #eeeeee;

      .icon {
        width: 11px;
        height: 18px;
        padding-left: 15px;
        align-self: center;
      }
      .input {
        margin-left: 10px;
        border: none;
        color: #cccccc;
        align-self: center;
      }
    }
  }
  .yanzheng {
    margin-top: 20px;

    .wrap {
      width: 80%;
      margin-left: auto;
      margin-right: auto;
      display: flex;
      justify-content: space-between;

      .left {
        width: 50%;
        height: 44px;
        border-radius: 22px;
        border: 3px solid #eeeeee;
        display: flex;

        .icon {
          width: 17px;
          height: 14px;
          padding-left: 15px;
          align-self: center;
        }

        .input {
          margin-left: 5px;
          font-size: 14px;
          border: none;
          width: 80px;
          color: #cccccc;
          align-self: center;
        }
      }

      .btn {
        text-align: center;
        line-height: 44px;
        width: 40%;
        height: 44px;
        border-radius: 22px;
        border: 3px solid #eeeeee;
        font-size: 14px;
        font-weight: 500;
        color: #0e8ed8;
      }
    }
  }
  .btn-dengru {
    margin-top: 30px;

    .btn {
      width: 80%;
      margin-left: auto;
      margin-right: auto;
      text-align: center;
      height: 44px;
      background: #ff552e;
      color: white;
      border-radius: 22px;
      font-size: 20px;
      line-height: 44px;
    }
  }
  .btn-zhuce {
    margin-top: 40px;

    .btn {
      width: 56px;
      margin-left: auto;
      margin-right: auto;
      height: 20px;
      font-size: 14px;
      font-weight: 400;
      color: #0e8ed8;
      line-height: 20px;
    }
  }
}
</style>