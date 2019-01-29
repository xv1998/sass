# sass

### 这是个配置了scss的微信小程序快速新建模板

### 安装
sass安装命令
```
  $ gem install sass
  $ sass -v
```
### sass命令行
//单文件转换命令
sass input.scss output.css

//单文件监听命令
sass --watch input.scss:output.css

//如果你有很多的sass文件的目录，你也可以告诉sass监听整个目录：
sass --watch app/sass:public/stylesheets


