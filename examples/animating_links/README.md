# 说明

使用CSS transition技术来对超链接做点动画效果。

### 本例实现的效果

第一个效果： 增加下划线

第二个效果： 鼠标悬停时，改变链接的背景颜色

第三个效果： 增加背景渐变

### CSS3： Gradient

CSS3 Gradient分为linear-gradient(线性渐变)和radial-gradient(径向渐变)。

#### linear-gradient

其共有三个参数:

- 第一个参数表示线性渐变的方向
- 第二个和第三个参数分别是起点颜色和终点颜色。你还可以在它们之间插入更多的参数，表示多种颜色的渐变。

比如：


```

/* to bottom 是从上到下 */
background: linear-gradient(to bottom,
                            rgba(181, 225, 255, 0) 0%,
                            rgba(181, 225, 255, 0) 50%,
                            rgba(181, 225, 255, 1) 50%,
                            rgba(181, 225, 255, 1) 100%
```

#### radial-gradient

除了在线性渐变中看到的起始位置，方向，和颜色，径向梯度允许你指定渐变的形状（圆形或椭圆形）和大小（最近端，最近角，最远端，最远角，包含或覆盖 (closest-side, closest-corner, farthest-side, farthest-corner, contain or cover)）

```
radial-gradient(#ace 5%, #f96 25%, #1E90FF 50%)

```
