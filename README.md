<div align="center">
  <img alt="starknet logo" src="./assets/starknet.png" width="200" >
  <h1 align="center">Awesome StarkNet 中文</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="#buildstatus">
      <img alt="build status badge" src="https://github.com/gakonst/awesome-starknet/workflows/Build/badge.svg">
    </a>
    <a href="https://github.com/gakonst/awesome-starknet/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/gakonst/awesome-starknet">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>

  <p align="center">This repository is forked from <a href="https://github.com/gakonst/awesome-starknet">Awesome StarkNet</a></p>
  <p align="center">本文档汇聚<a href="https://medium.com/starkware/starknet-alpha-is-coming-to-mainnet-b825829eaf32"> StarkNet </a>资源、工具、代码库、生态、应用等内容。由<a href="https://twitter.com/StarkNet_ZH">「StarkNet 中文」</a>编撰。</p>
  <p align="center">欢迎加入我们或按照<a href="CONTRIBUTING.md">《贡献者指南》</a>为本库 PR 贡献。</p>
  
  <p align="center">找到我们：<a href="https://twitter.com/StarkNet_ZH"> Twitter </a> | <a href="https://mirror.xyz/starknet-zh.eth"> Mirror Blog</a> | <a href="https://starknetzh.substack.com"> Substack 日报/周报</a> | <a href="https://starknet-zh.notion.site/StarkNet-ca5af6495c3642e6b48424202fbec3d1"> 资源面板</a>  |  <a href="https://discord.gg/R8A879b8x3"> Discord</a></p>

</div>


## 🏰 官方资源

