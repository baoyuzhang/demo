## CSS3实现页面平滑过渡
[【效果预览】](https://baoyuzhang.github.io/demo/css3/Transition/Transition.html)
1. 分析动画效果
2. 使用@font-face引入自定义的字体
3. 使用transform变换实现平移、旋转
4. 使用transition实现过渡动画
5. 使用animaition和keyframes定义动画


#### 元素不可见：
  - `display: none;`：隐藏不占位
  - `display: hidden;`：隐藏占位
	- `visibility: hidden;`：隐藏占位
  - `position: absolute;left: -99999px;`
	- `opacity: 0;`：在原来位置，只是透明度为0

#### ~ 和 + 均用于并列元素，区别在于：

- `#id ~ a`：id后面所有的a，只要在后面的都包括，不强调紧跟<br>
- `#id + a`：紧跟在id后面的一个a

#### CSS3动画：
- `transition`：需要事件触发
- `animation`：不需要事件触发
