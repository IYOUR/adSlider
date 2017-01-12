1. 项目中必须引入jquery
2. 引入swiper.js和swiper.css文件
3. 在需要使用的地方直接插入一个空的div标签(用class或id进行标识)
4. 在js里进行引用和初始化。例： 文字滚动：$(".one").Adslider({}); 轮播图片：$(".two").Adslider({type:"image:});
5. 参数说明：


参数| 说明
---|---
"type":"text"   | 类型：text/image(默认为text类型)
"textHeight":"30px" | 滚动文字高度
"speed":"5px" | 文字滚动速度
 "time":2000, | 文字滚动时间
"movetime":500 | 滚动文字纵向切换时间
"text":[] | 要滚动的文字内容。 例：["1超市特点:顾客至上。","2超市特点:顾客至上，质优价廉。"]
imageInfo":[] | 要展示的图片信息。 例：[{src:"http://***.jpg",href:"#"},{src:"http://***.jpg",href:"#"}]
"imageHeight":"auto" | 设置展示图片的高度
"round":false | 是否启用图片轮播(仅在多张图片时启用)
