1. 使用命令行工具切换到项目目录下，全局安装** generator-express ** 
  `$ npm install -g generator-express`
2. 安装完成后， 在命令行内输入 `$ yo express`
  ![](/assets/g-e1.png) 意思是是否创建新的文件作为项目的目录 输入 `n`
  ![](/assets/g-e2.png) 选择所需要的框架 ，这里选择 **MVC**
  ![](/assets/g-e3.png) 选择模板引擎， 这里选择 **Jade**
  ![](/assets/g-e4.png) 是否使用CSS预处理器 ，这里选择 **None**
  ![](/assets/g-e5.png) 选择数据库， 这里选择 **MongoDB**
  ![](/assets/g-e6.png) 选择构建工具， 这里选择 **gulp**
  ![](/assets/g-e7.png) 最后等待安装
3. 在运行项目之前，需要启动 **MondoDB** ，新打开一个命令行窗口输入 `$ mongod` ![](/assets/md.png) 表示**MongodDB**启动成功
4. 在项目目录下打开命令行工具，输入 `$ gulp` 
  ![](/assets/gulp1.png) 
  这个表示运行成功
5. 打开浏览器输入 `http://localhost:3000/`  
![](/assets/g-e8.png) 

