# rotateNum
引入index.js文件
直接按照下面的格式使用<br>
var dom = document.querySelector(".number")<br>

var digit = new Digit({<br>
    number : 881.12, // 到达指定数值停止滚动<br>
    finish : 3, // 整体完成时间<br>
    speed : 1, // 数值越大，越多数字同时进行翻滚，取值范围（1 ~ 10）<br>
    direction : "right", // 动画方向<br>
    dom: dom, // 在指定dom节点插入动画<br>
})<br>

digit.render() // 执行
