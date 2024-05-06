# 深入理解文件系统原理和实践

## ISBN: 978-7-89381-214-9

## email: hiltontao96@163.com

## 目录


```
1.初始Linux文件系统     ………………………………… 001
  1.1 为什么学习文件系统 ……………………………… 001
  1.2 文件语义      …………………………………………… 003
  1.3 文件结构      …………………………………………… 008
  1.4 file 和 inode operation ………………… 015
  1.5 注册与卸载文件系统      ………………… 019
  1.6 接口错误码          …………………………… 021
  1.7 文件对齐和非对齐写 ……………………………… 024
  1.8 文件 truncate  ………………………………………… 027
  1.9 文件数据写入 write ……………………………… 035
  1.10 文件打开和关闭   ………………………………… 038
  1.11 文件属性信息    …………………………………… 041
2.深入理解zfs       …………………………………………… 045
  2.1 zfs 存储池设计  ……………………………………… 045
  2.2 zfs 层次结构   ………………………………………… 053
  2.3 zfs 指针结构和文件结构 …………………… 056
  2.4 zfs 属性 zap   ………………………………………… 062
  2.5 位图与 metaslab  …………………………………… 072
  2.6 zfs SpaceMap 和 MetaSlab ……………… 078
  2.7 zfs 校验码    …………………………………………… 088
  2.8 zfs 缓存概念理解  ………………………………… 089
  2.9 zfs 缓存实现   ………………………………………… 094
  2.10 zfs zil     ……………………………………………… 097
  2.11 zfs 事务组    ………………………………………… 101
  2.12 读请求流程代码走读  ………………………… 107
  2.13 zfs zio     ……………………………………………… 116
  2.14 zfs 磁盘移除   ……………………………………… 119
  2.15 zfs scrub    …………………………………………… 124
  2.16 zfs dedup    …………………………………………… 126
  2.17 zfs 快照     …………………………………………… 129
  2.18 zfs 动态 trim  ……………………………………… 131
3.文件存储从单机到分布式  …………………………… 136
  3.1 单机到分布式的架构变化……………………… 136
    3.1.1 元数据中心架构 ……………………………… 136
    3.1.2 无中心架构   …………………………………… 139
  3.2 分布式下的一致性  ………………………………… 141
    3.2.1 数据广播和流式传递 …………………… 141
    3.2.2 多数一致性   …………………………………… 145
    3.2.3 两副本可靠吗  ………………………………… 147
  3.3 数据和请求负载均衡 ……………………………… 150
    3.3.1 leader 分散  …………………………………… 150
    3.3.2 数据扩容和重平衡 ………………………… 152
  3.4 EC 卷       ………………………………………………… 156
    3.4.1 背景及原理   …………………………………… 156
    3.4.2 ec 和多副本差异……………………………… 158
  3.5 分布式异常数据修复 ……………………………… 160
  3.6 对象与文件存储差异 ……………………………… 166
4. 测试与优化        ………………………………………… 169
  4.1 文件系统测试    ……………………………………… 169
    4.1.1 单元测试    ……………………………………… 169
    4.1.2 模拟真实环境测试 ………………………… 171
    4.1.3 生态工具测试  ………………………………… 172
    4.1.4 性能测试    ……………………………………… 175
  4.2 小文件优化     ………………………………………… 177
  4.3 lustre 对 zfs 参数优化  ………………… 178
```
