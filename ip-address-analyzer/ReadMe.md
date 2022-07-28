# ip-address-analyzer功能
读取按行分割的ip地址，通过ip2region查询ip地址城市，获取所有出现的城市和出现次数，输出到指定文件中。


# ip-address-analyzer用法
- 把xdb文件复制到当前目录，并命名为ip2region.xdb
- 把按行分割的ip地址文件复制到当前目录
- 执行命令：python ip-address-analyzer ipAddr.txt out.txt
- 分析结果写入到out.txt中
> 需要python3



