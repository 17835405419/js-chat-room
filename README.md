# js-chat-room
采用原生js 与 原生node开发的简易聊天室 （持续改进中）

> 启动项目
  * 进入根目录 输入以下命令启动服务器
    * node server.js
    * 或者
    * nodemon server.js
   * 浏览器输入 http://127.0.0.1/login.html 进入登录界面
   
   
   > **注意**
      * 由于没有数据库存储房间信息，当有人切换新房间时，之前的房间在线人员将清空，该部分大bug可自行增加redis等数据库存储数据来解决
      * 代码比较乱，之后会优化（有空的话）
