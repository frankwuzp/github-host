# github-host

## 快速访问

- Github 站点：`https://raw.githubusercontent.com/frankwuzp/github-host/main/hosts`
- Gitee 国内镜像：`https://gitee.com/frankwuzp/github-host/raw/main/hosts`

## 墙介绍

被 qiang 大体有两种：DNS污染，封杀IP。 

DNS污染则无法通过域名直接访问，一种方法就是修改DNS，这个最简单的就是修改hosts。 封杀IP的话，只能通过 “反墙” 来解决。由于政策风险，这里不介绍。 

## github访问

由于众所周知的原因 github 很多时候无法加载，或者样式不显示。我们可以简单修改 Host，解决 github 无法访问。编辑下面文件：
**C:\Windows\System32\drivers\etc\hosts**。把上述hosts文件内容复制进去即可。


## 更新

github 子域名非常多，服务器非常多，墙是动态的。所以需要不断更新 hosts 来解决无法访问问题。

## 迭代记录

**211014 14:24 [frankwuzp](https://github.com/frankwuzp) 增加三点功能**

1. 增加更多相关网址，具体如下：

```txt
    "github.dev",
    "central.github.com",
    "alive.github.com",
    "desktop.githubusercontent.com",
    "github.blog",
    "github.io",
    "github.map.fastly.net",
    "media.githubusercontent.com",
    "raw.githubusercontent.com"
```

2. `hosts` 文件增加显示北京时间。
3. 同步镜像文件到 [Gitee](https://gitee.com/frankwuzp/github-host) 仓库，输入以下网址可直达查看：
   
`https://gitee.com/frankwuzp/github-host/raw/main/hosts`

