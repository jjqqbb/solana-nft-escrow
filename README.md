# paulx solana escrow contract & clients

Reference implementation for the guide https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/

The contract is in [program](program) and the tests are in [scripts/src](scripts/src)

# 笔记

## init - userA

- 存入资产A
  - 创建临时账户
  - 转资产A到临时账户
  - 修改临时账户资产ATA为Escrow账户
- 设置价格

## exchange - userB

- 检查价格
- userB资产B转给userA
- Escrow账户资产A转给userB
- 关闭临时账户
