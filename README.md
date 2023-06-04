# 🔎 Building an MEV Searcher

In the last lesson, we understood what MEV is, what Flashbots are, and some use cases of Flashbots. In this level we will learn how to mint an NFT using Flashbots. This is going to be a very simple use case designed to teach you how to use Flashbots, not make a profit. Finding opportunities where you can make profit using MEV is a hard problem and are typically not public information. Every Searcher is trying to do their best, and if they tell you exactly what strategies they're using, they are shooting themselves in the foot.

```shell
NOTE: Similar to the arbitrage/flash loan level - you will almost never find an open-source MEV strategy that is actually profitable, because once it's out in the open, there is always someone willing to run it for cheaper driving down the profit margin to zero. MEV is a field which requires a lot of ingenuity to be profitable and keeping the strategy secret. You will find, however, a lot of open-source MEV bots that can help build your understanding on what kind of strategies make sense - even if that specific one is no longer profitable.
```

This tutorial is just meant to show you how you use Flashbots to send transactions in the first place, the rest is up to you!

# 👨‍💻 Output

```shell
gitpod /workspace/LW3-flashbots (main) $ npx hardhat run scripts/flashbots.js --network sepolia
Address of Fake NFT Contract: 0x217C5b9bcbd88fEb291b8240F9255fECFf17c480
Block Number:  3621404
Block Number:  3621405
Block Number:  3621406
Block Number:  3621407
Block Number:  3621408
Block Number:  3621409
Block Number:  3621410
Block Number:  3621411
Block Number:  3621412
Block Number:  3621413
Block Number:  3621414
Block Number:  3621415
Block Number:  3621416
Block Number:  3621417
Block Number:  3621418
Block Number:  3621419
Block Number:  3621420
Block Number:  3621421
Block Number:  3621422
Block Number:  3621423
Block Number:  3621424
Block Number:  3621425
Block Number:  3621426
Block Number:  3621427
Block Number:  3621428
Block Number:  3621429
Block Number:  3621430
Block Number:  3621431
Block Number:  3621432
Block Number:  3621433
Block Number:  3621434
Block Number:  3621435
Block Number:  3621436
Block Number:  3621437
```
## 💥minted https://sepolia.etherscan.io/address/0x217c5b9bcbd88feb291b8240f9255fecff17c480

## Boom 🤯 We now learned how to use flashbots to mint a NFT but you can do so much more 👀
## GG 🥳

# 📚 Readings

Flashbots Docs ➡ https://docs.flashbots.net/
Arbitrage bot using Flashbots ➡ https://github.com/flashbots/simple-arbitrage

# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

## <p align="center">[🤖 Warlocks!](http://warlocks.netlify.app)