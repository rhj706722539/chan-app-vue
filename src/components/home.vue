<template>
  <section>
        <div class="nav">
            <ul>
                <li>店员奖励</li>
                <label><i class="icon iconfont">&#xe6d7;</i></label>
                <p class="rt" id="screen-icon"><i class="icon iconfont">&#xe711;</i></p>
            </ul>
            <div class="amount">
                <p>账户余额（元）</p>
                <p>13458.89</p>
            </div>
            <div class="sub-bg">
                <ul>
                    <li>
                        <p class="fz">8038.98</p>
                        <p>累计奖励（元）</p>
                    </li>
                    <li>
                        <p class="fz">8038.98</p>
                        <p>冻结金额（元）</p>
                    </li>
                    <li>
                        <p class="fz">8038.98</p>
                        <p>可转金额（元）</p>
                    </li>
                </ul>
                <!--<div class="side-md"></div>-->
            </div>
        </div>
        <section class="khfxWarp clerk">
            <section class="m-jz-clerk">
                <div class="m-tt" id="channelTitle">
                    <ul>
                        <li>热门活动</li>
                        <li class="rt"><i class="icon iconfont">&#xe65d;</i></li>
                    </ul>
                </div>
                <div class="m-aw-lst">
                    <ul>
                        <li class="rt">
                            <p class="bt">活动名称活动名称活动名称</p>
                            <p class="ft">2017/09/30 ~ 2017/10/09</p>
                        </li>
                    </ul>
                    <ul>
                        <li class="rt">
                            <p class="bt">活动名称活动名称活动名称</p>
                            <p class="ft">2017/09/30 ~ 2017/10/09</p>
                        </li>
                    </ul>
                    <ul>
                        <li class="rt">
                            <p class="bt">活动名称活动名称活动名称</p>
                            <p class="ft">2017/09/30 ~ 2017/10/09</p>
                        </li>
                    </ul>
                </div>
            </section>
        </section>
        <section class="khfxWarp report">
            <section class="m-jz-clerk">
                <div class="m-tt" id="channelTitle">
                    <ul>
                        <li>我的上报</li>
                        <li class="rt"><i class="icon iconfont">&#xe65d;</i></li>
                    </ul>
                </div>
                <div class="m-aw-lst mb-bd">
                    <ul>
                        <li class="lt">
                            <div>￥10</div>
                            <div>奖励冻结</div>
                        </li>
                        <li class="rt">
                            <p class="bt">活动名称活动名称活动名称</p>
                            <p class="ft">活动时间：2017/09/30 ~ 2017/10/09</p>
                            <p class="ft">业务号码：12131311</p>
                        </li>
                    </ul>
                    <ul>
                        <li class="lt">
                            <div>￥10</div>
                            <div>奖励冻结</div>
                        </li>
                        <li class="rt">
                            <p class="bt">活动名称活动名称活动名称</p>
                            <p class="ft">活动时间：2017/09/30 ~ 2017/10/09</p>
                            <p class="ft">业务号码：12131311</p>
                        </li>
                    </ul>
                    <ul>
                        <li class="lt">
                            <div>￥10</div>
                            <div>奖励冻结</div>
                        </li>
                        <li class="rt">
                            <p class="bt">活动名称活动名称活动名称</p>
                            <p class="ft">活动时间：2017/09/30 ~ 2017/10/09</p>
                            <p class="ft">业务号码：12131311</p>
                        </li>
                    </ul>
                </div>
            </section>
        </section>
        <section>
            <div class="m-ft-btn">
                <div class="m-not-btn">
                    <a href="#" class="btn btn-green-border btn-large">奖励提取</a>
                    <a href="#" class="btn btn-green-bj btn-large fr">销量上报</a>
                </div>
            </div>
        </section>
    </section>
</template>
<script>
    export default {
    name: 'home',
    data () {
        return {
        msg: 'Welcome to Your Vue.js App'
        }
    }
    }
</script>
<style scoped>
.nav {
    height: auto;
    background-color: #30CA79;
}
.nav ul li {
    color: #fff;
}
.nav label i {
    color: #fff;
}
.nav ul .rt i {
    color: #fff;
}
.amount {
padding: 0.5rem;
width: 100%;
float: left;
text-align: center;
color: #fff;
}
.amount p:first-child {
	font-size: 0.68rem;
}
.amount p:last-child {
	font-size: 1.5rem;
}
.sub-bg {
	width: 100%;
	overflow: hidden;
    padding-bottom: 0.5rem;
}
.sub-bg ul li {
	float: left;
    width: 33.3333%;
    text-align: center;
    line-height: normal;
    font-size: 0.512rem;
}
.fz {
	font-size: 0.9rem;
}
.m-tt{float:left;width:100%;height:1.493rem;border-bottom:1px solid #e8e8e8;}
.m-tt ul li{float:left;line-height:1.493rem;font-size:0.597rem;color:#111}
.m-tt ul .rt{float:right}
.m-tt ul .rt i{float:left;/*margin-top:0.1rem;*/font-size:0.58rem;color:#d4d4d4}
.clerk {
	margin-top: 8.1rem;
	overflow: hidden;
}
.report {
	margin-top: 0.42rem;
	overflow: hidden;
}
.m-jz-clerk {
	float: left;
    padding: 0 0.5333rem;
    width: 100%;
    height: auto;
    background: #fff;
}
.m-aw-lst {
	float: left;
    width: 100%;
}
.m-aw-lst ul {
	float: left;
    width: 100%;
	overflow: hidden;
    height: auto;
	border-bottom: 1px solid #e8e8e8;
}
.m-aw-lst ul li {
	float: left;
}
.m-aw-lst ul .rt {
	width: 14.85rem;
    padding: 0.34rem 0;
    float: right;
}
.m-aw-lst ul .rt p {
	font-size: 0.512rem;
    color: #999;
}
.m-aw-lst ul .rt .bt {
    font-size: 0.64rem;
    color: #111;
    margin-bottom: 0.2rem;
}
.mb-bd ul .lt {
	width: 2.8rem;
    text-align: center;
    line-height: normal;
    padding: 0.34rem;
}
.mb-bd ul .lt div:first-child {
	font-size: 0.768rem;
	color: #F5822B;
	margin-bottom: 0.3rem;
}
.mb-bd ul .lt div:last-child {
	font-size: 0.512rem;
}
.mb-bd ul .rt {
	width: 12rem;
	line-height: normal;
	padding: 0.34rem 0;
}
.mb-bd ul .rt .bt {
	font-size: 0.64rem;
	color: #111;
	margin-bottom: 0.2rem;
}
.m-jz-lst ul .rt p {
	font-size: 0.512rem;
	color: #999;
}
.m-ft-btn {
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
}
.m-not-btn {
    float: left;
    padding: 0 0.53rem;
    width: 100%;
    height: 2.77rem;
    text-align: center;
    background: #fff;
    box-shadow: 0 0 0 green, 0 -2px 10px #ccc, 0 0 0 red, 0 0 0 yellow;
}
.m-not-btn a {
    float: left;
    margin-top: 0.45rem;
    width: 7.25rem;
    height: 1.877rem;
    text-align: center;
    line-height: 1.87rem;
    border-radius: 0.12rem;
}
.m-not-btn .fr {
    float: right;
}
.m-not-btn .btn-green-bj {
    background: #00ce6d;
    color: #fff;
    font-size: 0.768rem;
}
.m-not-btn .btn-green-border {
    border: 1px solid #00ce6d;
    color: #00ce6d;
    font-size: 0.768rem;
}
</style>
