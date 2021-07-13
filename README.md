# 混沌工程精选 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

**混沌工程实践社区**精选了国内混沌工程的实践案例、知识文章和出版书籍。
>**混沌工程实践社区**是一个由热爱混沌工程的技术专家共同发起的实践社区，旨在推广混沌工程技术: 第一时间提供海内外有关混沌工程的最新进展和实践报告，最大程度连接全世界更多的混沌工程爱好者和技术专家，期望可以帮助到对混沌工程有兴趣的新人，使他们熟悉混沌工程的方法和技巧，更快地进入混沌工程领域开展研究和实践。

### 什么是混沌工程?
> 混沌工程是在分布式系统上进行实验的学科, 目的是建立对系统抵御生产环境中失控条件的能力以及信心。- [混沌工程原则](https://principlesofchaos.org/zh/).

## 精选内容
- [知识普及](#知识普及)
- [经典回顾](#经典回顾)
- [实践案例](#实践案例)
- [出版书籍](#出版书籍)
- [混沌大佬](#混沌大佬)
- [混沌日报](#混沌日报)

## 知识普及
* [为什么每个程序员都得学习混沌工程](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429688&idx=2&sn=cde9ed932a0ec29cc98353747edf8b8a&chksm=8469c551b31e4c47d97b163a672987776eb1cf20c52667467296e21f5adc342866445c2f9a0a&scene=178&cur_album_id=1809498693138497536#rd)
* [对混沌工程的一点思考](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429562&idx=1&sn=14f6595737350ea5b6ab676d21ca029f&chksm=8469c4d3b31e4dc5b23b1a86473aa23a0e7ac3adfafc33642c7353229014aa994badb91ba0af&scene=178&cur_album_id=1809498693138497536#rd)
* [对混沌工程的五个常见误解](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429741&idx=2&sn=2296e4d6100e976776a404b1ce9d94f3&chksm=8469c504b31e4c1288b064bf562a776c71d5c60350cb625da5f997632ced7028e437e82077a2&scene=178&cur_album_id=1809498693138497536#rd)
* [混沌工程: DevSecOps转型必备](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429888&idx=3&sn=50872732315173969f6ea44ff47f9d74&chksm=8469c269b31e4b7fe9ea6594f6511d215bc2ae89de9b3a19bae9dc37b325b6ae5ac319dd614f&scene=178&cur_album_id=1809498693138497536#rd)
* [云原生时代，我们为何离不开混沌工程？](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429888&idx=2&sn=8dad525a43eaec4f26acbc4af01f8111&chksm=8469c269b31e4b7f6cad08da755d00a0ae986364fa7c63baa92b5958f5ab1be1bddc45460321&scene=178&cur_album_id=1809498693138497536#rd)
* [业界老司机谈混沌工程现状](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429820&idx=2&sn=51e612679acd8bacda7f4a779b598664&chksm=8469c5d5b31e4cc3648c90cfd333cf6de3b0c2e5044a08bad0cb674c6da330ceec068406c4ca&scene=178&cur_album_id=1809498693138497536#rd)
* [我的工作是制造混沌，我与Chaos Mesh的故事](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429956&idx=3&sn=1c9f1013a980d5a1159a90f8bf67beed&chksm=8469c22db31e4b3bac723487eed1b7e10c30cf708980ce85da869f6d132999354aa800df2fd8&scene=178&cur_album_id=1809498693138497536#rd)
* [切尔诺贝利事故是一次严重失败的混沌实验](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429993&idx=2&sn=2c10a16e32f5b8bc919552733c486ac2&chksm=8469c200b31e4b16154df2674c9f9f958c98549cd62be0f96f4a18d32b802482956a6f2d35d2&scene=178&cur_album_id=1809498693138497536#rd)
* [为什么测试对云原生流水线不再足够](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429993&idx=5&sn=99c4c78a00a158a820c597ecd3d9e152&chksm=8469c200b31e4b167fbf47ec78b728ebf93cfecfb58467ec98c2a244423f514520e84450a05a&scene=178&cur_album_id=1809498693138497536#rd)
* [扫盲贴: 什么是游戏日 (GameDay)](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430036&idx=5&sn=3e735a00570beb3c9cb0a55dc2c9741b&chksm=8469c2fdb31e4beb9ec91ffc29b2c2e3d2f8be06d583be6ba5e8ea4aa24161ee9979a0055d7e&scene=178&cur_album_id=1809498693138497536#rd)
* [混沌工程实验的迭代特性](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429642&idx=5&sn=4f3670c2111a83176b999dae235d5a14&chksm=8469c563b31e4c750b64dd6c7f0ef7808234ab0f0044fc329251df5f0231f3c757daad969982&scene=178&cur_album_id=1809498693138497536#rd)
* [为什么基础服务不应该高可用](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430129&idx=3&sn=d2427e95a9c5a915c6cd1b68266565c1&chksm=8469c298b31e4b8e900aeb48e8943cbe7407e6760db3644bc8cfe58e3845ca1eb2f9d672465f&scene=178&cur_album_id=1799383814721355776#rd)
* [在生产进行测试，你疯了吗](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430089&idx=2&sn=fc4854e0364a8fe8d9d04d8952c50ef4&chksm=8469c2a0b31e4bb696f1f0e9c4b98480117e667c4106e8ba93bfbf980d414b4d4c081c65f9ef&scene=178&cur_album_id=1799383814721355776#rd)
* [Netflix猿猴军团(Simian Army)|IDCF](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430235&idx=4&sn=6a4999af9a31bd1b24b13d32b8d1b83a&chksm=8469c332b31e4a249a23d39cdacfc60761760eb984e41baeecb418d662458b0250cdc7a8eb81&scene=178&cur_album_id=1799383814721355776#rd)
* [扫盲篇-混沌工程: 故意破坏的艺术](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430266&idx=3&sn=4fe6cc863b4f90fa9b8a88952cea5fef&chksm=8469c313b31e4a0553732f293fff9b5c27739e00f283405ccc4b9f96508c8459a35aa6002d7c&scene=178&cur_album_id=1799383814721355776#rd)
* [《混沌工程-系统韧性实践》序言和免费电子书下载](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430358&idx=2&sn=651637b4859fa450660b33e00e24e707&chksm=8469c3bfb31e4aa9c005b1b11e28162385a0f295efb6abe4cf65272d9db1ea99c2ca1581f430&scene=178&cur_album_id=1799383814721355776#rd)
* [扫盲贴: 什么是探索性测试](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430398&idx=3&sn=6ac38a119d0f4f88ae1c660dc2f81bf5&chksm=8469c397b31e4a81901eda91f48a2dc1925891b64e30fb7998f6fa4f4a4ba4a2882489472155&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌工程=可观测性+探索性测试？](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430492&idx=2&sn=34d93aad1e2ff3733fa9698872c11d76&chksm=8469c035b31e4923d18ba84ff6a9af94f2d2aaf29d7707faf6f1e310828494e5ffa8ab285281&scene=178&cur_album_id=1799383814721355776#rd)
* [是时候，开始你的混沌工程之旅了](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430691&idx=1&sn=379bb375ba07ac0a2d2197bafa450af7&chksm=8469c14ab31e485cfccedd79eb08b4c9e4f0903490a2a90391e5f580f5cf95ec30e7d1c8e735&scene=178&cur_album_id=1799383814721355776#rd)
* [对混沌工程的一次胡思乱想](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430811&idx=1&sn=cd8c43c17dd44e1ec81818f03ce81d04&chksm=8469c1f2b31e48e4d8388babc403f7028cf89b23e8dccc342f17d2c3fec99b82b2bfcceeb366&scene=178&cur_album_id=1799383814721355776#rd)
* [给网络注入“毒物”的混沌猴子](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430845&idx=1&sn=bcf129ad9e81b46d1da0e5da4736fb0f&chksm=8469c1d4b31e48c274141a78ae547559e007fa3ab17713322b8fcce7a44939c93ac0c55e4431&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌工程: 造车厂自动驾驶安全必备](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430872&idx=1&sn=3707b1b390835f254a1293753a1e23d5&chksm=8469c1b1b31e48a7cf5dbe1402089ba1f0421000846f2896ea0ad598d15c7ccf34305c661b54&scene=178&cur_album_id=1799383814721355776#rd)
* [RSA CEO:释放混沌猴子,获得最大的韧性](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651431030&idx=1&sn=760fac2926646e676732316601bfbbf0&chksm=8469fe1fb31e7709c4306ff27a732377819cb008f1179184ea3f7e2c582f7f780d6197a7f820&scene=178&cur_album_id=1799383814721355776#rd)
* [级联故障研究:混沌工程核心使命](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430945&idx=2&sn=1018b09a913d490ba10e815f0dad15ca&chksm=8469fe48b31e775ed8f62bd692daf3f9a3b0e6fa0bbaca0ef072dba10169ac4323f90e8147f2&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌工程在安全领域的实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651431012&idx=1&sn=ff3049b4eca5f292b8b04f2196fd9d98&chksm=8469fe0db31e771b73b78216a32ae1de4b14eb68cd6c5013b9eb61d2c4deb908f89da0db02d7&scene=178&cur_album_id=1799383814721355776#rd)
* [领导，是时候开展混沌工程了](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651431085&idx=1&sn=15911c034ef894b4f9cf65fc6685ce52&chksm=8469fec4b31e77d2532a2e57364f1687bcf0f095a77288fe268e14dcdb7f81f5d8eb1c4b6085&scene=178&cur_album_id=1799383814721355776#rd)

## 经典回顾
* [Netflix ChAP: 史上第一个混沌实验平台](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430266&idx=2&sn=f8eade2289a49a693d01e9d09cf08be1&chksm=8469c313b31e4a05c0966b1f7190dd0194bf8c0e254506e3becedec704b0d6682a5f6501b25a&scene=178&cur_album_id=1799383814721355776#rd)
* [Netflix教科书: 进取到令人毛骨悚然](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430530&idx=3&sn=584da7e0b9ee7e60e0c64f5a6e8a6278&chksm=8469c0ebb31e49fda3735578e79268e7db1b98ce3f8abf7bcb51a7b9496d1df33e955b2cab10&scene=178&cur_album_id=1799383814721355776#rd)
* [Netflix教科书: 反脆弱混沌工程实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430530&idx=2&sn=808300c0b5ddd6a3da413d4bfd246b18&chksm=8469c0ebb31e49fdba70030bd4fe75bc9bcbf4b1e3c85c0d5240a4e61cafa6b229a05cd00962&scene=178&cur_album_id=1799383814721355776#rd)
* [Netflix: 训练更聪明的混沌猴子](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430959&idx=1&sn=5f049e1869505b83be6bd267c0b19be1&chksm=8469fe46b31e7750bb6caaf0e15cec546781f12a3019515ffe66f4a48a3d3b0dc2c92042922d&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌狨书: 混沌工程的经典之作](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651431296&idx=1&sn=065a1528833bce768d06390b3935ba1e&chksm=8469ffe9b31e76ff364763c4764aa75fdcad36acf0186cf554066d32cab73518d1d4cab6b7d0&scene=178&cur_album_id=1799383814721355776#rd)

## 实践案例
* [当区域性故障来临，你的系统还能幸免于难吗？](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429956&idx=4&sn=eb60a24ce2a001f87be8c9dbea16773b&chksm=8469c22db31e4b3b8e7752668c38b64aaefb34657e42b2869f44526f646ea5c2a5fa5ab6a0bf&scene=178&cur_album_id=1809498693138497536#rd)
* [字节跳动混沌工程实践之场景化主动实验](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430129&idx=5&sn=e3c28f99730e41af0c877d210d50aaaf&chksm=8469c298b31e4b8e680680f0fcdb5e3493ccc4393ea0ab32de50942d76e8ec4b6c365b5fa3ca&scene=178&cur_album_id=1799383814721355776#rd)
* [字节跳动混沌工程实践总结](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430691&idx=2&sn=4b05da19cde91349bdbf3d44cefd2254&chksm=8469c14ab31e485cd71933319aa984813355dba1092c6b0cafdcf74891cea8ac87deb9289e4a&scene=178&cur_album_id=1799383814721355776#rd)
* [爱奇艺混沌攻防大战背后的矛盾双修](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430036&idx=4&sn=ff439ff34bad83dc38cf95608ae53d33&chksm=8469c2fdb31e4beb996b924fa21cfad576f8ba66161d266dd7b5be3f4e8ffc0d04a9a8a597d6&scene=178&cur_album_id=1809493898143055874#rd)
* [FreeWheel核心业务团队混沌工程实践之路](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430036&idx=3&sn=016b673f0f1c75b34832a9ce56c1e617&chksm=8469c2fdb31e4beb7e0257d2b643b5f0548ded18f973b65d6c16654d927d81ac6bcfd8291698&scene=178&cur_album_id=1809493898143055874#rd)
* [混沌工程在券商的应用探索|最佳实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429993&idx=3&sn=799580c0a4b110266926059fc3948b12&chksm=8469c200b31e4b16f59df24bf16099b818b581b7e6df880a44dc7f205e5fc2b6a176a3d20183&scene=178&cur_album_id=1809493898143055874#rd)
* [Chaos Mesh云原生混沌工程测试平台](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429993&idx=4&sn=0ebe15bc5b16a4d4686dbc18d2229085&chksm=8469c200b31e4b162870caec19e30677e15643244c40fc4e0ae39154532db4265add51a48946&scene=178&cur_album_id=1809493898143055874#rd)
* [阿里造了一个“上帝视角”的混沌控制台](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430036&idx=2&sn=7892e3f51dd10f1e85373fdb590c9a8f&chksm=8469c2fdb31e4beb564e2a24a1d32e1b2d44c9e752dedd8fde928ee9ce9b030854c0c563404d&scene=178&cur_album_id=1809493898143055874#rd)
* [使用AWS FIS服务实施混沌工程](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429688&idx=3&sn=e071a66a62e3cb43910004dc15308148&chksm=8469c551b31e4c475ea852e57e6eb2bd5be2b90e083ba1b1e325caa838e92cc71380fdd9c6b5&scene=178&cur_album_id=1809493898143055874#rd)
* [服务网格Linkerd的混沌工程实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430089&idx=4&sn=e2221ac072be1d398e8d1c13bb66bb27&chksm=8469c2a0b31e4bb6bc63490e5a5af15a5eec28d26f428729131df8467a7c24ca6b6fd69247ea&scene=178&cur_album_id=1809493898143055874#rd)
* [LitmusChaos: K8s上的混沌工程框架](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429956&idx=2&sn=b192122d170e21579beb84ea0b5d3cb9&chksm=8469c22db31e4b3b1178fc59af29fcdf2db26aa1709f585d07c151e80b7220c066cb8f203f34&scene=178&cur_album_id=1809493898143055874#rd)
* [云原生混沌工程 - 增强 K8s 应用容错性](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430187&idx=5&sn=fd2e8e408a9e7bdc79f828437ff1571d&chksm=8469c342b31e4a545f8c4eb23390b2eebcb6848639647d8d48ee41dac1dedb2a9bade7fdc3cf&scene=178&cur_album_id=1799383814721355776#rd)
* [滴滴稳定性系列1: 如何做好系统稳定性建设](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430089&idx=5&sn=827c2ee868272db2423565ae3e1f3dbf&chksm=8469c2a0b31e4bb627c7dc3ca47ac6cc8c36e66ee14814bc5975df9b5f7b0df190dd52fb8fdf&scene=178&cur_album_id=1809493898143055874#rd)
* [滴滴稳定性系列2: 如何做线上全链路压测](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430129&idx=4&sn=15d6ce6b2ad0a81c86a925ee82b7d210&chksm=8469c298b31e4b8e2482ec710c2a686a36d8f91744e558615e3e76b890a538e2acaa7e7f2904&scene=178&cur_album_id=1799383814721355776#rd)
* [滴滴稳定性系列3: 混沌工程实施方案](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430187&idx=4&sn=4a71fba6854a8e1bd951be86e355a463&chksm=8469c342b31e4a545d8fbb199a1808fb738d3b6f6c199a773ecf1ccdf25d4a540bbee43d6e4e&scene=178&cur_album_id=1799383814721355776#rd)
* [红帽在OpenShift上的混沌工程实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430129&idx=2&sn=67193a51b186c30788a722fd5ff2c838&chksm=8469c298b31e4b8e1d71b7482e3de0c5f7191aec5205eda9a5fe72512de52bbca7e8d88ae473&scene=178&cur_album_id=1799383814721355776#rd)
* [Loki: 数据流处理平台的混沌工程实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430089&idx=3&sn=a88c506c32873c00edf6fa6d87854513&chksm=8469c2a0b31e4bb677aec744d9bc75073ae0d7c9882d1732c679110fd853def4c18c6714e526&scene=178&cur_album_id=1799383814721355776#rd)
* [服务网格Linkerd的混沌工程实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430089&idx=4&sn=e2221ac072be1d398e8d1c13bb66bb27&chksm=8469c2a0b31e4bb6bc63490e5a5af15a5eec28d26f428729131df8467a7c24ca6b6fd69247ea&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌工程: 苏宁系统稳定性之道](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430235&idx=3&sn=a2fcafe9cbbbd25dcae3c861ea2c860d&chksm=8469c332b31e4a24669434801b3dcb23b77ba19d05d18976ca5511bd040555b2c33e59d178ca&scene=178&cur_album_id=1799383814721355776#rd)
* [小米在混沌工程故障注入平台的实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430333&idx=3&sn=064c5b2f67e30b107f10de71d039aee6&chksm=8469c3d4b31e4ac2c9bfcd8638118d2f29f08342d45502e5418e85ac833f966c0ef6bec7352d&scene=178&cur_album_id=1799383814721355776#rd)
* [工商银行的混沌工程平台应用实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430358&idx=3&sn=45f688b9f0dac5747802ad79d69f5a39&chksm=8469c3bfb31e4aa93228bbdb6900b35d68ee4c08059d6d19ff951bb0744080d45168a3d1ca8c&scene=178&cur_album_id=1799383814721355776#rd)
* [携程在反脆弱方向的混沌工程实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430398&idx=2&sn=e764739e1c699623e91bb6e65205ca49&chksm=8469c397b31e4a8106d8c56db17a5d777adb2bd6506a326692b430075a9299350c22630360c9&scene=178&cur_album_id=1799383814721355776#rd)
* [酷家乐: 混沌工程在创业公司的实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430462&idx=3&sn=1a2c6d429c55c1582ed9fcaaf42983a7&chksm=8469c057b31e49411aacadd79068c469c39bc789b520159ffe4fab0d9eff788063366bb7b791&scene=178&cur_album_id=1799383814721355776#rd)
* [史上增长最快的SaaS公司Slack的混沌工程实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430462&idx=1&sn=5b0444c684b36ed0f73088682b2d18de&chksm=8469c057b31e4941550f8e29ba7b9a509bb1fde901b09977eec98d4c5b832232f577fa4cb078&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌工程缓存实战系列 - Redis](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430511&idx=2&sn=47a2e3c0db54b6741daec2c693e0f39f&chksm=8469c006b31e491081b09c1245cab98b90e7bdc27417b1ac6cde6df9f978bd864d6f2d4f8ba4&scene=178&cur_album_id=1799383814721355776#rd)
* [Gremlin: 拥抱失败的混沌工程实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430553&idx=2&sn=79032c1814556ec8593c5b08b301308e&chksm=8469c0f0b31e49e62de331ec5cd8ee37758ae38334ecdf84f8a9638fedcea0962658db99d35f&scene=178&cur_album_id=1799383814721355776#rd)
* [特来电的混沌工程实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430627&idx=2&sn=1ae1967457d7f8530d03edd6ed53893d&chksm=8469c08ab31e499c5c29e771f1028146d4bff5d67764f7e8f948235ac441ed429772dd32d776&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌演讲-.NET架构的混沌工程实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430797&idx=1&sn=f358c04fb73d569ef05706325c17db65&chksm=8469c1e4b31e48f299cffcbe688536960dcd2985d6ceb6bfb007a4d3c2c66801c9646a8f0af6&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌工程底座: 两大巨头的灰度实践](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430825&idx=1&sn=90f6c7a6425d3b9a519a165a196eabbc&chksm=8469c1c0b31e48d690a7da01477f60a3a5f97d9a7971797cb28cdeea1b38e3a9b06821d9f84c&scene=178&cur_album_id=1799383814721355776#rd)
* [Apache Kafka的4个混沌工程实验](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430929&idx=1&sn=82bf42184744bd62df857a28a83ddee8&chksm=8469fe78b31e776e5e8af15c1b33ccfa41f46265f117770a96a360f2b4a6a2080426a4176a42&scene=178&cur_album_id=1799383814721355776#rd)
* [Netflix: 训练更聪明的混沌猴子](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430959&idx=1&sn=5f049e1869505b83be6bd267c0b19be1&chksm=8469fe46b31e7750bb6caaf0e15cec546781f12a3019515ffe66f4a48a3d3b0dc2c92042922d&scene=178&cur_album_id=1799383814721355776#rd)
* [灰度黑洞:零风险的混沌工程实验](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430990&idx=1&sn=1d715a58e8efdf3f01d492eae2e3340a&chksm=8469fe27b31e77317535fe863b9f8135ccf349ed1cfe85cab6d70ebe6cd09d9eb55df09fd627&scene=178&cur_album_id=1799383814721355776#rd)
* [Jepsen:分布式系统最早的混沌框架](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651431110&idx=1&sn=7b7de4e03ed1a72e70e5874862f7dd2a&chksm=8469feafb31e77b998bc612265613f9535dc4adf0fbc723fb6fd515fb1ccb30f2041aeba8bfc&scene=178&cur_album_id=1799383814721355776#rd)
* [引入混沌实验的持续部署流水线](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651431150&idx=1&sn=350000420b58794381ed54329fc099a7&chksm=8469fe87b31e7791945503402063a40e46207ba5b28a990b7c07f636c1428a20415b0722cc06&scene=178&cur_album_id=1799383814721355776#rd)
* [Lyft: 基于服务网格代理的混沌框架](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651431186&idx=1&sn=3ea3b23087767c4a234325cfb84a926f&chksm=8469ff7bb31e766db9cee13b7c12f1b359e22623841f8dc122e6d17a6847ca6c03c535e2dc2f&scene=178&cur_album_id=1799383814721355776#rd)
* [Datadog混沌工程实践干货分享(上)](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651431226&idx=1&sn=e08cdb55ac1718bdf18c8ec2977230c5&chksm=8469ff53b31e764588d748d887206bbabf13526e13ca495a03337b79f8dd26663a9d389102a8&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌案例: 提高零售网站的可靠性](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651431252&idx=1&sn=2740b44ae47958ce9e16590fd635f777&chksm=8469ff3db31e762b4d039fe764096641d91697a05fef50bd205e13e6f109c221bd8355039adc&scene=178&cur_album_id=1799383814721355776#rd)

## 出版书籍
* 《[混沌工程实战](https://book.douban.com/subject/35141777/)》
* 《[混沌工程实战：手把手教你实现系统稳定性](https://book.douban.com/subject/34466272/)》
* 《[混沌工程：复杂系统韧性实现之道](https://book.douban.com/subject/35507343/)》

## 混沌大佬
* [你认识这个混沌工程大佬吗 - Adrian Cockcraft](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430187&idx=2&sn=9336a315b48c9a73e6a866c40facab1e&chksm=8469c342b31e4a54f7fee753fa52affe2c8bf95de90d5f66e9fb815a892660346b83a536224f&scene=178&cur_album_id=1799383814721355776#rd)
* [你认识这个混沌工程大佬吗 - Jesse Robbins](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430333&idx=2&sn=dfd9d6e5ede5763face10687e268d7a3&chksm=8469c3d4b31e4ac285adb710bd69db01a073277f9eb624ccdeafef39ef52ee8cd398fc0a61f7&scene=178&cur_album_id=1799383814721355776#rd)

## 混沌日报
* [混沌日报-2021年5月13日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430945&idx=1&sn=d40ac326e893b38d2f1d43912359f9f0&chksm=8469fe48b31e775e6a041f46a0e012283382f429e70e7cab9b7d08fd152a4de413567a76611f&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌日报-2021年04月28日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430578&idx=1&sn=ab9e4a5c77f6a87a9ba936f36ad10fec&chksm=8469c0dbb31e49cd636dfcdd8c90b3137a4988cfed5f678efd557ae331057821fdcf2264fa76&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌日报-2021年04月22日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430564&idx=1&sn=f29c38f044ba2221395f94bde9689a9d&chksm=8469c0cdb31e49db72cb32ffb579b8003193816a111f8c532876d384060a35325e222ee52039&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌日报-2021年04月21日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430553&idx=1&sn=f6aae302b09c23817af079d9481a1b5a&chksm=8469c0f0b31e49e697aec5c303add6db4d3c6061ec978c44ab80a5dcb1c69f87fa558749ed46&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌日报-2021年04月20日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430530&idx=1&sn=1887ef0fc72ea5c5f16e6e5c4a4891a6&chksm=8469c0ebb31e49fd967ad75afbf3e99b75b11caeaff08f1f45d0793f090e1a1a9d6682375cc4&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌日报-2021年04月19日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430511&idx=1&sn=6e28933632751b61f02a4cf18ea9de2d&chksm=8469c006b31e4910af830b3364a79a203ddc3630adb54b38ca17fd379d4c36f2819811588368&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌日报-2021年04月18日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430492&idx=1&sn=a6107d8aca297b168c58d52f4ab23973&chksm=8469c035b31e49230982cf42facf1fe158cbee379d367a39ff9f7b9f2c25d04065914f783c58&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月17日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430462&idx=2&sn=735340f17f2b2d4163bae0414693c97f&chksm=8469c057b31e4941fb61b41a1fa73810b8d4c39e6bc91537b66525e50f3c43b2d2cabd76a41c&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月16日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430398&idx=1&sn=397cfacbad30385d189a552b55bf9091&chksm=8469c397b31e4a811bcaaedb00c2bd92ead9590c82cebdd39164c57f1306d1d2a5edd79bc768&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月15日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430358&idx=1&sn=5354239606a032a47bbb0c7c7f987b1d&chksm=8469c3bfb31e4aa9bba8adfd589e0c1d9065336d114b555ca41f5e057e49bd450c41696e28d8&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月14日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430333&idx=1&sn=bfcebf86b7a69d98887ef5fcf4cc508c&chksm=8469c3d4b31e4ac2cc8baf637f767cd69551e1e4dbe02da57c8dd6252edc44807e248e8b95fb&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月13日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430266&idx=1&sn=8b26ff195e07555e6a303f1955f3c792&chksm=8469c313b31e4a05ae56239467fba0612cd726359f3a0506fa8695580481161564635cc8143f&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌日报-2021年04月12日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430235&idx=1&sn=90ba8e1ff197e95d6805d9e879142030&chksm=8469c332b31e4a2408f95e5036d2ad19446a6f74beca7a0c96800357886f3e0946a74f889466&scene=178&cur_album_id=1799383814721355776#rd)
* [混沌日报-2021年04月11日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430187&idx=1&sn=12df33c6aa1ef796e4dcba67d4b44ff9&chksm=8469c342b31e4a5440e0aee9560728b2ff16736977dc6bc21f20334ccb8e071bc79876cf8735&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月10日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430129&idx=1&sn=ee02a7d46d6bfff95ce0ca2e01c7f2dc&chksm=8469c298b31e4b8eacfacb81735f43a893f3c55fd1f2a0cfb98727f33831380116e73ad79a49&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月09日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430089&idx=1&sn=3ce12f9fbc2dc858af454699f1692016&chksm=8469c2a0b31e4bb61c2c04738acba761369b14278290a8e0065b0352e114f84e04d2724b5879&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月08日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651430036&idx=1&sn=710444fbef93b7cdd66e319d0e343e39&chksm=8469c2fdb31e4beba77135a6d2750d8024ef6fee4c7200fc224de66a226c5b2be64fac5983dc&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月07日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429993&idx=1&sn=2d12e816ea0deef2f430d6d04591f4ac&chksm=8469c200b31e4b1608e042aa7c35b115d82e18fc309420051cf6693fdeb97b446d2d01fa2562&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月06日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429956&idx=1&sn=e1366a398fa10f3a3559bf772581415c&chksm=8469c22db31e4b3ba4da8bbd13456ec53fbc0fc2efb32d6f4ef3645af8c9752498e861ff99bb&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月05日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429888&idx=1&sn=5b5ab327269109d1f9d52ea1a7db7738&chksm=8469c269b31e4b7fecc7488b15e4bbcd9e881172b6c0dde4bf63e53038ca8ec6707152cce7f6&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月04日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429820&idx=1&sn=a23843174b66f54711982dccc145d50c&chksm=8469c5d5b31e4cc32beccacc3839aa571245ddb302544702d957a7350c34b3c70b125b555881&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月03日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429799&idx=1&sn=4f6673090f0845ec911b051a324c6158&chksm=8469c5ceb31e4cd8d1d723d2416de9505fb28495a1851aa4eb030ccb660d262881ef360a48ee&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月02日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429741&idx=1&sn=9d65ae622c74917dbf2e254cab52457e&chksm=8469c504b31e4c12be7f92be30dc85cc3e8917d0f674f42854aadddefd2a4949749340c427ee&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年04月01日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429688&idx=1&sn=074adf937560bbf5f00e684bb5391c11&chksm=8469c551b31e4c47be81f1a224f1d8fed35c8414419985e4be1ab3ecfc1bb8da976e7d0c5bab&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年03月31日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429642&idx=1&sn=c52465ace37f440d74d1b486ae116161&chksm=8469c563b31e4c75a06cdd9fcdcb2c70204bc57620e790df642297190dafb92816d8b407e8c0&scene=178&cur_album_id=1803953058595323905#rd)
* [混沌日报-2021年03月30日](https://mp.weixin.qq.com/s?__biz=MzA4MTQzOTQ5NA==&mid=2651429582&idx=1&sn=e348475416e6f68c102ad8beab6f8d26&chksm=8469c4a7b31e4db1d3f6b27a77a25411a33a46edc5c0886746d96dc1f535457f72d7c8d0c8f1&scene=178&cur_album_id=1803953058595323905#rd)

## 联系我们
请关注**混沌工程实践社区**的微信公众号：“**混沌工程实践**”！

![微信公众号二维码](./qrcode_wechat.jpg) 
