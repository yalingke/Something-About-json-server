# Something-About-json-server

一、json-server
参考文档：https://github.com/typicode/json-server

注意：改工具默认启动的服务自带跨域能力
     这个工具已经在服务端处理了跨域的问题，直接请求即可。
     此工具只是测试哪里，真正的场景是需要再客户端解决跨域的，（通用解决方案就是代理服务器）

json-server：一个Node模块，运行Express服务器，通常用于模拟接口，测试数据。
安装：npm install -g json-server
启动
使用总结：
1. 创建一个db.json，写入json数据
2. 启动接口服务(该服务默认占用3000端口) json-server --watch db.json
3. 增删改查：  
      GET/list       查询所有
      GET/list/id    查询单个
      POST/list      添加
      DELETE/list/id 根据id删除
      PATCH/list/id  根据id修改


              
二、接口测试工具：postman


三、http-server
1. 安装：npm i http-server
2. 查看使用帮助 hs -h
3.
 # 默认占用8080端口启动一个服务器，直接打开浏览器
 hs -o
 # 指令占用端口开启服务器
 hs -p 3001 -o
 # 不启动缓存开启
 hs -c-1 -p 3001 -o