- [官网](https://starkware.co/)
- [StarkNet 概况](https://starknet.io/)
- [StarkNet 文档](https://docs.starknet.io)
- [StarkNet 开发指南](https://starknet.io/building-on-starknet/)
- [Starknet Stack Resources](https://github.com/starknet-io/starknet-stack-resources) - Cairo 和审计资源
- [Setting up the environment](https://www.cairo-lang.org/docs/quickstart.html) - 运行 Cairo 开发环境
- [Hello Cairo](https://www.cairo-lang.org/docs/hello_cairo/index.html) - Cairo 合约开发指南
- [Cairo Reference](https://www.cairo-lang.org/docs/reference/index.html) - Cairo 语义详解
- [Cairo – a Turing-complete STARK-friendly CPU architecture](https://eprint.iacr.org/2021/1063.pdf) - Cairo 白皮书
- [Cairo 程序执行的验证代数表达式](https://arxiv.org/abs/2109.14534) - 使用 [精益证明助理 (Lean proof assistant)](<https://en.wikipedia.org/wiki/Lean_(proof_assistant)>) 的 Cairo 证明有效性
- [StarkNet Playground](https://www.starknet.io/playground) - 浏览器 StarkNet 示例
- [Cairo Playground](https://www.cairo-lang.org/playground/) - 浏览器 Cairo IDE、范例和谜题
- [StarkNet Voting Workshop](https://starkware.notion.site/starkware/StarkNet-Voting-Workshop-b61ef5f4a62d45af86892cba3158f7e6) - 投票 dApp 开发指南
- [YouTube channel](https://www.youtube.com/channel/UCnDWguR8mE2oDBsjhQkgbvg/playlists) - StarkWare 官方 YouTube 频道
- [STARK 验证合约审计报告](https://github.com/starkware-libs/starkex-contracts/blob/master/audit/EVM_STARK_Verifier_v4.0_Audit_Report.pdf)



##  ⚡️ 生态工具

- OpenZeppelin 合约标准：
  - [入门指南](https://blog.openzeppelin.com/getting-started-with-openzeppelin-contracts-for-cairo)
  - [OpenZeppelin Cairo 1.0 合约标准库](https://github.com/OpenZeppelin/cairo-contracts/tree/cairo-1/src/openzeppelin/token)
  - [Cairo 合约文档](https://docs.openzeppelin.com/contracts-cairo)
  - [Cairo 扩展功能](https://github.com/OpenZeppelin/cairo-contracts/blob/main/docs/Extensibility.md)
  - [帐户抽象](https://github.com/OpenZeppelin/cairo-contracts/discussions/41)
  - [Nile](https://github.com/OpenZeppelin/nile) - CLI 开发工具
- [Cairo 合约向导](https://wizard.openzeppelin.com/cairo) - 交互式合约生成器
- [Starknet JSON-RPC API](https://docs.alchemy.com/reference/starknet-api-quickstart) - Alchemy API
- [Warp](https://github.com/NethermindEth/warp) - Solidity <-> Cairo 转译器
- [Vyro](https://github.com/tserg/vyro) - Vyper <-> Cairo 转译器
- [Skyro](https://github.com/skyro-compiler/skyro) -  [Idris2](https://github.com/idris-lang/Idris2) <-> Cairo 转译器
- [Starkscan](https://starkscan.co/) - 区块链浏览器
- [Voyager](https://voyager.online) - 区块链浏览器
- [Protostar](https://github.com/software-mansion/protostar) | [网站](https://docs.swmansion.com/protostar) - [Software Mansion](https://twitter.com/swmansion) 开发的 Cairo 智能合约开发、测试管理工具
- [Prototype](https://github.com/sambarnes/prototype) - 基于 Protostar 的项目开发模板
- [starknet.py](https://github.com/software-mansion/starknet.py) - Python SDK 代码库
- [starknet.js](https://github.com/0xs34n/starknet.js) | [文档](https://www.starknetjs.com/guides/what_s_starknet.js) - StarkNet JavaScript 代码库
- [Starknet JVM](https://github.com/software-mansion/starknet-jvm) - JVM 语言的 StarkNet SDK
- [Cairo Foundry](https://github.com/onlydustxyz/cairo-foundry) - 类 Foundry 的 StarkNet 合约框架
- [Horus Checker](https://github.com/NethermindEth/horus-checker) - [Nethermind](https://nethermind.io/horus) 开发的 StarkNet 智能合约形式化验证工具
- [Amarna](https://github.com/crytic/amarna) - Trail of Bits 推出的[静态安全分析工具](https://blog.trailofbits.com/2022/04/20/amarna-static-analysis-for-cairo-programs)，用于识别错误代码和安全隐患
- [Medjai](https://github.com/Veridise/Medjai) - Cairo 符号执行工具。用以检测 Bug | [使用说明](https://medium.com/veridise/medjai-protecting-cairo-code-from-bugs-d82ec852cd45)
- [Cairo Fuzzer](https://github.com/FuzzingLabs/cairo-fuzzer) - 合约安全检查工具
- [Starkscan Verifier](https://github.com/starkscan/starkscan-verifier) - 验证 Cairo 合约
- [Papyrus](https://github.com/starkware-libs/papyrus) - StarkWare 开发的 Rust 全节点
- [Juno](https://github.com/NethermindEth/juno) - Nethermind 开发的 GoLang 全节点客户端
- [Pathfinder](https://github.com/eqlabs/pathfinder) - Equilibrium 开发的 Rust 全节点
- [Kaioshin](https://github.com/keep-starknet-strange/kaioshin) - 基于 Substrate 用 Rust 写的排序器
- [Blockifier](https://github.com/starkware-libs/blockifier) - Rust 排序器执行交易组件
- [Pytest](https://github.com/TimNooren/pytest-cairo) - Python 测试 Cairo 和 StarkNet
- [Cairo1 Template](https://github.com/msaug/cairo1-template) - Cairo 1.0 开发模板
- [cairo-glyph](https://github.com/sambarnes/cairo-glyph) - Cairo 管理器
- [Starknet Devnet](https://github.com/Shard-Labs/starknet-devnet) - Starknet 本地测试网
- [starknet-hardhat-plugin](https://github.com/Shard-Labs/starknet-hardhat-plugin) - Hardhat 开发工具包
- [Cairo Jupyter](https://github.com/ankitchiplunkar/cairo-jupyter) - Cairo 合约语言 Jupyter 内核
- [pre-commit-cairo](https://github.com/franalgaba/pre-commit-cairo) - Cairo git 代码管理工具
- [Generator](https://github.com/onlydustxyz/generator-starknet) - 用 [@yeoman](https://twitter.com/yeoman) 的智能合约生成器
- [StarkNet React](https://github.com/apibara/starknet-react) - StarkNet React hooks
- [VS Code Cairo 插件](https://marketplace.visualstudio.com/items?itemName=ericglau.cairo-ls)
- [VS Code Cairo 语义插件](https://marketplace.visualstudio.com/items?itemName=starkware.cairo)
- [Starkops](https://github.com/0xs34n/starkops) - TypeScript 语言 StarkNet 工具链命令行
- [starknet-web3-rpc-adapter](https://github.com/software-mansion-labs/starknet-web3-rpc-adapter) - 向 StarkNet 传输信息的转接器应用
- [Starktx](http://starktx.info) - 交易解码工具 | [源代码和文档](https://github.com/TokenFlowInsights/StarkTx)
- [Giza](https://github.com/maxgillett/giza) - Cairo VM 证明和验证代码库
- [Felucca](https://github.com/franalgaba/felucca) - 代码依赖性管理工具 Felucca
- [Cairo rs](https://github.com/lambdaclass/cairo-rs) - Cairo Rust VM
- [starknet-rs](https://github.com/xJonathanLEI/starknet-rs) - StarkNet Rust 代码库
- [starkli](https://github.com/xJonathanLEI/starkli) - StarkNet Rust 的 CLI 工具
- [StarkNet 数据仓库 (“SDW”)](https://tokenflow.live/blog/edw-open)
- [ZigZag StarkNet 预言机](https://github.com/ZigZagExchange/starknet-oracle)
- [React + Redux 库](https://github.com/ruleslabs/starknet-redux-multicall) - 通过批量缓存调用，撷取每个区块的状态
- [Cairo CLI Docker](https://github.com/Shard-Labs/cairo-cli-docker) - 制作 Cairo 工具映像
- [DEX 聚合交易解码器](https://github.com/zoeAD/basic-solver)
- [Get StarkNet](https://github.com/starknet-community-libs/get-starknet) - dApp 部署钱包代码库
- [Cairo Streams](https://github.com/onlydustxyz/cairo-streams) - 数组流代码库
- [Caigo](https://github.com/dontpanicdao/caigo) - Golang 代码库
- [Apibara](https://github.com/apibara/apibara) - dApp 开发工具和 API
- [Starknet Swift](https://github.com/software-mansion/starknet.swift) - Swift 的 Starknet SDK
- [Tayt](https://github.com/crytic/tayt) - 智能合约模糊测试工具
- [Ape](https://github.com/ApeWorX/ape) - [ApeWorX](https://twitter.com/ApeFramework) 开发的智能合约开发工具
- [vscode-cairo-extension](https://github.com/qd-qd/vscode-cairo-extension) - Cairo vscode 开发插件
- [Interface Generator](https://github.com/msaug/starknet-interface-generator) - Cairo 合约接口生成工具
- [Sahara](https://github.com/boray/sahara) - [合约类与合约库查询工具](sahara-jet.vercel.app)
- [Kaaper](https://github.com/onlydustxyz/kaaper) - Cairo 项目文档生成器
- [Cairo Sha256](https://github.com/cartridge-gg/cairo-sha256) - SHA256 生成器
- [Nile Coverage](https://github.com/ericnordelo/nile-coverage) - Cairo 合约覆盖率报告插件
- [STARK Utils](www.stark-utils.xyz) | [代码库](https://github.com/gaetbout/stark-utils) - 开发者转换、哈希计算、签名工具
- [miniSTARK](https://github.com/andrewmilson/ministark) - GPU 加速 STARK 证明器
- [Beerus](https://github.com/keep-starknet-strange/beerus) - 使用 [Helios](https://github.com/a16z/helios/) 搭建的 StarkNet 轻型客户端，便于从用户端检索网络状态、与合约交互
- [Garaga](https://github.com/keep-starknet-strange/garaga) - 在 StarkNet 密码学应用
- [Remix plug-in](https://github.com/groksmith/starkware-remix-plugin) - Remix Cairo 开发插件
- [Remix game day](https://github.com/starknet-edu/remix-game-day) - Remix 开发 StarkNet 合约简易指南
- [Quaireaux](https://github.com/keep-starknet-strange/quaireaux) - Cairo 1.0 相关代码库和算法
- [Shenlong](https://github.com/keep-starknet-strange/shenlong) - Cairo 的 LLVM IR 编译工具
- [Get Starknet](https://github.com/starknet-io/get-starknet) - 部署 dApp 和钱包工具
- [Sierra Docs](https://sierra-docs.github.io/#/)



## 🗂 官方 GitHub 库

- [StarkWare](https://github.com/starkware-libs) - 官方代码库
- [Cairo Language](https://github.com/starkware-libs/cairo-lang) - StarkNet 语言
- [starkex-contracts](https://github.com/starkware-libs/starkex-contracts) StarkEx 合约
- [veedo](https://github.com/starkware-libs/veedo) - Verifiable Delay Function
- [starkex-resources](https://github.com/starkware-libs/starkex-resources) - StarkEx 资源
- [starkgate-frontend](https://github.com/starkware-libs/starkgate-frontend) - StarkGate 前端
- [stark-perpetual](https://github.com/starkware-libs/stark-perpetual) - 永续合约
- [starkex-for-spot-trading](https://github.com/starkware-libs/starkex-for-spot-trading) - 现货交易
- [starkex-js](https://github.com/starkware-libs/starkex-js)
- [starknet-specs](https://github.com/starkware-libs/starknet-specs) - 标准
- [starknet-addresses](https://github.com/starkware-libs/starknet-addresses) - 合约和代币地址
- [starknet-docs](https://github.com/starkware-libs/starknet-docs)
- [starknet-snap](https://github.com/starkware-libs/starknet-snap)
- [cairo-playground](https://github.com/starkware-libs/cairo-playground)
- [starkware-crypto-utils](https://github.com/starkware-libs/starkware-crypto-utils)



## 💡 学习资源

- [StarkNet 可视化学习](https://starknet-tutorials.vercel.app/)
- [starknet-edu](https://github.com/starknet-edu/) - Cairo 合约学习指南
  - [Cairo 101](https://github.com/starknet-edu/starknet-cairo-101) - 如何阅读 Cairo 代码 | [中文](https://github.com/starknet-edu/starknet-cairo-101/tree/mandarin)
  - [ERC20](https://github.com/starknet-edu/starknet-erc20) - 如何在 StarkNet 部署 ERC20
  - [ERC721](https://github.com/starknet-edu/starknet-erc721) - 如何在 StarkNet 部署 ERC721
  - [通讯桥](https://github.com/starknet-edu/starknet-messaging-bridge) - 部署 StarkNet <-> Ethereum 跨链应用
- [Starknet Book](https://book.starknet.io/chapter_1/environment_setup.html)
- [Cairo Book](https://cairo-book.github.io/)
- [Sierra Doc](https://sierra-docs.github.io/#/)
- [Symbonstark](https://symbonstark.surge.sh) - Cairo 学习 | [GitHub](https://github.com/JejomStark/SymbOnStark)
- [Perama 博客](https://perama-v.github.io/cairo/intro/) - StarkNet / Cairo 学习笔记
- [Perama 的 Cairo 使用示例](https://perama-v.github.io/cairo/by-example)
- [@RoboTeddy StarkNet 开发实操心得](https://hackmd.io/@RoboTeddy/BJZFu56wF)
- [StarkWare 开发笔记](https://seen-joke-82c.notion.site/StarkWare-Development-965f54711eb84dc79f3b61f22df9e383)
- [Cairo by Example](https://cairo-by-example.org/) - Cairo 学习范例
- [Cairo 和 StarkNet 学习笔记](https://david-barreto.com/) | 作者：[David Barreto](https://twitter.com/barretodavid)
- [From Solidity to Cairo 1.0](https://lead-archeology-a38.notion.site/From-Solidity-to-Cairo-1-0-WIP-07097d7de1ad45d9b7c6c63f60b7141c) - Solidity 与 Cairo 1.0 比较
- [Cairo 和 StarkNet 安全](https://ctrlc03.github.io/#signature-replay-attacks) | 作者：[ctrlc03.eth](https://twitter.com/ctrl_c3)
- [Cairo 格式和风格指南](https://hackmd.io/@0xHyoga/BkKhLIMJi)
- [StarkNet Developer Guide](https://www.devpill.me/docs/starknet-development/introduction/) | 作者：[devpill.me](https://www.devpill.me/)
- [BrainSTARK](https://aszepieniec.github.io/stark-brainfuck/) - Brainfuck 语言实现 STARK 证明系统
- [Min StarkNet](https://github.com/Darlington02/min-starknet) - 部署简化版 StarkNet 协议和标准
- 利用 Starknet 帐户抽象实现[单钱包多人交易竞赛](https://medium.com/@patrick_99337/a-fun-introduction-to-cairo-1-0-d28a9793babb)



## 🛠 生态开发部署

- [Chainlink Starknet 部署文档](https://docs.chain.link/data-feeds/starknet) | [Cairo Starter Kit](https://github.com/smartcontractkit/cairo-starter-kit)
- [StarkNet Debug](https://github.com/starknet-edu/starknet-debug) - 合约 debug 教程 
- [Hardhat 项目基本范例](https://github.com/Shard-Labs/starknet-hardhat-example) - StarkNet 运行开发环境 Hardhat 范例
- [用 Cairo 运行物理数学 Gamma 函数](https://github.com/abstractnull/specialfunctions_cairo)
- [用 Solidity 部署 StarkNet pedersen hash](https://github.com/zknoname/pedersen-hash-solidity)
- Cairo 部署 [ERC721R 标准](https://github.com/ctrlc03/ERC721R-Cairo) (https://erc721r.org)
- 用 Cairo [部署 ERC-721 合约](https://github.com/scaffold-eth/scaffold-eth/tree/starknet-nft)
- 通过 OpenZepplin Cairo 合约标准[部署机枪池代币 ERC-4626](https://github.com/OpenZeppelin/cairo-contracts/issues/277) | [代码](https://github.com/koloz193/ERC4626)
- [Omni Account](https://github.com/happenwah/omni-account) - StarkNet 通用帐户
- [StarkNet 钱包 API](https://github.com/myBraavos/get-starknet-wallet)
- [starknet-libs](https://github.com/sekai-studio/starknet-libs) - Cairo 使用代码库示例
- [Soul Moment](https://github.com/ChecksFinance/soul-moment) - Cairo 语言的 Soulbound Token  (SBT)
- [Cairo Dutch](https://github.com/sambarnes/cairo-dutch) - NFT 荷兰拍机制
- [RICKS](https://github.com/FawadHa1der/ricks-cairo-contracts) - NFT 碎片化协议
- Cairo 部署 [NFT 限价拍卖机制 CRISP](https://github.com/08351ty/CRISP-cairo)
- [starknet-boilerplate](https://github.com/threepwave/starknet-boilerplate) - 使用 starknetjs 和 nile 部署 starknet/cairo 项目
- [starknet-multisig](https://github.com/eqlabs/starknet-multisig) - 多签部署 | [使用](http://starknet-multisig.vercel.app)
- [cairo-multisig](https://github.com/sambarnes/cairo-multisig) - 多签部署
- [安装 Hardhat 写 Cairo 测试](https://github.com/gaetbout/starknet-stack)
- [Cairo Base-64](https://github.com/dhruvkelawala/cairo-base64) - Base64 编码的多字符 ASCII Felt 库
- [Flashloan](https://github.com/tohrnii/flashloan-starknet)
- [Oriac](https://github.com/xJonathanLEI/oriac) - Rust 部署 Cairo VM
- [链上存取控制合约](https://github.com/419Labs/access-controller-contracts) - 卡槽模式，用以链上注册 | by [@alpharoad_fi](https://twitter.com/alpharoad_fi)
- [Cairo ML](https://github.com/raphaelDkhn/cairo_ml) - Cairo 1.0 神经网络模型
- [Neural Network Cairo](https://github.com/franalgaba/neural-network-cairo) - Cairo 1.0 神经网络
- [tiny-dnn-on-starknet](https://github.com/guiltygyoza/tiny-dnn-on-starknet) - 神经网络
- [Basic Solver](https://github.com/zoeAD/basic-solver) - DEX 聚合交易解码器
- [用 Wintefell 部署 Cairo VM](https://github.com/maxgillett/giza)
- [BLS 椭圆曲线](https://github.com/0xNonCents/multi-precision_cairo) | [BLS12-381](https://github.com/0xNonCents/cairo-bls12-381)
- [Nistp256](https://github.com/spartucus/nistp256-cairo) - 用 Cairo 部署 NIST P-256
- [cairo-aes](https://github.com/onurinanc/cairo-aes) - Cairo 部署 AES-128
- [alt_bn128](https://github.com/tekkac/cairo-alt_bn128) - 验证 SNARKS 运算的椭圆曲线
- [common-ec-cairo](https://github.com/EulerSmile/common-ec-cairo) - 普通椭圆曲线，可使用不同参数
- [cairo-alt_bn128](https://github.com/tekkac/cairo-alt_bn128) - Cairo 部署 alt_bn128，可用来验证 SNARK 运算
- [starknet-btc-lightclient](https://github.com/samlaf/starknet-btc-lightclient) - 比特币轻节点客户端
- 用 Cairo 部署[现金流应用 SuperFluid](https://github.com/ayushm2003/basic-superfluid)
- [StarKonquest](https://github.com/onlydustxyz/starkonquest) - Cairo 学习入门游戏
- [用 Cairo 进行数组运算](https://github.com/omarespejel/cairo-lang/blob/add-array-operations/src/starkware/cairo/common/array_operations.cairo)
- [Messaging Vyper](https://github.com/exp-table/starknet-messaging-vyper) - L1 <-> L2 通讯 Vyper 示例
- [felt-packing](https://github.com/gaetbout/starknet-felt-packing) - felt 字段元素封装
- [starknet-utils](https://github.com/strangerstork/starknet-utils) - felt 封装
- [Bulletproof](https://github.com/Lev-Stambler/bulletproof-cairo) - StarkNet 部署 Bulletproofs 隐私方案
- [StarkVest](https://github.com/abdelhamidbakhta/starkvest) - ERC20 代币分发 (vesting) 合约库
- [StarkNet USD](https://github.com/orkunkilic/starknet-usd) - 利用 L1 <> L2 通讯桥部署的 L2 稳定币协议
- [Thoth](https://github.com/FuzzingLabs/thoth) - 字节码反汇编程序，可生成调用流程图与控制流程图
- [Cairo Wadray](https://github.com/lindy-labs/cairo-wadray) - 利用 felt 的固定小数点算数公式
- [Cairo Math 64x61](https://github.com/influenceth/cairo-math-64x61) - Cairo 64x61 固定点数
- [Starknet Staking](https://github.com/pedrobergamini/starknet-staking) - 利用 L1 <> L2 通讯实现质押奖励
- [Linear Regression](https://github.com/trangnv/linear-regression-starknet) - 采用 commit-reveal 机制的机器学习模型
- [cairo-accesscontrol](https://github.com/lindy-labs/cairo-accesscontrol) - 会员访问控制合约
- [Khepri StarkNet](https://github.com/bitcoin-stark/khepri-starknet) - 利用 STARK zkp 的比特币轻节点
- [ZeroSync](https://github.com/ZeroSync/ZeroSync) - STARK 证明的比特币全节点
- [STARK-SNARK Recursive Proofs](https://github.com/VictorColomb/stark-snark-recursive-proofs) - Circom 编译器 Winterfell 生成 STARK 证明
- [STARKNET-PHASER-GAME](https://github.com/ExyUzi/STARKNET-PHASER-GAME) - 赛车游戏
- [json-on-starknet](https://github.com/raphaelDkhn/json-on-starknet) - Cairo 合约实现 JSON 数据结构，例如应用于 MIDI 文件
- [Cairo ECS](https://github.com/BibliothecaForAdventurers/cairo-ecs) - Cairo 实现 MUD ECS 引擎 | [介绍](https://mirror.xyz/matchboxdao.eth/d3lVAOa9Bi0kY-caoUT3lDC6E61mWJqtP1q6tME4xGY)
- [Sandstorm](https://github.com/andrewmilson/sandstorm) - 采用 [miniSTARK](https://github.com/andrewmilson/ministark/) 的 Cairo 证明器



## 🧲 教学内容

- STARK 有效性证明 - [视频](https://youtu.be/E4YO11rHMhw) | [Slide](https://slideshare.net/TinaBregovi/starknet-intro)
- [桥接通讯](https://github.com/starknet-edu/starknet-messaging-bridge) - [文档](https://starknet.io/docs/hello_starknet/l1l2.html) | [视频](https://www.youtube.com/watch?v=C-6SBaDi5_c) | [Slide](https://slideshare.net/TinaBregovi/starknet-l1l2-messaging-workshop)
- [StarkNet ERC-20/721](https://github.com/starknet-edu) - [视频](https://youtu.be/PJWIgIoj5kw) | [Slide](https://slideshare.net/TinaBregovi/starknet-erc20-erc721)
- [钱包、帐户抽象和语义](https://community.starknet.io/t/starknet-account-abstraction-model-part-2/839) - [视频](https://youtu.be/Vgd41wf7-bE) | [Slide](https://slideshare.net/TinaBregovi/starkware-account-abstraction)
- StarkNet JS - [视频](https://youtu.be/gqj0ENOE0EE) | [Slide](https://slideshare.net/Neven6/starknet-js)


## 💬 社区讨论

- [费用机制](https://community.starknet.io/t/fees-in-starknet-alpha/286) | [文档](https://starknet.io/documentation/fee-mechanism/#How) | [博客](https://www.ethereum.cn/Layer2/fees-in-starknet-alpha)
- [去中心化](https://community.starknet.io/t/starknet-decentralization-kicking-off-the-discussion/711) | [Tentermint 方案](https://community.starknet.io/t/starknet-decentralization-tendermint-based-suggestion/998) | [最长链原则](https://community.starknet.io/t/decentralized-consensus-potential-candidate-longest-chain/824) | [视频](https://www.youtube.com/watch?v=rQd6xXIQ43g)
- [特殊情况逃逸出口研究](https://community.starknet.io/t/starknet-escape-hatch-research/1108)
- [Cairo 合约扩展模式](https://github.com/OpenZeppelin/cairo-contracts/blob/main/docs/Extensibility.md) | [社区讨论](https://community.starknet.io/t/contract-extensibility-pattern/210?u=martriay) | [Twitter](https://twitter.com/StarkNet_ZH/status/1521704816916922368)
- [AAVE <> StarkNet 讨论](https://governance.aave.com/t/request-for-approval-aave-starkware-phase-i/7145)
- [MakerDAO x StarkNet 方案讨论](https://forum.makerdao.com/t/mip39c2-sp19-adding-the-starknet-engineering-core-unit-sne-001/9745)


## 🔆 开发工具和指南

- [Starklings](https://github.com/onlydustxyz/starklings) - StarkNet 交互式开发指南
- [Starklings Cairo1](https://github.com/shramee/starklings-cairo1) - Cairo 1.0 版本 Starklings 交互指南
- [Rust Book ZH](https://github.com/0xAsten/rust-book-zh) - Rust 编程语言中文翻译
- [Protostar 编写 StarkNet 智能合约的全开发周期教程](https://blog.swmansion.com/testing-starknet-contracts-made-easy-with-protostar-2ecdad3c9133) by [Software Mansion](https://twitter.com/swmansion)
- [StarkNet 开发指南](https://github.com/onlydustxyz/development-guidelines/blob/main/starknet/README.md)
- [GoL2 合约开发指南（一）：合约和 Indexer](https://medium.com/@yuki_labs/gol2-behind-the-scenes-contract-indexer-database-32f92fee2404)
- [Cygnus 合约格式指南](https://hackmd.io/@0xHyoga/BkKhLIMJi)
- [Cairo 惯例](https://github.com/milancermak/cairopractice/blob/master/2022-08-25-cairo-conventions/CairoConventions.md)
- [如何部署 Cairo 开发环境](https://th0rgal.medium.com/the-easiest-way-to-setup-a-cairo-dev-environment-8f2a63610d46)
- [开发部署指南](https://medium.com/@0xexomonk/starknet-and-cairo-developer-ultimate-intro-guide-b97f2d08a1e5)
- StarkNet [终极开发环境](https://medium.com/starknet-edu/the-ultimate-starknet-dev-environment-716724aef4a7)
- 使用 Cairo 开发，[实现 Github 语法高亮](https://twitter.com/StarkNet_ZH/status/1511925350443278342)
- [设置合约在特定时段切换不同模式](https://github.com/0xtonysprocket/zz_simple_liquidity_pool/blob/main/contracts/Time_window_base.cairo)
- [使用隐式参数构建物件导向程序设计模式](https://mirror.xyz/onlydust.eth/rR2Gt31kGQLlXZ27mLb_4Jtwh-cu8r6v51YSh-ECMw8)
- [Cairo 生成证明命令行工具](https://github.com/maxgillett/giza/pull/1)
- [开发框架比较：protostar VS nile](https://github.com/onlydustxyz/protostar-vs-nile)
- [Cairo 开发框架比较](https://github.com/immutable/imx-starknet/issues/7)
- 开发工具 [Protostar 与 Nile 比较](https://mirror.xyz/onlydust.eth/1yoQch6XFpOjd9VVzZ48bZbpwtmLO2fOqYg7QxzW3DA)
- [全节点安装指南](https://twitter.com/StarkNet_ZH/status/1522111642498048000)
- [Infura 或 Alchemy 安装节点](https://mirror.xyz/onlydust.eth/5-AwlDVo6ROXLRQzWDnMLCVVuVEU98koOMXn_wqV_Hk)
- [Security Challenges Factory for Starknet](https://starknet-challenges.vercel.app/)


## 🧬 生态

- [StarkNet 生态](https://starknet-ecosystem.com) - [社区发起](https://github.com/419Labs/starknet-ecosystem.com) StarkNet 生态项目和团队汇总
- [跨链桥 StarkGate](https://goerli.starkgate.starknet.io) | [前端 repo](https://github.com/starkware-libs/starkgate-frontend) | [合约](https://github.com/starkware-libs/starkgate-contracts/tree/main/src/starkware/starknet/apps/starkgate) |  [合约地址](https://github.com/starkware-libs/starknet-addresses)
- [Kakarot](https://github.com/sayajin-labs/kakarot) - 利用 STARK 证明用 Cairo 实现的三型 ZK-EVM
- [Arch](https://immutablex.medium.com/immutable-is-pleased-to-introduce-arch-v1-0-c45531dc3a2) - Immutable X 开发的 NFT 跨链桥
- [Starknet Indexer](https://github.com/olegabu/starknet-archive-docs#starknet-indexer) - [官网](starknetindex.com)
- [Checkpoint](https://checkpoint.fyi/) - Snapshot 提供的 StarkNet 数据检索库 | [发布](https://twitter.com/StarkNet_ZH/status/1536980057893535744) | [文档](https://docs.checkpoint.fyi/)
- [Empiric](https://empiric.network/) - Oracle | [GitHub](https://github.com/42labs/Empiric)
- [Fossil](https://docs.oiler.network/oiler-network/products/fossil/getting-started) - Starknet L2 Verifier 验证合约和链上预言机 by [@OilerNetwork](https://twitter.com/OilerNetwork) | [API](https://fossil.oiler.network/docs) | [官宣](https://medium.com/oiler-network/introducing-fossil-ce4c23ad17c4)
- [Chronos-Oracle](https://github.com/CarmineOptions/Chronos-Oracle) - 期权协议 [Carmine](https://carmine.finance/) 预言机
- [zkPad](https://zkpad.io) - 众筹和 launchpad 平台 | [GitHub](https://github.com/ZkPad-Labs/zkpad-contracts)
- [CodeforDAO](https://github.com/CodeforDAO/cairo-contracts) - 开发者协作 DAO
- [RockyBot](https://github.com/Modulus-Labs/RockyBot) - 链上机器学习人工智能交易机器人
- [Switch](https://github.com/Starknet-Recovery-Service) - 钱包恢复服务（[StarkNet House](https://twitter.com/StarknetHouse) 黑客松第一名）
- [Tic tac](https://github.com/aymericdelab/cairo-matchbox-hackathon) - 链上 AI 代理（[MatchboxDAO](https://twitter.com/matchbox_dao) 黑客松第一名）
- [GoL2-Contract](https://github.com/yuki-wtf/GoL2-Contract) - [GOL2](https://www.gol2.io/) 全链游戏
- [Carbonable Contracts](https://github.com/Carbonable/carbonable-contracts) - 碳中和项目 [Carbonable](https://carbonable.io/) 半同质化代币合约
- [StarkNet Plugin Account](https://github.com/argentlabs/starknet-plugin-account) - StarkNet 帐户合约插件标准
- [Dojo](https://github.com/dojoengine/dojo) - Cairo 全链游戏开发工具


## 📱 应用

- [Argent-x](https://github.com/argentlabs/argent-x) - 网页插件钱包
- [Braavos](https://braavos.app) - 智能合约插件钱包
- [Demux](https://github.com/smchala/demultiplexer-wallet) - 流支付智能合约钱包
- [Opera 插件和手机钱包](https://www.opera.com/crypto/next) - 目前 Deversifi 可使用
- [Invisibl3](https://twitter.com/StarkNet_ZH/status/1544163777624817666) - [ZigZag](https://twitter.com/ZigZagExchange) 开发的隐私插件


## ⚗️ 研究

- 快速提款
  - [StarkExchange: Fast Withdrawals using Cookie Jars](https://medium.com/starkware/starkexchange-fast-withdrawals-using-cookie-jars-88eefea6a11a)
  - [Conditional Transfers — The Key to Interoperability](https://medium.com/starkware/conditional-transfers-the-key-to-interoperability-2e1de044fb65)
- [dAMM](https://medium.com/starkware/damm-decentralized-amm-59b329fb4cc3) | [L2 Powered AMM](https://medium.com/starkware/caspian-an-l2-powered-amm-f20e93b5421)
- [DeFi pooling](https://medium.com/starkware/defi-pooling-1332ddebff21) | [文档](https://docs.starkware.co/starkex-v4/starkex-deep-dive/defi-pooling)
- [数据可用](https://medium.com/starkware/volition-and-the-emerging-data-availability-spectrum-87e8bfa09bb)
- [分形扩展：L2 <-> L3](https://medium.com/starkware/fractal-scaling-from-l2-to-l3-7fe238ecfb4f)
- [STARKs: Verifying complex auto battler calculation on Ethereum — Scaling decentralized games](https://killari.medium.com/starks-verifying-a-complex-auto-battler-calculation-on-ethereum-d8698f29808d)
- [What is the anatomy of a STARK proof?](https://hackmd.io/@liamzebedee/H1ejQCoHj)
- [ZK-STARKs — Create Verifiable Trust, even against Quantum Computers](https://medium.com/coinmonks/zk-starks-create-verifiable-trust-even-against-quantum-computers-dd9c6a2bb13d)


## 🔑 文章合集

- 《[密碼學證明的寒武紀大爆發](https://medium.com/taipei-ethereum-meetup/%E5%AF%86%E7%A2%BC%E5%AD%B8%E8%AD%89%E6%98%8E%E7%9A%84%E5%AF%92%E6%AD%A6%E7%B4%80%E5%A4%A7%E7%88%86%E7%99%BC-f3d5a5887c5d)》，译者：[Jerry Ho](https://twitter.com/29988122)  | [原文](https://medium.com/starkware/the-cambrian-explosion-of-crypto-proofs-7ac080ac9aed)
- STARK 算术化系列
  - [STARK Math: The Journey Begins](https://medium.com/starkware/stark-math-the-journey-begins-51bd2b063c71)
  - [Arithmetization I](https://medium.com/starkware/arithmetization-i-15c046390862)
  - [Arithmetization II](https://medium.com/starkware/arithmetization-ii-403c3b3f4355)
  - [Low Degree Testing](https://medium.com/starkware/low-degree-testing-f7614f5172db)
  - [A Framework for Efficient STARKs](https://medium.com/starkware/a-framework-for-efficient-starks-19608ba06fbe)
- [深入理解 zk-STARK 证明系统](https://trapdoor-tech.github.io/zkstark-book/AIR/air.html)，作者：[@trapdoor_tech](https://twitter.com/trapdoor_tech)
- [STARKs, Part I: Proofs with Polynomials (vitalik.ca)](https://vitalik.ca/general/2017/11/09/starks_part_1.html)
- [STARKs, Part II: Thank Goodness It's FRI-day (vitalik.ca)](https://vitalik.ca/general/2017/11/22/starks_part_2.html)
- [STARKs, Part III: Into the Weeds (vitalik.ca)](https://vitalik.ca/general/2018/07/21/starks_part_3.html)
- 《[STARK 算法解析](https://mp.weixin.qq.com/s/nBfL0MzqzOxGlSZgw6I85Q)》，译者：zkCloak | [Anatomy of a STARK](https://aszepieniec.github.io/stark-anatomy/)
- 《[帐户抽象随想](https://mirror.xyz/sylve.eth/Un2EYccIpfE3BDevwOf9hWWcSn2NsiRIivZlBLNX7Ag)》


## 💻 其他

- [Quark Blockchain](https://github.com/liamzebedee/quark-blockchain) - STARK 扩展方案
- [Winterfell](https://github.com/novifinancial/winterfell) - STARK 证明架构
- [RISC ZERO](https://www.risczero.com/docs/explainers/zkvm/what_is_risc_zero) - zkVM
- [valida](https://github.com/delendum-xyz/valida) - STARK zkVM
- [zkOS](https://github.com/starkoracles/zkos) - 采用 Winterfell 和 RISC Zero 的 ZKP 执行层


---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law,
[Georgios Konstantopoulos](https://github.com/gakonst) has waived all copyright
and related or neighboring rights to this work.
