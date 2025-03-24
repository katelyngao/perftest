1.测试环境（自行按要求购买）
在腾讯云官网购买cvm(https://cloud.tencent.com/product/cvm)，
购买南京地域的标准型SA5机型，规格为2核4GiB内存+100GiB增强型SSD云硬盘（注意：压测此数据盘，不要压测系统盘）
费用参考：按量计费 0.6/小时
![企业微信截图_da8e1b99-29fb-4b48-8cf1-94b68d98b4f8](https://github.com/user-attachments/assets/10e5a8b8-748e-4d17-b393-10d290dd17ea)
![image](https://github.com/user-attachments/assets/f74017b6-9e1c-4638-b9c0-69f3708cd07a)

    
2.测试目标：在上述云CVM上，使用fio测试工具对数据盘进行压测，尽可能压测出更高的IOPS值，调整范围不限于操作系统参数、fio参数等

3.参与者创建自己的分支，并提交测试过程内容到对应的目录： 
 （1）testlog：压测工具、监控等 （2）testscript：操作系统参数修改、可执行的fio测试脚本命令等 （3）testreport：最终测试结果、测试调整过程、AI交互过程等你认为能突出自己能力的内容

4.项目最终排行榜
<!-- RANKING_START -->
| 排名 | IOPS值 | 作者 | 分支链接 |
|------|----------|------|--------|
| 1 | 1000 | user1 | [main](https://github.com/katelyngao/perftest/tree/main) |
<!-- RANKING_END -->

