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