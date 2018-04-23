## 一、首先得有一台国外或香港的服务器
环境：一台位于香港的CenOS 服务器<br>
         使用 SecureCRT 连接到该台服务器
<br>
<br>
1、新建一个防火墙，点击SecureCRT的 Options --》Global Options，新建一个如下的防火墙（代理），将通过本地127.0.0.1:8887的数据进行socket 5代理转发<br>
<br>![image1](image/1.png);
<br>
2、打开已经准备的香港服务器的Session Options，新建一个本地端口转发规则<br>
<br>![image2](image/2.png);
<br>![image3](image/3.png);
<br>
