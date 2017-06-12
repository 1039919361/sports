<template>
  <div class="my-resume">
    <header class="header">
      我的
    </header>
    <section class="resume-card">
        <div class="myself">
          <dl>
            <dt>
              <img src="../../assets/img/my.jpg" alt="">
            </dt>
            <dd>云卷云舒</dd>
          </dl>
        </div>

        <div class="menu">
          <ul>
            <li class="line">
              <a href="javascript:;">VIP 会员</a>
            </li>
            <li class="line">
              <a href="javascript:;">我的收藏</a>
            </li>
            <li class="line">
              <a href="javascript:;">客服中心</a>
            </li>
            <li class="line">
              <a href="javascript:;">兑换记录</a>
            </li>
            <li class="line">
              <a href="javascript:;">设置</a>
            </li>
          </ul>

        </div>
        <div class="view">
          本App专享：Mr 杨
        </div>
    </section>
  </div>
</template>

<script>
export default {
  data () {
    return {

    }
  }
}
</script>

<style lang="less" scoped>
.my-resume{
  position:absolute;
  top:0;
  left:0;
  right:0;
  height:16.466667rem;
  z-index:888;
  }
  .header{
    width: 100%;
    text-align:center;
    margin-top:.326667rem;
    color:#fff;
    font-size: 16px;
    }
  .resume-card{
    margin-top:16px;
  }
  .myself{
    background: #fff;
    height: 90px;
    dl{
      display: flex;
      padding-left: 10px;
      padding-top: 10px;
      dt{
        width: 70px;
        img{
          width: 100%;
          display: block;
          border-radius: 50px;
        }
      } 
      dd{
        font-size: 14px;
        line-height: 60px;
        margin-left: 20px;
      }
    }
  }

  .menu {
    background: #fff;
    margin-top: 10px;
    ul{
      .blank{
        height: 10px;
        background-color: #f7f7f7;
      }
    li.line{
      padding-left: 20px;
      margin-left: 0;
      border-bottom: 1px solid #eee;
      position: relative;
      ::after{
          content: '';
          display: block;
          width: 15px;
          height: 16px;
          position: absolute;
          top: 18px;
          right: 10px;
          background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAYJJREFUeNqslcErBHEUx2eXJBdntUehPchlIye5UdQWLluSwxRxVKs2t60tBwcns7mRKA7rvrmJv8DBCblIUZKE8fnVm3oHu2Z33qtP3+Yd3nfe+828XyoMQ69RBEGQRiowCHnf93+8FiPdpHgncgobMAtlr41oaMDbfiE3KlXEdMnMQKIENfW8h8lEKwapZmcgo+pBLmFYUk8wToe3JgZikkGuoU9SbnRjmLwmHVF0Hg/uK4J3SQ3BGcYdJgZicoUsQ9TyJOyaGYjJMbKlUit0sW5mIOH+h0P1vIPJdKJD/uPQu5ELGJWUO+wsHT5adOBG9YHMwJ2kemHeakQ6PvU0zAwYURdyAv2SepO9ZdZBFaKV8Q0FxnZvYsDbF5FFldqkeM3kK6J4XkYRzbtKcd/kP6B4DjlQxeuwZrns3EbNSMpt0hwv/5J4Vci6PlfFn2EqTvF/DWRbHsGI+u4X4t4FcTooy30cxSrF65aX/oBKVSi+b33pz8G23Muldv7IXwEGAC7agjacn98NAAAAAElFTkSuQmCC) no-repeat;
          background-size: 80%;
        }
      a{
        height: 48px;
        line-height: 48px;
        color: #666;
        span{
          float: right;
          margin-right: 30px;
        }
      }
    }
  }
}
.view{
  height: 50px;
  line-height: 50px;
  background: #fff;
  text-align: center;
}
</style>
