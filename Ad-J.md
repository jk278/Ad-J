[Adblock J Mobile]
! Title: Ad-J
! Version: 0.9.5
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
m.bilibili.com##.large.openapp-dialog
, .visible-open-app-btn.m-video-main-launchapp.launch-app-btn > .m-video2-awaken-btn
, .m-float-openapp.launch-app-btn
, .m-nav-openapp.launch-app-btn
! 播放器弹窗
, .mplayer-widescreen-callapp
! 播放器全屏跳转，解决无法全屏的问题
, .mplayer-fullscreen-call-app
, .home-float-openapp.launch-app-btn
, .mplayer-control-btn-quality
, .mplayer-control-btn-speed

! <h4>**知乎**</h4>  `2022.11.4`
! www.zhihu.com, zhuanlan.zhihu.com
zhihu.com##.is-higher.OpenInAppButton
! 右上角打开app↓↓
! , .Button--blue.MobileAppHeader-downloadLink.Button
, .AdBelowMoreAnswers
, .MHotFeedAd
, .MBannerAd
! 去除盐选推荐，选择使用↓↓
, .KfeCollection-VipRecommendCard
, .Question-main > div > .MBannerAd

! <h4>**简书**</h4>  `2022.11.4`
www.jianshu.com##.header-download
, .app-open
, .note__flow__download
, .index_call-ad
, .border.item
, .call-app-Ad-bottom
, .download
, .footer-wrap > .slogan
, #free-reward-panel
, .no-content > div
, .write-comment
, .recommend-ad.recommend-wrap
, .more
, .comment-open-app-btn-wrap
! 不想看评论的点赞数，删掉 > .reply-btn↓↓
, .comment-item.comment-item > .main > .comment-extra > .social-wrap > .reply-btn
, .line-container
! 要查看当前文章点赞数，不用这条↓↓
, .note-graceful-button
, .flow-list-ul > div > div
, #lwaAdFive 

! <h4>**百度知道**</h4>  `2022.11.4`
zhidao.baidu.com##.question-ads-exp
, #wap-youx-change-asp > div
, .feed-recommend-title
, .dl
, .light-theme.wgt-replies
, .light-theme.feed-recommend.mm-content-line.mm-content-box
, .iknow-fixed-bottom-btn
, .xiqrd6362ad
, .light-theme.single-up-ads-wrapper

! <h4>**百家号**</h4>  `2022.11.4`
baijiahao.baidu.com##.undefined
, .headDeflectorContainer
, .infinite-scroll-component__outerdiv
, .contentPadding.bottomTTSStruct
, div.contentPadding.contentMedia > div
, ._3cAIWshMtS86T-V_NTTzch
, .followSuper

! <h4>**百度经验**</h4>  `2022.11.4`
jingyan.baidu.com###wgt-ad-guess > .ad-card
jingyan.baidu.com##.feed-ad-wrap

! <h4>**csdn**</h4>  `2022.11.17`
! blog.csdn.net, www.csdn.net
csdn.net##.active.feed-Sign-span
, .active.openApp
blog.csdn.net##.wap-shadowbox.weixin-shadowbox
, .btn_open_app_prompt_div
, .add-firstAd
, #comment
www.csdn.net##.m_toolbar_left_app_btn



! <h3>**实用网站类**</h3>
! mba智库, 

! <h4>**mba智库**</h4>  `2022.11.17`
wiki.mbalib.com##.app-ad
, #down-app-pop
, #box-app-tip
, .download_app.news-banner-container
, .ke-lay-in-wiki.ke-lay
, .download_app.download-text



! ----<h3>**国外网站类**</h3>----
! 必应, pixiv, 

! <h4>**必应**</h4>  `2022.11.4`
cn.bing.com##.b_ad
www.bing.com###bnp_set_dse
cn.bing.com##.opal_serpftrc.b_ans

! <h4>**pixiv**</h4>  `2022.11.8`
www.pixiv.net##._gdpr-notify-header
, .description-signup-header
, .ad-frame-container
, .premium-lead-new-t-info-home-top



! <h3>**资讯网站类**</h3>
! 网易新闻, 

! <h4>**网易新闻**</h4>  `2022.11.17`
! 3g.163.com##.bottom, header, .js-topad, .show
3g.163.com##.area-float-card
， .area-card
， .s-info > .s-openApp
， .widget-floatMenu
， footer > span
， .swiper-wrapper
， .js-area-topBanner.area-topBanner
， .js-open-app
， .js-area-content.area-content
， .area-recommend
， .main > div > div



! <h3>**影视网站类**</h3>
! 歪片星球,土拨鼠电影, libvio, 

! <h4>**歪片星球**</h4>  `2022.11.8`
waipian5.com##.rm-h5
, .rm-list.rm-two.player-rm
, .player-recommend-float
, .rm-list.rm-one

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
panduoduo.yangkeduo.com##.pdd-go-to-app
, #devtoolTag
, #recommend-wrapper
, #recommend-head
, .goods-list-container



! <h3>**成人网站类**</h3>
! 九色视频, hello av girls, xnxx, xvideos, pornhub, 

! <h4>**九色视频**</h4>  `2022.11.16`
! 地址页: https://dizhi91.github.io 最新地址其一
github.jiuse370.xyz###main > .row
, .mb-0.jsv-g1.jsv
, #main > .p-0.mb-3.container-fluid
, .d-sm-none.d-block.container-fluid
, .p-0.mb-0.container-fluid
, div.colVideoList:nth-of-type(-n+2)
, #playerAdvLayer
, #videoShowPage > .tab-content
, .text-center.alert-success.alert
, .navTab.row.title

! <h4>**hello av girls**</h4>  `2022.11.8`
www.helloavgirls.com##div.ads.card:nth-of-type(n)
, div.mobile_ad:nth-of-type(n)
, .right-columns.card-columns > div.card:nth-of-type(2)
, .right-columns.card-columns > div.card:nth-of-type(4)
, .right-columns.card-columns > div.card:nth-of-type(5)
, .right-columns.card-columns > div.card:nth-of-type(7)

! <h4>**xnxx**</h4>  `2022.11.8`
www.xnxx.com###ad-header-mobile-contener
, .video-ad-support-mobile.video-ad.thumb-block
, content-ad-top-zone-contener
, .premium-results-line
, .is-filled.ad-support-mobile.ad-mobilerectangle
, site-nav > .gold-plate
, #mobile-menu .gold-plate
, .ad-support-mobile.is-filled.exo-ad-ins-container
, #x-home-messages
, .videoad-base

! <h4>**xvideos**</h4>  `2022.11.8`
www.xvideos.com##.ad-support-mobile.is-filled.exo-ad-ins-container
, .remove-ads
, .red-ticket.red-label.label.btn-default.btn
, .mobile-show-inline-block.badge
, #mobile-slogan > .mobile-slogan-red.btn > .icf-white-fill.icf-ticket-red.icon-f
, .videoad-base
, .video-ad-support-mobile.video-ad.thumb-block
, #ad-header-mobile-contener

! <h4>**pornhub**</h4>  `2022.11.9`
cn.pornhub.com##.adContainer
, .topAdContainter
, .delay.closeUrl


! <h3>**未分类**</h3>
! 

m.baidu.com##.ec_wise_ad
m.baidu.com##.c-video-container
weibo.cn##.wrap, .ad-wrap
18comic.vip##.visible-sm.visible-xs.bot-per
reddit.com##.XPromoPill

microsoftedge.microsoft.com###banner
www.userscript.zone##.top.searcad.col-12

