<template>
<article class="toCenter">
    <div class="l_box f_l">
        <div class="l_nav">
            <div class="carousel">
                <app-banner :listImg="listImg"></app-banner>
            </div>
            <div class="nav_info">
                <section class="blogger">
                    <h3>关于博主</h3>
                    <p><span>个人资料：</span>男，九零后，IT男，双子座<p>
                    <p><span>爱好：</span>写作、空想、慢跑、dota、阅读、电影</p>
                </section>
                <section class="event">
                    <h3>ToDoList</h3>
                    <p><span>1、Learn how to control emotions.</span></p>
                </section>
            </div>
        </div>
        <div class="news">
            <h2>最新文章</h2>
            <div class="blog">
            <figure>
                <a href="http://www.sunfei.shop" target="_blank">
                    <img src="../../static/img/home/emotions.jpg" title="曾仕强情绪管理">
                </a>
            </figure>
            <section>
                <h3><a href="http://www.sunfei.shop" target="_blank" title="开始学习情绪管理">开始学习情绪管理</a></h3>
                <p>最后一天的班，总是坐立难安。敲几行代码喝几口茶，写几行文字扯几句天。同组的同事说心已经飞回了家，项目经理却一直在群里喊把心收回来。我百无聊赖得翻着我以前写得文字走了神，好像突然入了一个奇幻梦境，里面悬挂着五颜六色的画...<a href="http://www.sunfei.shop">[详情]</a></p>
                <p class="info">
                    <span class="class f_l"><i class="iconfont">&#xe752;</i><a>情绪管理</a></span>
                    <span class="dateTime f_l"><i class="iconfont">&#xe65f;</i><a>2017-10-05  12:47:24</a></span>
                    <span class="praise f_r"><i class="iconfont">&#xe644;</i><a>0</a></span>
                    <span class="read f_r"><i class="iconfont">&#xe73d;</i><a>浏览（0）</a></span>
                    <span class="comment f_r"><i class="iconfont">&#xe667;</i><a>评论（0）</a></span>
                </p>
            </section>
        </div>
        <div class="blog">
            <figure>
                <a href="http://www.sunfei.shop" target="_blank">
                    <img src="../../static/img/home/family.jpg" title="为何家会伤人">
                </a>
            </figure>
            <section>
                <h3><a href="http://www.sunfei.shop" target="_blank" title="成长环境内化的人格">成长环境内化的人格</a></h3>
                <p>最后一天的班，总是坐立难安。敲几行代码喝几口茶，写几行文字扯几句天。同组的同事说心已经飞回了家，项目经理却一直在群里喊把心收回来。我百无聊赖得翻着我以前写得文字走了神，好像突然入了一个奇幻梦境，里面悬挂着五颜六色的画...<a href="http://www.sunfei.shop">[详情]</a></p>
                <p class="info">
                    <span class="class f_l"><i class="iconfont">&#xe752;</i><a>家庭教育</a></span>
                    <span class="dateTime f_l"><i class="iconfont">&#xe65f;</i><a>2017-10-05  12:47:24</a></span>
                    <span class="praise f_r"><i class="iconfont">&#xe644;</i><a>0</a></span>
                    <span class="read f_r"><i class="iconfont">&#xe73d;</i><a>浏览（0）</a></span>
                    <span class="comment f_r"><i class="iconfont">&#xe667;</i><a>评论（0）</a></span>
                </p>
            </section>
        </div>
        <div class="blog">
            <figure>
                <a href="http://www.sunfei.shop" target="_blank">
                    <img src="../../static/img/home/girls.jpg" title="闪光少女">
                </a>
            </figure>
            <section>
                <h3><a href="http://www.sunfei.shop" target="_blank" title="看《闪光少女》后...">看《闪光少女》后...</a></h3>
                <p>最后一天的班，总是坐立难安。敲几行代码喝几口茶，写几行文字扯几句天。同组的同事说心已经飞回了家，项目经理却一直在群里喊把心收回来。我百无聊赖得翻着我以前写得文字走了神，好像突然入了一个奇幻梦境，里面悬挂着五颜六色的画...<a href="http://www.sunfei.shop">[详情]</a></p>
                <p class="info">
                    <span class="class f_l"><i class="iconfont">&#xe752;</i><a>生活剪影</a></span>
                    <span class="dateTime f_l"><i class="iconfont">&#xe65f;</i><a>2017-10-05  12:47:24</a></span>
                    <span class="praise f_r"><i class="iconfont">&#xe644;</i><a>0</a></span>
                    <span class="read f_r"><i class="iconfont">&#xe73d;</i><a>浏览（0）</a></span>
                    <span class="comment f_r"><i class="iconfont">&#xe667;</i><a>评论（0）</a></span>
                </p>
            </section>
        </div>
        <div class="blog_more">
            <span>点击查看更多&gt;&gt;</span>
        </div>
        </div>
    </div>
    <div class="r_box f_r">
        <div class="concat">
            <h3>关注我</h3>
            <ul class="overflow">
                <li class="f_l"><i class="iconfont sina">&#xe65c;</i><p>新浪微博</p></li>
                <li class="f_l"><i class="iconfont tencent">&#xe600;</i><p>腾讯微博</p></li>
                <li class="f_l"><i class="iconfont mail">&#xe7d8;</i><p>邮箱</p></li>
                <li class="f_l"><i class="iconfont opinion">&#xe608;</i><p>意见反馈</p></li>
            </ul>
        </div>
        <div class="latest">
            <h3>最新文章</h3>
            <ul>
                <li><a href="http://www.sunfei.shop">开始学习情绪管理</a></li>
                <li><a href="http://www.sunfei.shop">成长环境内化的人格</a></li>
                <li><a href="http://www.sunfei.shop">看闪光少女后...</a></li>
            </ul>
        </div>
        <div class="links">
            <h3>友情链接</h3>
            <ul>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
            </ul>
        </div>
    </div>
