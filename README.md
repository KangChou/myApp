# myApp
CV and NLP (vue,python,flask,java,web,c++)
![image](https://github.com/KangChou/myApp/assets/36963108/0d91d877-54f5-4586-98bd-bc63303a6d87)


# 项目1：VUE 与 flask 前端交互
![image](https://github.com/KangChou/myApp/assets/36963108/69033173-bf7d-4da9-bc31-9c6ff050f1a0)

# 项目2：VUE 与 flask 前端交互  计算器
![image](https://github.com/KangChou/myApp/assets/36963108/58cbe365-6fee-420b-b4d2-ae2de09453fc)

# 项目3：VUE 与 flask 前端交互  计算器界面优化
![image](https://github.com/KangChou/myApp/assets/36963108/f0a2c5f3-20c0-4b98-9a66-0dc460b08803)


# 项目4：VUE 与 flask 前端交互  opencv抓取摄像头
![image](https://github.com/KangChou/myApp/assets/36963108/320f116c-0ea0-44bf-8549-3a74d920cf92)

# 项目5：VUE 与 flask 前端交互  opencv抓取摄像头人脸检测
![image](https://github.com/KangChou/myApp/assets/36963108/2d715446-fc4c-4ca2-ab14-57590c354370)


# 项目6：CLIP_explainability.ipynb使用了 OpenAI 的 CLIP 模型，该模型能够同时理解图像和文本，并计算它们之间的相似性得分。通过预处理图像和文本，并在模型上进行推理，可以获取图像和文本之间的相似性分数。
随后，通过解释性分析技术，特别是使用了注意力机制，对模型的关注点进行可视化，生成了热图，展示了模型对输入图像和文本的关注程度。这使得用户可以更深入了解模型是如何理解和关联图像及文本的。




# 环境配置

```
在myvue目录下运行Vue项目：







运行npm install可以安装package.json之中的依赖
（这将根据package.json文件中的依赖项列表，自动下载和安装所需的包到node_modules目录中。）
在终端或命令提示符中，运行以下命令全局安装Vue CLI：
npm install -g @vue/cli
python server.py
npm run serve


在项目根目录下执行以下命令，清除旧的构建缓存并重新安装依赖:
$ npm cache clean --force
$ rm -rf node_modules
$ npm install




{
  "name": "myvue", // 项目名称
  "version": "1.0.0", // 项目版本号
  "description": "My Vue project", // 项目描述
  "scripts": {
    "serve": "vue-cli-service serve", // 运行开发服务器的命令
    "build": "vue-cli-service build" // 构建生产版本的命令
  },
  "dependencies": {
    "vue": "^2.6.14" // 项目所依赖的Vue版本
  },
  "devDependencies": {
    // 开发环境所依赖的包
  },
  "author": "Your Name", // 作者名称
  "license": "MIT" // 许可证类型
}




{
  "name": "myvue",
  "version": "1.0.0",
  "private": true,
  "scripts": {
    "serve": "vue-cli-service serve"
  },
  "dependencies": {
    "vue": "^2.6.14"
  },
  "devDependencies": {
    "@vue/cli-service": "^4.5.14",
    "@vue/compiler-sfc": "^2.6.14"
  }
  
}

```
