# rotateNum
引入index.js文件
直接按照下面的格式使用
var dom = document.querySelector(".number")

var digit = new Digit({
    number : 881.12, // 到达指定数值停止滚动
    finish : 3, // 整体完成时间
    speed : 1, // 数值越大，越多数字同时进行翻滚，取值范围（1 ~ 10）
    direction : "right", // 动画方向
    dom: dom, // 在指定dom节点插入动画
})

digit.render() // 执行
