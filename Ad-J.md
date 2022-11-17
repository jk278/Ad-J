[Adblock J Mobile]
! Title: Ad-J
! Version: 0.9.6
! Last modified: 2022.11.17
! powered by Adblock Plus and uBlock Origin
! 自用去广告规则。移动端常用网站。
! 移动端专用。



! <h2>**网站分类**</h2>
! 常用网站类, 实用网站类, 国外网站类, 资讯网站类
! 影视网站类, 购物网站类, 成人网站类, 未分类



! <h3>**常用网站类**</h3>
! 哔哩哔哩, 知乎, 简书, 百度知道, 百家号, 百度经验
! csdn

! <h4>**哔哩哔哩**</h4>  `2022.11.11`
m.bilibili.com##.large.openapp-dialog, .launch-app-btn
! 播放器弹窗
m.bilibili.com##.mplayer-widescreen-callapp
! 播放器全屏跳转，解决无法全屏的问题
m.bilibili.com##.mplayer-fullscreen-call-app
m.bilibili.com##.mplayer-control-btn-quality, .mplayer-control-btn-speed

! <h4>**知乎**</h4>  `2022.11.4`
! www.zhihu.com, zhuanlan.zhihu.com
www.zhihu.com##.is-higher.OpenInAppButton
! 右上角打开app↓↓
! www.zhihu.com##.Button--blue.MobileAppHeader-downloadLink.Button
www.zhihu.com##.AdBelowMoreAnswers, .MHotFeedAd, .MBannerAd
! 去除盐选推荐，选择使用↓↓
www.zhihu.com##.KfeCollection-VipRecommendCard

! <h4>**简书**</h4>  `2022.11.4`
www.jianshu.com##.header-download, .app-open, .note__flow__download
www.jianshu.com##.index_call-ad, .border.item, .call-app-Ad-bottom
www.jianshu.com##.download, .footer-wrap > .slogan, #free-reward-panel
www.jianshu.com##.no-content > div, .write-comment, .recommend-ad
www.jianshu.com##.more, .comment-open-app-btn-wrap, .line-container
www.jianshu.com##.flow-list-ul > div > div, #lwaAdFive
! 不想看评论的点赞数，删掉 > .reply-btn↓↓
www.jianshu.com##.comment-item.comment-item > .main > .comment-extra > .social-wrap > .reply-btn
! 要查看当前文章点赞数，不用这条↓↓
www.jianshu.com##.note-graceful-button 

! <h4>**百度知道**</h4>  `2022.11.4`
zhidao.baidu.com##.question-ads-exp, #wap-youx-change-asp > div, .feed-recommend-title
zhidao.baidu.com##.dl, .light-theme.wgt-replies
zhidao.baidu.com##.light-theme.feed-recommend.mm-content-line.mm-content-box
zhidao.baidu.com##.iknow-fixed-bottom-btn, .xiqrd6362ad, .light-theme.single-up-ads-wrapper

! <h4>**百家号**</h4>  `2022.11.4`
baijiahao.baidu.com##.undefined, .headDeflectorContainer, .infinite-scroll-component__outerdiv
baijiahao.baidu.com##.contentPadding.bottomTTSStruct, div.contentPadding.contentMedia > div
baijiahao.baidu.com##._3cAIWshMtS86T-V_NTTzch, .followSuper

! <h4>**百度经验**</h4>  `2022.11.4`
jingyan.baidu.com###wgt-ad-guess > .ad-card, .feed-ad-wrap

! <h4>**csdn**</h4>  `2022.11.17`
! blog.csdn.net, www.csdn.net
blog.csdn.net##.wap-shadowbox.weixin-shadowbox
blog.csdn.net##.btn_open_app_prompt_div, .add-firstAd, #comment
www.csdn.net##.m_toolbar_left_app_btn
csdn.net##.active.feed-Sign-span, .active.openApp




! <h3>**实用网站类**</h3>
! mba智库, 

! <h4>**mba智库**</h4>  `2022.11.17`
wiki.mbalib.com##.app-ad, #down-app-pop, #box-app-tip, .ke-lay, .download_app



! <h3>**国外网站类**</h3>
! 必应, pixiv, 

! <h4>**必应**</h4>  `2022.11.4`
cn.bing.com##.b_ad, .b_ans
www.bing.com###bnp_set_dse

