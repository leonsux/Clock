# Clock

canvas+JS+面向对象 实现的创意时钟

### 使用方法

1. 在页面中添加 canvas 标签，要有id

    `<canvas id="can"></canvas>`

2. 引入 clock.js 文件

   `<script src="./clock.js"></script>`

3. 创建一个 Clock 对象实例

    ```
    new Clock({
      id: 'can', //必须：页面中canvas的id
      size: 300, //选填（默认300）：canvas大小
      // 一下均为选填，不填则使用缺省值
      bgColor: '', // 背景色
      baseColor: 'red',//基线颜色
      hColor: 'green',//时针颜色
      mColor: 'yellow',//分针颜色
      sColor: 'pink',//秒针颜色
      tColor: 'blue'//文字颜色
    });
    ```
