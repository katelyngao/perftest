1.测试环境（自行按要求购买）
在腾讯云官网购买cvm(https://cloud.tencent.com/product/cvm)，
购买南京地域的标准型SA5机型，规格为2核4GiB内存+100GiB增强型SSD云硬盘（注意：压测此数据盘，不要压测系统盘）
费用参考：按量计费 0.6/小时
![企业微信截图_da8e1b99-29fb-4b48-8cf1-94b68d98b4f8](https://github.com/user-attachments/assets/10e5a8b8-748e-4d17-b393-10d290dd17ea)
![image](https://github.com/user-attachments/assets/f74017b6-9e1c-4638-b9c0-69f3708cd07a)

    

​2. 测试目标：在上述云CVM上，使用fio测试工具对数据盘进行压测，尽可能压测出更高的IOPS值，调整范围不限于操作系统参数、fio参数等

3. 提交材料：
3.1 可执行的fio测试脚本（含参数说明）
3.2 原始日志：压测工具、监控等
3.3 测试分析报告：最终测试结果、测试调整过程、AI交互过程等你认为能突出自己能力的内容


4. 将自己的测试结果按照如下的格式填写
<!-- RANKING_START -->
| 排名 | 运行时间 | 作者 | PR 链接 |
|------|----------|------|--------|
| 1 | 2.34s | user1 | [PR #123](https://github.com/xingfeng2510/workshop/pull/123) |
<!-- RANKING_END -->
