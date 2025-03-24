##测试环境

腾讯云CVM：标准型SA5机型，规格为2核4GiB内存+100GiB增强型SSD云硬盘

##测试目标

在上述云CVM上，使用fio测试工具对数据盘进行压测（不能直接压测裸盘），针对ext4和xfs两种文件系统，分别尽可能的压测出最高的IOPS值，调整范围不限于操作系统参数、fio参数等

##测试要求

参与者fork该项目，并提交PR（pull request），包含以下内容：（1）PR 标题为实际测试IOPS （2）testlog：压测工具、监控等 （3）testscript：操作系统参数修改、可执行的fio测试脚本命令等 （4）testreport：最终测试结果、测试调整过程、AI交互过程等你认为能突出自己能力的内容

##参与者ext4文件系统最终IOPS排行榜（后台周期更新）
<!-- RANKING_START -->
| 排名 | IOPS值 | 作者 | PR链接 |
|------|----------|------|--------|
| 1 | 1000 | user1 | [PR #123](https://github.com/katelyngao/perftest/pulls) |
<!-- RANKING_END -->

##参与者xfs文件系统最终IOPS排行榜（后台周期更新）
<!-- RANKING_START -->
| 排名 | IOPS值 | 作者 | PR链接 |
|------|----------|------|--------|
| 1 | 1000 | user1 | [PR #123](https://github.com/katelyngao/perftest/pulls) |
<!-- RANKING_END -->
