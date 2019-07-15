<template>
  <div class="register">
    <p class="top">当前位置：门店 > 会员管理 > 会员注册</p>
    <div class="con">
      <div class="left">
        <h1>会员基本信息</h1>
        <img src="./../../img/组 9@2x(3).png" alt="头像" />
        <div>
          <span></span>
          <span></span>
        </div>
      </div>
      <div class="right">
        <p>
          <span class='span'>姓名<span>*</span></span>
          <input type="text" />
        </p>
        <p>
          <span class='span'>手机号<span>*</span></span>
          <input type="text" />
        </p>
        <p>
          <span class='span'>证件号<span>*</span></span>
          <input type="text" />
        </p>
        <p>
          <span class='span'>邮件</span>
          <input type="text" />
        </p>
        <p>
          <button>保存</button>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
.register {
  width: 1066px;
  height: 555px;
  background: rgb(240, 249, 255);
  box-sizing: border-box;
  padding: 20px;
  position: relative;
  .top {
    font-size: 12px;
    position: absolute;
    top: 0px;
    left: 20px;
    color: black;
  }
  .con {
    width: 100%;
    height: 100%;
    background: white;
    overflow: hidden;

    .left {
      float: left;
      margin: 23px 0 0 21px;
      h1 {
        font-size: 18px;
        font-weight: normal;
        color: #333333;
      }
      img {
        width: 110px;
        margin: 77px 0 0 80px;
      }
      div {
        margin: 20px 0 0 114px;
        span {
          display: inline-block;
          width: 25px;
          height: 25px;
          cursor: pointer;
        }
        span:nth-of-type(1) {
          background: url("./../../img/更换@2x.png") no-repeat center center;
          background-size: 25px 25px;
        }
        span:nth-of-type(2) {
          background: url("./../../img/删除筛选项@2x.png") no-repeat center
            center;
          background-size: 25px 25px;
        }
      }
    }
    .right {
      float: left;
      margin: 107px 0 0 140px;
      color:#333333;
      p {
          margin-bottom: 25px;
        .span {
          display: inline-block;
          width: 56px;
          text-align: right;
          span{
              color:red;
          }
        }
        input {
          margin-left: 20px;
          width: 160px;
          height: 35px;
          border-radius: 5px;
          outline: none;
        }
        button{
            margin:25px 0 0 55px;
            width:130px;
            height:50px;
            border:none;
            border-radius: 5px;
            background:#ffd409;
            font-size:18px;
        }
      }
    }
  }
}
</style>