# comment_import_amazon_to_wordpress
## 软件使用前工具准备
1.安装Chrome浏览器：http://chrome.siyue51.fun/（中文） 或者 https://www.google.com/chrome/bsem/download/en_us/（英文需要VPN）  
![RKLG IV}Y3B9~XFFFE_QJYB](https://user-images.githubusercontent.com/44847916/199871031-1f4838d6-5cb6-4cf6-8abe-2e2c243b5c42.png)  
2.Chrome中安装Ryviu插件（收费）：https://chrome.google.com/webstore/search/Ryviu（需要VPN）    
![FQB@G7U{(W`5`J$$ 2_AT{0](https://user-images.githubusercontent.com/44847916/199871110-a2b86109-c01a-4e17-8614-dbd5a74185c5.png)  
## 软件使用前设置
1.选择加载插件目录，插件插件目录一般在：C:\Users\（用户名）\AppData\Local\Google\Chrome\User Data  
![HO71%6F}HHHDAO(GFX}ML%6](https://user-images.githubusercontent.com/44847916/199865531-7d89354d-3cea-4574-a522-494fa2097a3d.png)  
2.创建全新存储产品数据的文件，程序执行完后可以查看文件中的执行结果  
![GN1X5H(UH}QJ)NC@ VF{28V](https://user-images.githubusercontent.com/44847916/199866169-427cc00a-cd45-422a-ae8a-0915d7d0cf80.png)  
## 软件执行设置
1. 站点配置：导入评论站点（必填）、评论来源站点（非必填，默认亚马逊）、产品头字符（必填，不含中括号，没有可放空，一般是域名）、产品末尾随机字符数（非必填，默认8）  
![{LYK}8(4WEF0M3EKX%WK6}3](https://user-images.githubusercontent.com/44847916/199867154-2b2a8563-0b5c-4b8e-ab6e-556b9040ffb7.png)
2. consumer_key和consumer_secret配置：点击保存配置会将当前界面中consumer_key和consumer_secret及插件目录保存到config.txt文件中，默认会优先使用界面中的consumer_key和consumer_secret及插件目录配置，只有在找不到界面配置的情况下才会使用config.txt文件中的consumer_key和consumer_secret配置  
![R9F9ZWR9 FDW~37JC%TS8Q9](https://user-images.githubusercontent.com/44847916/199868261-ce6721d8-8701-48b2-8fe5-76df7676f695.png)
3. consumer_key和consumer_secret需要进入wordpress后台管理平台woocommerce插件设置开发者选项中生成获取
