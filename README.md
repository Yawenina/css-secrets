# css-secrets

《CSS Secrets》 Source Code.

Demo: https://codepen.io/Yaweninan/project/editor/AYyQxM

## Chap1. 背景与边框

### 1.1 半透明边框
  - `background-clip`：指定背景图/色延伸的范围。默认值`border-box`。
![Background-clip](http://p197ycwdx.bkt.clouddn.com/background-clip.png)

### 1.2 多重边框
  - `box-shadow`：可以用逗号分隔多个值，形成多重边框的效果。把偏移、投影设置为0，正值的扩张半径。
  - `outline`: 只能支持两重边框(border + outline)。边框的样式比较多。不贴合圆角。
![multiple-borders](http://p197ycwdx.bkt.clouddn.com/multiple-borders.png)

### 1.3 灵活的背景图
  - `right, bottom`: 定位背景图的位置可以通过关键字指定相对哪个角的位移了。注意回退。
  - `calc()`: 进行灵活处理。
  - `background-origin`: 指定左上角的角是`content`, `padding`, `border`。
![background-origin](http://p197ycwdx.bkt.clouddn.com/background-origin.png)
  

### 1.4 条纹背景
  - `linear-gradient`: 如果渐变色的位置相同，则颜色会在该位置突然变化。
  - 如果某个颜色的位置比他之前的位置都要小，那么它的值为之前的最大位置。
  - `repeating-linear-gradient`: 色标无限重复，直到填满整个背景。
![striples](http://p197ycwdx.bkt.clouddn.com/striples.png)
  