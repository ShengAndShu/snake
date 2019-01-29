# snake
一个基于jQuery和canvas的小游戏。
## 使用方法
* 1.引入文件
```
<script src="jquery.min.js"></script>
<script src="snake.js"></script> 
```
* 2.HTML
```
<canvas id="snake""></canvas>
```
* 3.javascript
```
$(function(){
	$('#snake').snake();
});
```
* 4.配置

`color`：Array，设置第一关和第二关蛇的颜色，默认["#000","#ff7600"]<br>
`speed`: Number，设置第一关蛇的速度，默认300<br>
`row`: Number，设置画布行数，默认30行（即300px,单个方块高10px）<br>
`col`: Number，设置画布列数，默认30列（即300px,单个方块宽10px）<br>
`keyWidth`: Number，设置单个虚拟按键的宽度，默认50<br>
