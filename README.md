# Heimdall 大中华镜像源(修改版)

[![Heimdall_Banner](https://i.imgur.com/iuV8w3y.png)](https://heimdall.site)

[![Discord](https://img.shields.io/discord/354974912613449730.svg)](https://discord.gg/CCjHKn4)
[![Docker Pulls](https://img.shields.io/docker/pulls/linuxserver/heimdall.svg)](https://hub.docker.com/r/linuxserver/heimdall/)
[![firsttimersonly](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](https://www.firsttimersonly.com/)
[![Paypal](https://heimdall.site/img/paypaldonate.svg)](https://www.paypal.me/heimdall)

___

官方网站 - https://heimdall.site

原始项目 - https://github.com/linuxserver/Heimdall
___

## 改动描述

为保障应用初始化, 我将 `/app/SupportedApps.php`文件中的

https://apps.heimdall.site/list => https://gitee.com/sKai-Zhang/Heimdall-List/raw/master/list.json

链接更换后将不再从Github获取数据包, 而是从当前镜像项目中获取

### 筛选方式

我们需要先访问 `https://apps.heimdall.site/list`, 获取JSON内容, 将内容通过正则表达式 `https://apps.heimdall.site/files/[^\s]*.zip`, 进行筛选, 最后将所有数据包下载至当前项目.

## 使用方式

### 常规部署

替换app目录中的SupportedApps.php文件即可

### Docker部署

容器下载部署后请勿运行, 先将容器中的app目录挂载出来, 然后替换中的SupportedApps.php文件, 若您已经运行了, 请执行 `/init` 重新执行初始化.

## 已收录应用包

212个

- 986692d42d54246a445cd11157227245e39a053d/files.zip
- 369ce39bc37015dbc2cf17c527531678d9699305/files.zip
- 8a6dbc9abb2120c3376e8475bfe5d2f9e48ce309/files.zip
- ca4ebd4dc66d0a7108167227362d07687dbb3561/files.zip
- b3cfefdec67f55e67ae15cf4d9a460e117cd8519/files.zip
- 0eb761de35990e769c420a4cd9a9d76290a87e26/files.zip
- ab3084f780c2d93d72ab6503637a5d782d679ea1/files.zip
- 36c5d7c2cca0998f1581d867bd4b2786d1afb219/files.zip
- eee5af4295bda1c0669bdf40364de35371554afa/files.zip
- fc32681b7e2286b438e8feca148d422529da2bed/files.zip
- c63259ded422eae2d24881076a83410c9e59d948/files.zip
- b9cbe7ca2b854ea9aa2b9655e0244e202c37c2d1/files.zip
- 42b669272b7b66bf0ce97e67944d5d637a8fc127/files.zip
- 92198a2c04fb2a6c6476134e86048951cd06ade9/files.zip
- aadc1699faf97eb8b48f45c7e246aa428b6d63ea/files.zip
- d482ffa527c31d31f3e98118daa9a932e4554481/files.zip
- d154af36e620c5bc9e0635f9eb6d2c6fe0c30bd2/files.zip
- 0efa3d5c86ee24ec4529821a851ecbcce6b9f1a0/files.zip
- 90316bb1f9d59c6af63275c83aa2daab49ce5b83/files.zip
- 8b34ca130132c19111d74446e411c256bf03bcb1/files.zip
- 6595da795382ca313324de5b169f2c1ca0141f0b/files.zip
- 423530d740f2ef88bf319fa0077374a37440c363/files.zip
- 6a4280d9229a3a1878dc11e08c3e6e1496647ed2/files.zip
- 2c242624982614e7fbad6de35ca58fbedb027875/files.zip
- 873d7dc9e293a044337b4bce1499af926a7682d3/files.zip
- e5c64df7f5118f0816d6d56999f01330f56cad38/files.zip
- a6a1738a48312d9e137f828c934639985c8930ee/files.zip
- 6adb7b4fd29ba9f4b7bc6483557985ab7eb2a2f3/files.zip
- d8673c6995ceacc35a4d32b2f223dd42a588112d/files.zip
- 11a0118ccb4c48aed955b8047cc4b1dfdfea5879/files.zip
- 6595e1a45bc2412944eb112085931bf38abad277/files.zip
- 00e1cbbefa4a142d6344fe223919043809beae6a/files.zip
- fcfd98391344b6eadc8932ded9071bae8a95a353/files.zip
- 2e5b3f091caf6b505d6b34d6977b58c77a84c11e/files.zip
- 10e915f2ffe9802a28f01c629d167f1bb009c539/files.zip
- 4cb71f2cfbaed6731b23e65a51ae786459f94949/files.zip
- fb10a0a318d081af0025e3f4c193ad7e5652d94c/files.zip
- dae269990a0dfad0c319ece01b53a0e5e467865c/files.zip
- 88084f291f9ed78bd19d4caca1cbd276cdae551b/files.zip
- f15c6abe982b50425529492f2d171f9db16fc152/files.zip
- 26f0515546eecf7cc97cb098e10dc6bc6b5654f9/files.zip
- f8feef8c4382915f4ee97a78f34792579120a9e1/files.zip
- edd4eef6c7455a9e765b2e235bf62b16f8f0ce26/files.zip
- 32089a2fea1e290e804dfe81a060ea523df1ff2f/files.zip
- 786e3e080c19e3e169988f5048b3f43fd26bb1c8/files.zip
- a690ba702afc4ae3947cd9d7fb04fc9d3a819558/files.zip
- 92f97ee896e74b78f8200f0e189b95003a49cf07/files.zip
- 0a975868685c3fac3a80d22664a6d2243601b8c7/files.zip
- 8bdc723735754e726e365e3a68ff3a85aa2ebaf0/files.zip
- a933ef709b9219d93549c5c5f6259a0dc75161ef/files.zip
- 8b8b5d6d73681196c4541f2f414e6815756cb14e/files.zip
- f88355c91be2c78267d2b6a9eadefd2280e9a373/files.zip
- c8d77b64870b6c8e19f3df8aef852dd2a2c804d6/files.zip
- 5a2c6ba6bc43d3289a54a4df3b5dbef82a8f4aa1/files.zip
- 74cffcd71296b98f42a5e30c733c499cc699161e/files.zip
- 91e93c5a23846d9dd210c22bfaefae515167eb19/files.zip
- dad3f43fcbd68c73564e56fa64d2d13c4b2ebd30/files.zip
- 8b6f269ceeff73168eb23016e94480d2d485412e/files.zip
- bb4f4ac56f406f066cf61440e33dd60e127f6bb9/files.zip
- 41a200017219c40be0b7c8d5c72110e8f8051f29/files.zip
- d5263aeeb64d889fc6f4c6790c42d9996cbdf1cb/files.zip
- 73ad3bd5ea14c3c56a6057acfb569cba7822e9e3/files.zip
- b3ca905d868334c0f1e805cdb69b9e8770a2920a/files.zip
- b64e95a4cb1284ff48faf18b4d8e221510f2bc27/files.zip
- e227126e5e1725c86122d975038e74f3c5c8aa1b/files.zip
- 17f76c0463a1b1a62a5345cc6b6b988ade62d746/files.zip
- 9bc854e7f894930ce87f540bf58ad93f9da46736/files.zip
- 81f62acdc8149eee6fb210eccb9b97b8cbda4121/files.zip
- b5f35d059afbc9d35a90b93ff74d4a04be17e015/files.zip
- de9e51e663ac53e15efc9183c80a0d7d4471d692/files.zip
- 5fe3559914b570f96b3b5c16175d156f2499629b/files.zip
- 79186f88f6ebb6b7b3a4a5767f2fb73628bdc7bb/files.zip
- 8d18119eaf1506e400639a91c2aa04da82fcf60f/files.zip
- 9634cb12585605a257a32c225c2c6fca51632f91/files.zip
- ffb1290346c6ef24553a8799c7f860744fa7b5b7/files.zip
- 2b75aa031cef137e2c84351fc12f4e0f6dc494e6/files.zip
- 56f2a241126f80bc407fa54ab187b7e1d114ec8d/files.zip
- 4474d1d2572eb4244f7df556da3809d0808a7789/files.zip
- a8c74a64ccaab163c9b7c69b26284ee2ea6ce7c9/files.zip
- 662de4d013b0a1aedb899ac6e128cbc170be650d/files.zip
- a9854053e5ff2303861ebf6c90b0fdadcacd9661/files.zip
- 17db2c8aa972a9aa01978abd70036c3a47974dd6/files.zip
- 81cd29f75be4ccce68d6bc3e7dfe6e0c471f65a4/files.zip
- 8a76f097e06cf0e7981102e27c42ec453fe0caa6/files.zip
- 902d30fd9799218233280085d01b836b176b1058/files.zip
- f89efecd6037f92585bd71cc08bdc5eea852de6d/files.zip
- 95c148659d2b89bea53da15abeb86c5572161eda/files.zip
- c7fb8f352d99400ca1280c5824946636ecd2b2f0/files.zip
- ec209cf3ff5db2ec67958dd16b24941d43afe3ef/files.zip
- 7cbe2d6ebd221edbe4c583796c649b2c78afc25d/files.zip
- a10af56cf6f4d1f219604ffaaf79a42cbc452382/files.zip
- 4a43f3ca9a997acff2418eacdc60e6470b07a2ae/files.zip
- dc57753826153bcad4b8565f7bab1cbb1d89fe2f/files.zip
- 68de52dadc694cd3e0005a7aeb021b5f240e4380/files.zip
- 41aab2e65b3b388d1a99af8c0c2c1735a55db8be/files.zip
- 974cffac18cbffaa7a56a278e0ccf2790a662866/files.zip
- 2a033ff469db2babce7730790554cdc4cb6d3211/files.zip
- 2c2c587e500000eb386a18ce936158532c71fea6/files.zip
- f6a8a40aced7deb7778a2516d93f337cefa13f26/files.zip
- 2c0cba4ba710eef2750fd2461df9241eaa259b47/files.zip
- 0ab5456b94bc50c0e513dd59fb446b5b37e27bd4/files.zip
- dda9dec8bd0cd11ac73124e8785e7809b0d01155/files.zip
- bbb5c07125af96a6880f011cdb1f8a27db582f1f/files.zip
- 5d4d048cd73ceba92c993401f4027106b683397e/files.zip
- 16683617d71a3ad34efe6b7db5399fd67690ecb9/files.zip
- 2bf68a625b1ea2eb473ae55903af211f5b9735c5/files.zip
- f10461cc010fe7fed9bd2aa5d431b097ee262de8/files.zip
- 6ecc3e7172b8f6b643015d5291d577aafd349197/files.zip
- fe494c29983894e4ea051d9e53631f2ba4d777be/files.zip
- 9cef89f04616c2efac5690b8eff5555bbeb0ea33/files.zip
- 93c08ccf13f065cc7ada6a5439115e45e1a50aad/files.zip
- 8aebb6c7e612d0221eb69159d8d0d7309a1d0f05/files.zip
- b8c459f23d6b6740e840f0bb147ee2c129d9d091/files.zip
- 6aec9dadad34d597339f01b2e01c19e1ac14fd0b/files.zip
- fad29ae901489afca031a56e030f9771bf1fc983/files.zip
- ea56e10860044f4d39c3c58729405611fcda0718/files.zip
- dbaed4e6d08d0cf7e4d6b3eb21b696fbff504ba1/files.zip
- 59fd8c7b968f86bbf85c8ed6ec50d957ef36dc54/files.zip
- 4a77d043ab270b33d71e654b92c6faafdd085a0a/files.zip
- a19f80135a3e7ac748e0f813926466f25873c90b/files.zip
- 574eda1f8ea53e4633ba0d2a2af8d143fb3d9ffd/files.zip
- 67ba7f5159bbaaa723288e79b453006d51720522/files.zip
- 64f6d1ed1ae435dd2ee01b22ce575299d4157483/files.zip
- 7438633dd367696bc177d31096cfc86b27c4f833/files.zip
- f203c59f40b36ceaf54211812513dd17fe068218/files.zip
- c4cb6280a4916f99e8b65f057aa5940c1c265fea/files.zip
- 1da501929663658f287156d3d7583ea4c94c9378/files.zip
- 65c9f4e80e9e496d194e47b481ce05d2c8eb69ba/files.zip
- e450f6149880caefaed5452becee7e4e3d28e824/files.zip
- 7713720dd82d12528935857a4584885ad4512b9f/files.zip
- 2c50212b91de2fedf145a954c5fc9bb7e0dfb046/files.zip
- 1eef7977121f53a07f92e0e180b4fa9f3c02e44d/files.zip
- 8ebb3c7a1a0b4d608963c511826249b6706f183a/files.zip
- 75a0875259394285f34c2de9e622f43fb0280b00/files.zip
- 668407e7dfbb4d487deeb8ee9dfdce003467a345/files.zip
- 0251236bfbb4cfd0d40114fa085d7944d4e49016/files.zip
- 8c939eb2c9df3f1a32e729153e36d5a3b79dcad9/files.zip
- 36a1c86357ab8385a6d9f57ce104999fcee90968/files.zip
- 75933e5a8a0cce994a2637c1cf897ec21b79dea1/files.zip
- fca5a7885c8a23f58c270f320e59a3ffd969c4f3/files.zip
- 850c02c07bc32c063ad57054eac44635ce18c519/files.zip
- 3846f66bef88084251d8f3c5db3515a9aa1882f4/files.zip
- 2e3c73e67fd5a7e1074d5f71d67da47afd5204c9/files.zip
- a59aa00d99cb22f71084a61e112408b0cddf138c/files.zip
- 897b30daaee4dbbc1933fcd0dac410661367fdba/files.zip
- 33eb8491580412e10f86d472d2729c8b4c0fe036/files.zip
- 529868983a68fc06bbc40ab80b93ee1ed483a8aa/files.zip
- 9c1dfa6644a65c6fbd73ec246cba43af23ee3e88/files.zip
- 540cee7f198b120f8f0470bebf3ff7ceda19180a/files.zip
- 034a473c9439ae1974867d61b7a49ad63d28c8f9/files.zip
- a79110ba7c9266fc8753d13868f7fac072d2e975/files.zip
- 16a0a16b9b2ac2c0c73e93475c527c51fa7ea1d4/files.zip
- 4cebb740da66ef4c774e30a2401945284e28d3ac/files.zip
- b1787202245142d580b78fe6e486486d6c57a9f2/files.zip
- 1cc58d362348080edb673569a6d190b2db10e4de/files.zip
- 5427a828cd6f93c88faf551c3aa27a8ee8d0532d/files.zip
- b3f62ec86c20cf3baad5c201490dc779588bf6a0/files.zip
- 900b8ebb02e8d094bdc87943d8b87e29cc3e43f9/files.zip
- 42e91e9688897c9c667ba85e06f452aec10f055d/files.zip
- 95174038b6716ece30a894c2cd9c559bbb9e701f/files.zip
- eca3c757337f60b8f263519267cc421c3c9d3c2c/files.zip
- ecc9ef0bc5b99644661a5ae7d21ab845530b6e73/files.zip
- 05a1606d6d189bd5626318b4640e46cb70f76dc4/files.zip
- 580989aa95a177ca47d219c952e2a14518162505/files.zip
- 37f9eafa9d30378a632ef1c0ce2e494f187973c8/files.zip
- dcc622ca3af08f936c95b99fb5b005fbd19eae10/files.zip
- 3624bb3cad52bbb8b9376226d50b29cdbd64ea5b/files.zip
- e70fd5544a13633a53a6716eb585f70cd348904e/files.zip
- ebfaa316961f375f928fb9ce0f1c5c0d36a1eca2/files.zip
- 2e59e5ae3a95b3145a0073e131a010c0d1f817fd/files.zip
- c609eb59ec78e0fc23f8cb0259610f0ef45dae83/files.zip
- d6159cd5263e0b6a34af934ac51c8e3a8edcaf32/files.zip
- 7b203c6493d4773ea7d929f62cfd3d6809560e50/files.zip
- 5b764f1b969988a52fa2a173e2fa9106e1a375b0/files.zip
- 7a7bcb139f334d31f13b475bd602630caeacf5c8/files.zip
- fcd5989c11c29ecbc0ea92e64f4364171bbd1c7f/files.zip
- d3ad7cf1b20224a1ab6d8cd81c876e38d52a7779/files.zip
- e467dc8d4d86ac7f4092f6f722ab7469f3f9fa0e/files.zip
- 7f7164a0e9b857f1ef23f015face718a5256c450/files.zip
- da64278570532417e529c7864da93edd49b47d9f/files.zip
- 3a613f9d39391a6d259d62243e41d267ca861e6f/files.zip
- 8c4c39e9de1521267e8eb98bc6c01754901406e8/files.zip
- 383148f0dbf5f20224e87ecaeebbd18ef8e583bc/files.zip
- 7e74e6b4f7963af636393ee397d0ec7f1a610bd0/files.zip
- 35d0b96bf9686106b00e09baa8d446972a993975/files.zip
- 05378a1bba9c23fda8fa87a3b7dffae1b7bc9f41/files.zip
- 673d272d5be967f5b79e284d921ec9387a3ec93b/files.zip
- c1c10a6c065781445b23c1e0c809ee6a27f71189/files.zip
- f048b1054320b96cf9334a0054aba16c004a6309/files.zip
- 104197735f2a9a78802694aa8fd7d445d4a114b6/files.zip
- 35c310b4b97651f8f270644de0a022f46821037d/files.zip
- 4060fe14019a8726037de3b1e4e5c02f1966ad4b/files.zip
- d8408073b77aa410732b33d94fd0e6d71ef2f08a/files.zip
- edfd64b4540a0b0562b7a2ef1360d4a7597c5cc8/files.zip
- b25ed1401e2a33a1e90f7cddd473191149d38859/files.zip
- 1027e60a5cae371e787570e1b3c47a341ced9f97/files.zip
- 7ddc21efab49839edba446aecbd1606e9b5be3e1/files.zip
- 39473f75a1c2da12383ad2535468737e54d5d610/files.zip
- fc1ca15de7810b005f69f51cb74e4cac43ac1eca/files.zip
- 0a439b1434cb1989929a53e7b11f96ba9bb53c09/files.zip
- 241f625fb9483770b1a6ee738e40f9784617b88d/files.zip
- ab0b5abf5873832766f9eba1607f62b372f96826/files.zip
- b3f63458760c2ef374fdef4bd4ffd7114cb7bbba/files.zip
- 930b04c3c5ceedd30e11acd008c624ed8239f792/files.zip
- 43606b34e8c36a663ec09be6d0449420452061e2/files.zip
- 6001389339bfa5af050b7f46bcddfe3e9fe78229/files.zip
- 46f6cf61df48e47f5d073a55a17160917bf9feb2/files.zip
- 8370dd8753b1b6df9f199553e0e6e51fc162e54a/files.zip
- 8e33e85f7de679ac40e5066a7ead38a74475cb6b/files.zip
- 50052bb8aa17c255aa40f025a2a52980f00e5c98/files.zip
- 32a2bfdd58b38cd145b79d43f1ca21b786b1921e/files.zip
- f0cc2b946e0d95559f2572e1e6aa87c797c30528/files.zip