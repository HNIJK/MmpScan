# 置顶

该工具目前还没那么快写完，然后本人参与并维护了另一款与此类似的工具，欢迎你们疯狂Star!

[花溪九尾](https://github.com/Cl0udG0d/HXnineTails/tree/test)

# 介绍

### 工具介绍

这是一款致力于将各类优秀脚本集合在一起调用、联动，最终可形成超级渗透脚本的工具。目的是扫描到更全的资产信息，发现更多的漏洞利用。但是这是通过牺牲扫描速度来提升扫描广度的。所以不太适合要进行紧急信息收集和漏洞利用的情况。

目前工具的功能还尚未完善，作者仅仅开发了一个基础框架的一半。后续更新请敬请期待！

### 目录介绍

- save

  保存资产扫描信息，和漏洞利用信息

-  main_script

  要集成、联动的脚本的调用脚本，其下分为两个子目录

  - crack_script

    存放着编写的漏洞利用脚本

  - property_script

    存放在编写的资产收集脚本

- tmp

  存放着修改过的联动脚本result文件。对其格式进行一定修改方便后面处理。

# 目前功能

1. 批量oneforall扫描域名，生成ip-domain名单



# 以后功能

1. 完善源码泄露扫描
2. 完善xray漏洞扫描
3. 完善C段扫描
4. 完善隐藏目录、敏感目录、后台扫描



# 使用方法

- `python MmpScan.py --target xxx`

  输入单个url

- `python MmpScan.py --file xxx`

  输入文件，读取多个主域名不同的url。