! <h4>**pixiv**</h4>  `2022.11.8`
www.pixiv.net##._gdpr-notify-header, .description-signup-header
www.pixiv.net##.ad-frame-container, .premium-lead-new-t-info-home-top



! <h3>**资讯网站类**</h3>
! 网易新闻, 

! <h4>**网易新闻**</h4>  `2022.11.17`
3g.163.com##.area-card, .js-open-app, .js-area
3g.163.com##.widget-floatMenu, footer > span
3g.163.com##.main > div > div, .swiper-container-android, .s-openApp



! <h3>**影视网站类**</h3>
! 歪片星球,土拨鼠电影, libvio, 

! <h4>**歪片星球**</h4>  `2022.11.8`
waipian5.com##.rm-h5, .rm-list.rm-two.player-rm
waipian5.com##.player-recommend-float, .rm-list.rm-one

! <h4>**土拨鼠电影**</h4>  `2022.11.9`
www.tbsdy.com##.download_app

! <h4>**libvio**</h4>  `2022.11.9`
www.libvio.me##div.container:nth-of-type(2)
www.libvio.me##.t-img-box



! <h3>**购物网站类**</h3>
! 淘宝, 拼多多, 

! <h4>**淘宝**</h4>  --2022.11.9--
main.m.taobao.com##button
main.m.taobao.com###SLK_evokeUi_v2_wrap

! <h4>**拼多多**</h4>  --2022.11.9--
panduoduo.yangkeduo.com##.pdd-go-to-app, #devtoolTag, #recommend-head
panduoduo.yangkeduo.com###recommend-wrapper, .goods-list-container



! <h3>**成人网站类**</h3>
! 九色视频, hello av girls, xnxx, xvideos, pornhub, 

! <h4>**九色视频**</h4>  `2022.11.16`
! 地址页: https://dizhi91.github.io 最新地址其一
! github.jiuse370.xyz###main > .row, .mb-0.jsv-g1.jsv
github.jiuse370.xyz##.row, .jsv, mb-n
github.jiuse370.xyz###main > .p-0.mb-3.container-fluid, .d-sm-none.d-block.container-fluid
github.jiuse370.xyz##.p-0.mb-0.container-fluid, div.colVideoList:nth-of-type(-n+2)
github.jiuse370.xyz###playerAdvLayer, #videoShowPage > .tab-content
github.jiuse370.xyz##.text-center.alert-success.alert, .navTab.row.title

! <h4>**hello av girls**</h4>  `2022.11.8`
www.helloavgirls.com##div.ads.card:nth-of-type(n)
www.helloavgirls.com##div.mobile_ad:nth-of-type(n)
www.helloavgirls.com##.right-columns.card-columns > div.card:nth-of-type(2)
www.helloavgirls.com##.right-columns.card-columns > div.card:nth-of-type(4)
www.helloavgirls.com##.right-columns.card-columns > div.card:nth-of-type(5)
www.helloavgirls.com##.right-columns.card-columns > div.card:nth-of-type(7)

! <h4>**xnxx**</h4>  `2022.11.8`
www.xnxx.com###ad-header-mobile-contener
www.xnxx.com##.premium-results-line
www.xnxx.com##.gold-plate
www.xnxx.com##.ad-support-mobile
www.xnxx.com###x-home-messages, .videoad-base

! <h4>**xvideos**</h4>  `2022.11.8`
www.xvideos.com##.ad-support-mobile.is-filled.exo-ad-ins-container
www.xvideos.com##.remove-ads, .mobile-show-inline-block.badge
www.xvideos.com##.red-ticket.red-label.label.btn-default.btn
www.xvideos.com###mobile-slogan > .mobile-slogan-red.btn > .icf-white-fill.icf-ticket-red.icon-f
www.xvideos.com##.videoad-base, #ad-header-mobile-contener
www.xvideos.com##.video-ad-support-mobile.video-ad.thumb-block


! <h4>**pornhub**</h4>  `2022.11.9`
cn.pornhub.com##.adContainer, .topAdContainter, .delay.closeUrl


! <h3>**未分类**</h3>
! 

m.baidu.com##.ec_wise_ad
m.baidu.com##.c-video-container
weibo.cn##.wrap, .ad-wrap
18comic.vip##.visible-sm.visible-xs.bot-per
reddit.com##.XPromoPill

microsoftedge.microsoft.com###banner
www.userscript.zone##.top.searcad.col-12

