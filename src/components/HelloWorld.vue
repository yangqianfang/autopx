<template>
    <div class="body">
        <div class="logo"></div>
        <div class="content">
            <div class="ticketbox">
                <div class="item item-01">
                    <div class="box">
                        <div class="info">
                            <div class="money"><span>￥</span>25</div>
                            <div class="text">新用户专享用车券</div>
                        </div>
                        <div class="buttonbox">
                            <a
                                role="button"
                                class="am-button button"
                                aria-disabled="false"
                                ><span>立即领取</span></a
                            >
                        </div>
                    </div>
                </div>
                <div class="item item-01">
                    <div class="box">
                        <div class="info">
                            <div class="money"><span>￥</span>25</div>
                            <div class="text">新用户专享用车券</div>
                        </div>
                        <div class="buttonbox">
                            <a
                                role="button"
                                class="am-button button"
                                aria-disabled="false"
                                ><span>立即领取</span></a
                            >
                        </div>
                    </div>
                </div>
                <div class="item item-02">
                    <div class="box">
                        <div class="info">
                            <div class="money">
                                <span>￥</span>50 <span>( 现金 )</span>
                            </div>
                            <div class="text">新用户充50送50</div>
                        </div>
                        <div class="buttonbox">
                            <a
                                role="button"
                                class="am-button button"
                                aria-disabled="false"
                                ><span>立即领取</span></a
                            >
                        </div>
                    </div>
                </div>
            </div>
            <div class="title"><span> 活动规则</span></div>
            <div class="rulebox">
                <p>1、限新用户领取2张面值25元优惠券、充值50元赠送50元。</p>
                <p>2、限除大理外运营城市</p>
                <p>3、禁止恶意刷单，如发现取消新用户礼包资格</p>
                <p>4、如有疑问请拨打客服热线4000888502</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "这里是一段文字",
    props: {
        msg: String,
    },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
    font-size: 16px;
}
h3 {
    margin: 40px 0 0;
}
ul {
    list-style-type: none;
    padding: 0;
}
li {
    display: inline-block;
    margin: 0 10px;
}
a {
    color: #42b983;
}

.body {
    background: url(../assets/images/bg.jpg);
    width: 100%;
    background-size: cover;
    overflow: hidden;
    padding-bottom: 30px;
}
.body .logo {
    width: 149px;
    height: 103px;
    background: url(../assets/images/logo6.png);
    background-size: cover;
    margin: 20px auto 0;
}
.content {
    margin: 500px 30px 0 30px;
    background: #fff;
    height: auto;
    border-radius: 10px;
    padding: 50px;
}

.ticketbox div.item {
    margin-bottom: 10px;
}
.ticketbox .item-01,
.ticketbox .item-02 {
    width: 587px;
    height: 193px;
    margin: 0 auto;
}
.ticketbox .item-01 {
    background: url(../assets/images/item_01.png);
    background-size: cover;
}
.ticketbox .item-02 {
    background: url(../assets/images/item_02.png);
    background-size: cover;
}
.item .box {
    width: 100%;
    height: 100%;

    display: flex;
    justify-content: space-between;
}
.item .box .info {
    padding-left: 50px;
    padding-top: 30px;
    text-align: left;
}

.item .box .buttonbox {
    width: 190px;
    display: flex;
    align-items: center;
}
.item .box .buttonbox .button {
    color: #be6301;
    font-size: 18px;
    text-align: center;
    height: 60px;
    line-height: 60px;
    border-radius: 30px;
    width: 120px;
    margin: 0 auto;
    border: 0;
    background: #fff;
    text-align: center;
}
.item .box .info .money {
    font-size: 58px;
    color: #fff;
    font-weight: bolder;
}
.item .box .info .text {
    font-size: 28px;
    color: #be6301;
}
.item .box .info .money span {
    font-size: 0.12px;
    font-weight: 400;
}
.title {
    border-bottom: 1px solid #ff921c;
    position: relative;
    width: 80%;
    margin: 40px auto 40px auto;
}
.title span {
    position: absolute;
    color: #ff921c;
    left: 50%;
    -webkit-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    background: #fff;
    font-size: 30px;
    padding: 0 10px;
}
.rulebox,
.title span {
    padding: 0 10px;
}
.rulebox p {
    font-size: 26px;
    color: #333;
    text-align: left;
    padding: 0;
    margin: 0;
    line-height: 46px;
}
</style>
