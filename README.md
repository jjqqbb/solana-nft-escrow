# paulx solana escrow contract & clients

Reference implementation for the guide https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/

The contract is in [program](program) and the tests are in [scripts/src](scripts/src)

# 笔记

## init - userA

- 存入资产A
- 设置价格

## exchange - userB

- 存入资产B
- 检查价格
- 资产B转给userA
- 资产A转给userB
- 关闭临时账户
