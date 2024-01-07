说明：由于没有可用的梯子，找一个英文网页实现翻译为中文并保存为PDF文件，及下载为ZIP文件，完成了后面的功能。 



实现思路：

1、以天府银行官网英文版为例，通过爬虫技术Jsoup解析网页document，分别对图片和文字进行抓取，通过正则表达式过滤需要翻译的英文文本；


2、将抓取的英文文本调用百度翻译接口进行翻译并输出到PDF，备注：需使用百度翻译账号； 


3、将图片和翻译的文本使用itex组件输出到PDF文件并保存；


4、实现将PDF文件通过zip打包，下载。
