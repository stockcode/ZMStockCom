﻿1、使用前找到Bin子目录的RegCom.bat文件，用记事本打开编辑，把ZMStockCom.exe实际路径填入后保存(路径如有空格，全路径必须用引号包起来);

2、然后右键以管理员权限运行RegCom.bat完成交易COM组件的注册；

3、反注册步骤先修改UnRegCom.bat里的ZMStockCom.exe程序实际路径，再以管理员权限运行即可；

4、本组件支持批量委托或批量查询行情，并提供了C++和C#调用使用范例(目录分别为CPlusPlus_Demo、CSharp_Demo)，演示程序编译了32位同步连接和64位异步连接调用执行程序(X64和X86目录)，CSharp_Demo演示程序需要.NET4.0才能运行；

5、本程序包为普通版，支持建立到交易服务器的单连接，不支持多账号多连接(属于高级版功能)，需要高级版的请加QQ群975658589 下载高级版程序包；

6、C#调用范例里演示的是连接TDX的模拟服务器，实际使用时请修改为您的券商信息进行测试，加QQ群(QQ群975658589，链接：https://jq.qq.com/?_wv=1027&k=5af0gkN )申请试用；

7、本中间件提供的是exe的执行程序组件，数据请求是通过RPC服务跨进程的，如果您对性能要求特别高，可以用DLL版的COM组件ZMTradeCom.dll，不过只能支持32位程序调用(注册和反注册文件分别是RegDllCom.bat和UnRegDllCom.bat，同样注意加入ZMTradeCom.dll的实际全路径，路径如有空格，全路径必须用引号包起来，另外需要注意的是，如果用ZMTradeCom.dll，必须把本组件的所有文件放到您的执行程序同目录使用，否则可能导致程序无法正常运行；

8、本中间件支持九十余家券商，但由于测试条件所限，如您的券商存在兼容性问题，联系客服解决；

9、交易中间件，自带行情查询功能，交易接口在交易时间可随时请求当前的5档行情报价，另外提供普通行情、扩展行情及Level2行情的接口；

10、本中间件详细说明及接口定义请参考文档“股票交易及行情COM组件开发手册.xls”；

11、Bin2目录为内核0接口支持升级了协议的程序版本，支持财富证券，红塔证券，浙商证券，九州证券，联储证券、华龙证券、山西证券、大同证券、银河证券、广发证券、兴业证券、国海证券、华西证券、万联证券、中泰证券、国融证券、光大证券、西部证券、海通证券、宏信证券、联讯证券、安信证券、东方证券、国信证券、招商证券、第一创业、华泰证券、川财证券、金元证券、东兴证券、中金证券、华金证券、南京证券、万和证券、太平洋证券、中山证券等，此版本不支持阿里云等虚拟机使用；

12、新发布的内核1接口，即使升级了协议的券商，已支持在阿里云等虚拟机上运行。
