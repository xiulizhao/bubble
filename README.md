# bubble
气泡标签云元素，用于JS一团气泡文字标签云代码<br>
<img src="http://www.wware.org/img/ee7.jpg?_2566" width="400px"><br>
普通属性<br>
data-fontsize	基本字体大小, 单位px	16<br>
data-radius	滚动半径, 单位px 页面宽度和高度的五分之一	140<br>
data-mspeed	基本字体大小, 单位px滚动最大速度, 取值: slow, normal(默认), fast	slow/normal/fast<br>
data-ispeed	基本字体大小, 单位px滚动初速度, 取值: slow, normal(默认), fast	slow/normal/fast<br>
data-direction	初始滚动方向, 取值角度(顺时针360): 0对应top, 90对应left, 135对应right-bottom(默认)...	135<br>
data-keep	基本字体大小, 单位px鼠标移出组件后是否继续随鼠标滚动, 取值: false, true(默认) 对应 减速至初速度滚动, 随鼠标滚动	false/true<br>
调整css格式如下：<br>
```css
.b01{
    width: 160px;
    height: 160px;
    line-height: 160px;
}
.co01{
    background: -moz-linear-gradient(top, #d1e5fd 0%, #3d86f4 100%);
    background: -webkit-linear-gradient(top, #d1e5fd 0%,#3d86f4 100%);
    background: -o-linear-gradient(top, #d1e5fd 0%,#3d86f4 100%);
    background: -ms-linear-gradient(top, #d1e5fd 0%,#3d86f4 100%);
    background: linear-gradient(to bottom, #d1e5fd 0%,#3d86f4 100%);
}
```
