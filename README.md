# OopStorm 团队博客

OopStorm 团队博客，欢迎分享自己的知识。

## 发布文章

1. 编写 Markdown 文件，并放置到 /source/_posts 中即可

2. 需要设置标题，否则会显示 `[Untitled Post]`

		// 标题设置方法
		在 Markdown 文件头部加入以下文本即可
		
		---
		title: Hello World
		---

## 修改样式

> 基本样式修改

	找到以下文件
	/themes/archer/_config.yml
	
	# ========== 资料栏 ========== #
	# avatar 团队头像
	avatar: /avatar/OopStorm.jpg
	# author 团队名
	author: OopStorm
	# signature 团队名下面的子标题
	signature: 团队博客
	# SNS 各种链接
	social:
	  email: 12345@qq.com
	  github: //github.com/fi3ework
	  # wechat and qq should be a path of qr-code image
	  wechat: /assets/example_qr.png
	  qq: 
	  weibo: 
	  zhihu: 
	  douban: 
	  facebook: 
	  twitter: 
	  instagram: 
	  stack-overflow: 
	  v2ex: 
	  linkedin: 
	  others: 
	  rss: 
	# member 成员 
	friends:
	  AlphaHinex: //alphahinex.github.io
	  devilx: //www.jianshu.com/u/3aad53dec75f
	  friendC: 
	# about 关于
	about:
	  enable: true
	  image: '/intro/about-bg.jpg'
	
	# ========== 站点 ========== #
	# 浏览器标题
	SEO_title: OopStorm
	# 主标题
	main_title: OopStorm
	# 子标题
	subtitle: It's better to burn out than to fade away
	# 首页顶部背景图
	site_header_image: '/intro/index-bg.jpg'
	# 文章顶部背景图
	post_header_image: '/intro/post-bg.jpg'
	# 404 背景图
	_404_image: '/intro/404-bg.jpg'
	
	# ========== 评论插件 ========== #
	# 目前支持直接添加 Livere，Disqus，Gitment，畅言及友言，填写插件对应的字段即可启用。
	# 如果想添加其他评论插件，在 custom.ejs 中添加即可。
	comment:
	  # Livere  site: https://livere.com/
	  livere_uid: 
	  # Disqus  site: https://disqus.com/
	  disqus_shortname: 
	  # Changyan  site: http://changyan.kuaizhan.com/
	  changyan_appid: 
	  changyan_conf: 
	  # Gitment  site: https://github.com/imsun/gitment
	  gitment_owner: 
	  gitment_repo: 
	  gitment_client_id: 
	  gitment_client_secret: 
	  # Youyan  site: http://www.uyan.cc/
	  youyan_uid: 
	
	# ========== 统计 ========== #
	# 是否开启不蒜子阅读量统计
	busuanzi: true
	# 百度统计(填写siteID)
	baidu_analytics:
	# Google统计(填写siteID)
	google_analytics:
	# CNZZ统计
	CNZZ_analytics:
	
	# ========== 其他 ========== #
	# 浏览器地址前的小标题
	favicon: /assets/favicon.ico
	# 首页的文章摘要字数(默认300，填0则不显示摘要)
	truncate_length: 
	# enable toc
	toc: true
	# intro height (默认是屏幕高度的50%, 可以直接输入其他数字)
	index_intro_height: 50
	post_intro_height: 50
	about_intro_height: 50

> 深度修改样式

自行在 /themes/archer/layout 中寻找对应的文件进行修改


## 更换主题

1. 下载新的主题
2. 将主题放入 /themes 中
3. 修改 /_config.yml 中的 theme 参数为新的主题