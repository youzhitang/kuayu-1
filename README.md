 # 使用说明
1. 安装 node-dev
    `yarn global add node-dev`
2. 下载代码 
    `https://github.com/FrankFang/kuayu-1.git`
3. 进入 qq-com 运行 server.js
    `cd kuayu-1/qq-com; node-dev server.js 8888`
4. 进入 frank-com 运行 server.js
    `cd ../tang-com; node-dev server.js 9999`
5. 设置 hosts
  用管理页权限打开记事本，打开 C:\Windows\System32\drivers\etc，文件类型调成所有文件，打开hosts，添加
  ```
      127.0.0.1 qq.com
      127.0.0.1 tang.com
  ```
  注意！不要修改hosts文件原内容！
6. 打开两个页面 qq.com:8888/index.html 和 frank.com:9999/index.html
7. 记得做完之后，删掉 hosts 里的两行，否则 qq.com 无法正常访问！
