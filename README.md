这是uwp图片动态加载的库
工作原理：
1异步加载，不卡主线程
2网络拿到图片后会保存在内容和本地中，下次访问同样网址则不再重复请求，节省流量和增加流畅性
