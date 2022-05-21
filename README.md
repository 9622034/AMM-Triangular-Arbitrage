# Dex AMM Triangular ArbitrageArbitrage三角套利机器人

如果你不太懂程序，可以直接加入我们的Richman DAO，投入资金就可以直接享受套利机器人带来的利润

一部分资金会用于维护高昂的节点服务器，同时我们会把资金分散去各个DEX套利

目前DAO成员每日获利5%～17%

我们只收取2%的技术服务费

https://www.richmandao.com/





## 设置教程
编辑 .env-example.txt 文件，添加你的私钥

脚本在你本地运行，不用担心安全问题，只要你的电脑没中毒！

使用以下命令进行编译:

```shell
git clone https://github.com/jamesbachini/DEX-Arbitrage.git
cd DEX-Arbitrage
mv .env-example.txt .env
npm install
npx hardhat run --network aurora .\scripts\deploy.js
```



```shell
npx hardhat run --network aurora .\scripts\deploy.js
```

Finally to recover any funds use the script.

```shell
npx hardhat run --network aurora .\scripts\recover.js
```

只接受付费咨询，白嫖党不要耽误我时间，谢谢🙏
