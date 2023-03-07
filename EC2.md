---
mindmap-plugin: basic
---

# Ec2

## 基础概念
- 实例类型
   - 通用型 M5/M5a/ M5d/ M6g/M6i
   - 可突增型 t3/t4g
   - 计算优化型  C5/C5a/ C5d/ C6g/C6i
   - 内存优化型  R5/R5a/ R5d/ R6g/R6i
- OS 类型
   - Linux (ubuntu/amzn2/centOS)
   - Windows
   - Redhat/SUSE
- 购买选项（OD/RI/Spot)
- 联网
   - 公网IP/私网IP/ EIP
- 安全
   - 安全组
   - 秘钥对
- 存储
   - EBS
      - IO1/IO2
      - GP2/GP3
      - St1/SC1
      - 实例存储
- 监控
   - 实例状态监控
   - Cloudwatch 监控
      - CPU 利用率
      - 网路利用率(Network in/out)
      - 磁盘性能（Read/write IO）

## 进阶概念
- 实例进阶监控
   - 内存使用/SWAP/突增积分使用(T 系列)等
   - 系统日志收集/Kdump(linux)
- Fleet 队列(EC2 队列/ Spot 队列)
- 成本
   - 可转换RI/ 标准RI
   - 区域RI/ 可用区RI
   - 多因子匹配
- 故障排查
   - 无法启动 - 卷问题/ 容量问题
   - 无法连接 - 连接超时/ 用户错误/ 秘钥问题/ 安全组设定
   - 系统日志排查
   - EC2  Rescue - EC2 实例救援
- AWS Graviton 的使用与差异