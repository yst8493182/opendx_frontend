# opendx_frontend编译

#### 1、安装依赖

**npm install --registry=https://registry.npm.taobao.org**

*备注：npm 命令如果没有的话自行百度下载安装*



#### 2、WebStrom配置

* Languages & Frameworks -> Javascript -> Webpack -> {project}\node_modules\@vue\cli-service\webpack.config.js

* Languages & Frameworks -> Javascript -> Libraries -> 勾选node_modules

* Editor -> Inspections -> html -> Empty tag , Unknown html xxx

* 关闭拼写检查：Editor -> Inspections -> Spelling -> typo -> 取消勾选

* 打包配置：Run -> Edit Configurations ->  在左侧增加一个npm配置，其配置内容大致如下：

  <img src="C:\Users\yifeng.huang\AppData\Roaming\Typora\typora-user-images\image-20210421151715036.png" alt="image-20210421151715036" style="zoom:67%;" />

配置完成后，就可以直接运行了

<img src="C:\Users\yifeng.huang\AppData\Roaming\Typora\typora-user-images\image-20210421151958301.png" alt="image-20210421151958301" style="zoom:50%;" />

生成文件路径为 opendx_frontend -> dist

