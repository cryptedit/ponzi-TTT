Ponzi TTT
[![Build Status](https://travis-ci.org/cryptedit/ponzi-TTT.svg?branch=master)](https://travis-ci.org/cryptedit/ponzi-TTT)
===
- [x] 创建合约 Ponzi 时，可以指定多个 trainer 作为合约 Owner 以及必须完成的课程数（本次课程数为4）
- [x] trainee 可以注册到合约 Ponzi，保证金为`2 ether`
- [x] trainer 可以给 trainee 签到
- [x] trainee 可以查看自己的课程完成进度、余额
- [x] trainer 可以查看合约总余额
- [x] 任何人 都可以查看课程完成情况，特定trainee完成与否
- [x] 完成规定的课程数之后，trainer 可以将保证金 `2 ether` 退给对应的 trainee

## 部署

```
$ truffle deploy --network ropsten
此处用到的 account 地址可以从 1_initial_migration.js 中 module.exports 的第3个参数获得，我本机生成的地址是`0xc3d2a1629d3990d8b9d9799c8675ec18c6f00247`，余额可以通过查看 https://ropsten.etherscan.io/address/0xc3d2a1629d3990d8b9d9799c8675ec18c6f00247 
```