</article>
</template>

<script>
 import Banner from './templates/Banner.vue'
 import a from '../../static/img/home/banner1.jpg'
 import b from '../../static/img/home/banner2.jpg'
 import c from '../../static/img/home/banner3.jpg'
 import d from '../../static/img/home/banner4.jpg'
 import e from '../../static/img/home/banner5.jpg'
 import f from '../../static/img/home/banner6.jpg'
     export default {
        name: 'Home',
        data() {
            return {
                listImg: [{
                    url: a
                }, {
                    url: b
                }, {
                    url: c
                }, {
                    url: d
                }, {
                    url: e
                },{
                    url: f
                }]
            }
        },
        components: {
            'app-banner': Banner
        }
    };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
article{margin-top:20px;overflow:hidden;}
article .l_box{width:670px;}
article .l_box .l_nav{overflow:hidden;}
article .l_box .l_nav .carousel{width:500px;height:280px;float:left;}
article .l_box .l_nav .nav_info{width:170px;float:right;height:280px;}
article .l_box .l_nav .nav_info h3{font:16px/1.5 "Microsoft Yahei";color:#474645;}
article .l_box .l_nav .nav_info p{font:12px/1.5 "Microsoft Yahei";}
article .l_box .l_nav .nav_info p span{color:#dc2048;}
article .l_box .l_nav .nav_info .blogger{border:1px solid #ffcc00;padding:20px;height:96px;margin-bottom:4px;}
article .l_box .l_nav .nav_info .event{border:1px solid #cceff5;padding:20px;height:96px;}

article .l_box .news{margin:20px 0;}
article .l_box .news h2{font:bold 16px/36px "Microsoft Yahei";border-bottom:4px solid #db6d4c;}
article .l_box .news .blog{padding:30px 0;border-bottom:1px solid #bfab86;overflow:hidden;}
article .l_box .news .blog figure{width:25%;float:left;}
article .l_box .news .blog figure img{width:167.5px;height:137px;display:block;}
article .l_box .news .blog section{float:right;width:72%;}
article .l_box .news .blog section h3{font:bold 16px/22px "Microsoft Yahei";margin-bottom:10px;}
article .l_box .news .blog section p{font:12px/22px "Microsoft Yahei";color:#777976;}
article .l_box .news .blog section p a{color:#759b0a;padding-left:5px;}
article .l_box .news .blog section .info{margin:10px 0;overflow:hidden;}
article .l_box .news .blog section .info a{padding:0 5px;color:#777976;}

article .l_box .news .blog_more{text-align:center;font:16px/40px "microsoft yahei";color:#676568;}

article .r_box{width:300px;}
article .r_box h3{font:18px/40px "microsoft yahei";border-bottom:1px solid #e6e6e6;color:#374659;}
article .r_box .concat ul{margin:30px 0;}
article .r_box .concat ul li{padding:0 16px 0 5px;}
article .r_box .concat ul li i{font:52px/52px "microsoft yahei";}
article .r_box .concat ul li p{font:12px/1.5 "microsoft yahei";margin-top:12px;text-align:center;color:#737f8b;}
article .r_box .concat ul li .sina{color:#fc2922;}
article .r_box .concat ul li .tencent{color:#39c1ff}
article .r_box .concat ul li .mail{color:#019934;}
article .r_box .concat ul li .opinion{color:#1d539b;}

article .r_box .latest ul{margin:10px 0;}
article .r_box .latest ul li{font:12px/25px "microsoft yahei";list-style:square inside;}
</style>
