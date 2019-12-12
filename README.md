### 安装（更新） wepy 命令行工具。
	npm install wepy-cli -g

### 安装依赖包
	npm install

### 开发实时编译。
	wepy build --watch
	
### 开发使用说明(重要)

1、使用微信开发者工具-->添加项目，项目目录请选择dist目录。

2、微信开发者工具-->项目-->关闭ES6转ES5。 <font color=red>重要：漏掉此项会运行报错。</font> 
### 目录结构

    ├── app.wpy                 //入口文件
    ├── components                  //组件
    ├── pages                   //页面
    │   ├── index.wpy         //首屏
    │   ├── form.wpy        //第二屏
    │   └── product.wpy      //第三屏
	