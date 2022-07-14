# ServerStatus-Hotaru-OneCloud
云探针、多服务器探针、云监控、多服务器云监控

## 基于 ServerStatus-Hotaru 最新版本稍作修改支持玩客云。

## 我的玩客云信息如下

```
cat /proc/version      
Linux version 5.18.0-rc3-meson (root@fv-az292-769) (arm-linux-gnueabihf-gcc (GNU Toolchain for the A-profile Architecture 8.3-2019.03 (arm-rel-8.36)) 8.3.0, GNU ld (GNU Toolchain for the A-profile Architecture 8.3-2019.03 (arm-rel-8.36)) 2.32.0.20190321) #trunk SMP Mon Jun 20 17:39:41 UTC 2022
```

## 修改代码如下，固定系统为debian，修改比较暴力，您也可以下载官方脚本参照如下信息修改后安装。

```
#检查系统
check_sys() {
  release="debian"
  bit=$(uname -m)
}
```

## 安装方法

服务端：

```bash
wget https://raw.githubusercontent.com/YouVision/ServerStatus-Hotaru-OneCloud/master/status.sh
bash status.sh s
```

客户端：

```
bash status.sh c
```

## 其余信息去官方查看，建议脚本安装，手工安装有点费事

修改比较暴力，您也可以下载官方脚本修改后安装。
