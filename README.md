# EasyTier-Web飞牛套件
- EasyTier是一个由 Rust 和 Tokio 驱动的简单、安全、去中心化的异地组网方案。
- EasyTier-Web是为EasyTier提供web管理页面，让用户更直观地管理组网。
### 使用方法：
API主机填飞牛本机ip+11211端口，例如http://192.168.1.3:11211。 初始用户名和密码都是admin，点击登陆后，找到左边侧边栏的设备列表，添加一个新的网络，剩下的操作和其他客户端一样，详情可以看easytier官网介绍。如果想要自定义端口，请在[应用文件]-[Easytier-Web]-config.json中修改，修改后重启应用生效。
### 注意事项：
- 本应用默认占用11211、22020、11010端口，由于11010是easytier服务的默认端口，所以原本运行着easytier程序或容器的，请关闭后再使用本应用，避免冲突。
- 11211为web端端口，可以按照上述的使用方法进行修改。
### 界面截图：
<img width="500" height="350" alt="PixPin_2025-11-17_17-53-22" src="https://github.com/user-attachments/assets/bd12cc0c-6ea4-43be-8c94-8de33317880d" /><img width="500" height="350" alt="PixPin_2025-11-17_17-54-12" src="https://github.com/user-attachments/assets/2bea4c7b-17bd-4730-8e8d-8a58a732395f" />
