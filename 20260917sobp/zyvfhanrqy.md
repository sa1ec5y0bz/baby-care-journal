# 【六院新闻】上海市第六人民医院贾伟平教授团队联合上海交大与清华医工交叉团队研发深度学习系统：可预测糖尿病视网膜病变进展

> 更新时间：2026-09-17 (UTC+8)

2024年1月4日，上海市第六人民医院内分泌代谢科、上海市糖尿病重点实验室贾伟平教授和李华婷教授团队，清华大学副教务长、医学院主任黄天荫教授团队，上海交通大学电院计算机系/教育部人工智能重点实验室盛斌教授团队在国际权威刊物《自然医学》（Nature Medicine）发表科研成果，可精准预测糖尿病视网膜病变进展。

该成果是医工交叉团队继2021年成功完成糖尿病视网膜病变辅助智能诊断系统“DeepDR”研发之后，进一步构建的基于时序影像序列深度学习的糖尿病视网膜并发症预警系统“DeepDR Plus”。该系统可基于眼底图像精准预测糖尿病视网膜病变进展，成果为推动全球糖尿病并发症的智能防控贡献了中国力量，有望为全球糖尿病视网膜病变的筛防新策略的制定提供指引。

**DeepDR Plus系统概览和研究设计**

糖尿病视网膜病变（DR）是糖尿病最常见的微血管并发症，也是全球可预防失明的主要原因。该病初期症状隐匿，病情严重时可能导致永久视力损伤甚至失明。由于不同患者病情进展存在较大差异，每位糖尿病病人患DR的风险和时间难以准确预测。

目前，以深度学习为代表的人工智能技术已被用于DR筛查，然而基于眼底图像来预测DR发生风险仍是全球关注的重难点问题。在糖尿病等相关慢病诊疗和管理的临床实践流程中，糖尿病患者往往只会按照相对固定的时间间隔进行筛查或随访，并发症的确切发生或进展时间无法知晓，这也导致传统深度学习模型无法实现疾病进展时序轨迹的精准建模，进而无法预测个体的发病和进展时间点。

针对这一困扰全球糖尿病管理的关键技术瓶颈与临床需求，本项研究首次基于大规模医学影像纵向队列，涵盖多国多种族的超20万名糖尿病患者的眼底图像和临床数据，创新性提出了基于Weibull混合分布模型的疾病进展分析深度学习框架，创造性地将糖尿病视网膜病变的进展和发生时间视为筛查区间内的随机变量，通过生存分析与时序分布概率建模，成功实现了对糖尿病视网膜病变进展的风险预警和时间预测。

研究团队通过将该系统应用于中国和印度的真实临床流程，证实该系统可在大幅降低筛查频率和公共卫生成本的情况下仍保持极低的漏诊率，从而为将来的糖尿病并发症防控实践提供了个性化筛查和管理决策的依据。

早期筛查和干预对于DR的预防和管理至关重要。国内和国际组织大多建议无或轻度DR的糖尿病患者每年进行常规眼底摄片检查，以便及时发现视网膜病变并进行干预。然而，由于经济和医疗资源等因素的限制，尤其是在中、低收入国家，糖尿病患者常规眼底摄片检查的实施和普及困难重重。本研究首次实现了个体化糖尿病视网膜病变风险和时间预测，DeepDR Plus系统仅根据基线眼底图像，准确预测未来5年DR进展的个体化风险和时间，优于传统临床参数模型。

此外，DeepDR Plus系统可以准确识别高、低风险人群，提供了人工智能驱动的个性化的推荐随访间隔（低风险患者给予相对更长时间的随访间隔建议而几乎不导致威胁视力DR的漏诊）和管理策略（高风险患者给予相对更严格的综合干预建议）。

人工智能驱动的个性化筛查间隔纳入糖尿病视网膜病变筛查系统，特别在发展中国家，可以极大提高眼底摄片筛查的效率、公平性和可及性。该研究为糖尿病视网膜病变筛查、预防和诊疗指南提供了新的证据，有望对未来糖尿病视网膜病变的临床诊疗流程和医疗费用等产生重要影响，在世界地图上为糖尿病智能防控贡献了中国技术和亚洲力量，为“一带一路”及全球中低收入国家和地区的糖尿病管理模式的提质增效与改革创新开辟了新道路。

上海市第六人民医院贾伟平教授、清华大学黄天荫教授、上海市第六人民医院李华婷教授、上海交通大学盛斌教授为本文共同通讯作者。上海交通大学医工交叉方向博士生戴领（联合导师为贾伟平院士与盛斌教授）、华东疗养院陈婷丽主任、上海市第六人民医院吴强主任、上海交通大学刘茹涵博士等为本文共同第一作者。

本工作得到香港中文大学Carol Y. Cheung、新加坡国家眼科中心Gavin Tan Siew Wei、Yih-Chung Tham和Ching-Yu Cheng等教授及其团队的指导和支持，此外，来自中国医学科学院北京协和医学院、首都医科大学、华中科技大学、上海科技大学、中山大学、香港科技大学，印度Shri Bhagwan Mahavir玻璃体视网膜中心等单位的多学科专家给予了帮助。该研究得到科技部国家重点研发计划、国家自然科学基金、上海市科委“一带一路”国际联合实验室建设项目、上海市内分泌代谢疾病研究中心（重中之重项目）及上海交通大学“交大之星”计划医工交叉研究基金等资助。

**来源：文汇APP**

## 相关阅读

- [子宫内膜薄能否怀孕呢](https://github.com/aatdlcl043/kids-nutrition-notes/blob/main/20260915ibqr/iyvmmvzcrq.md)
- [孕妇肚皮两边痒怎么办](https://github.com/w15ezo8wwd/mommy-care-diary/blob/main/20260915xqek/naswuolxhx.md)
- [在绍兴做一次第二代试管婴儿需要多长时间！绍兴市妇幼保健院做试管婴儿怎么样！](https://github.com/e1ljyri8rs/parenting-daily-tips/blob/main/20260910evkn/jydklvuswn.md)
- [气温骤降~这几味中药助你护脾胃、防风寒](https://github.com/nih9jzz6yi/child-care-essays/blob/main/20260916qnvg/atakejvlel.md)
- [细数能导致胎儿畸形的药物](https://github.com/mxtw9dwa7v/baby-sleep-tips/blob/main/20260915vghj/twigigkcwx.md)
- [绿豆不能和10种食物一起吃 喝绿豆汤的五大禁忌](https://github.com/jg9otl86or/child-care-essays/blob/main/20260915kgwe/yljagehdau.md)
- [荣格：你逃避的，正是你需要看见的](https://github.com/l0mxvbb0j0/mommy-baby-notes/blob/main/20260916metj/vqodjzffdh.md)
- [40岁生二胎没有孕前检查怎么办](https://github.com/cwz1rtzls4/child-care-essays/blob/main/20260915zppv/fqmgairoxz.md)
- [事关宝宝接种疫苗，江西疾控发布重要提醒！](https://github.com/whprpfn9bc/child-care-essays/blob/main/20260916gsgz/qhltvjzbyc.md)
- [俄罗斯试管婴儿三代试管医院可以成功吗(俄罗斯试管婴儿生出来健康吗)](https://github.com/h3qlethz3l/baby-care-journal/blob/main/20260910bjle/bcquboitds.md)
- [孕妇隔着衣服晒太阳的方法-孕妇如何正确的晒太阳](https://github.com/o8mgbpui8y/mommy-baby-notes/blob/main/20260915wgkb/chhfgcgqrn.md)
- [走~去淄博！烧烤啤酒小龙虾，“痛风”套餐整一个？](https://github.com/nih9jzz6yi/parenting-daily-tips/blob/main/20260916kupp/bwuoxcrwdz.md)
- [株洲试管婴儿费用大揭秘：明细拆解+省钱攻略，一目了然！](https://github.com/na1l60kg9l/toddler-parenting-log/blob/main/20260911yyjm/wjbbtcaiwf.md)
- [移植成功率高的女性都有这些特点！](https://github.com/iebkyzpjrn/pregnancy-care-hub/blob/main/20260916cuva/fhvuwqudrv.md)
- [耳鼻喉医话 | 眩晕反复发作，为什么还需要看耳鼻喉科？](https://github.com/tp7gz3q4gt/mommy-baby-notes/blob/main/20260916pkfz/bbysmnrkhf.md)
- [【健康】这些症状竟是免疫力低下的表现！免疫力到底是个什么力？](https://github.com/km2vgbd5nt/kids-health-guide/blob/main/20260916qryf/ledyjptpbb.md)
- [剖腹产后有疤痕憩室怎么治疗](https://github.com/v89wdpmc44/mom-baby-stories/blob/main/20260915pzju/sgywbkkukb.md)
- [太淘气！说滴竟然全是实话！](https://github.com/j593cre19a/child-care-essays/blob/main/20260916knhs/ckidxdmlgd.md)
- [【医生来了】节目预告：本周关注“端午养生”&“自我急救技能”](https://github.com/e1ljyri8rs/family-health-notes/blob/main/20260916riqq/eauqultvpa.md)
- [医院妇幼健康十佳卫士：聂小成——一名自讨“苦”吃的“憨”医生](https://github.com/l0mxvbb0j0/mommy-baby-notes/blob/main/20260916wuhs/twsucaewkf.md)
- [警惕心梗年轻化 守住生命防线](https://github.com/vjd2jnnrxj/baby-food-notes/blob/main/20260916uglb/iymdwavbsf.md)
- [【召集令】爱在妇幼，健康成长——欢迎参加市妇幼保健院“六一”儿童节活动](https://github.com/t57i648hhi/child-growth-notes/blob/main/20260911dcju/bzuxhojhvp.md)
- [二胎剖腹产之后多久可以生三胎,剖腹产三胎多久可以同房](https://github.com/znp78by4gt/pregnancy-diary-hub/blob/main/20260911gzwh/lmizpoprlw.md)
- [上海试管保险推荐机构名单一览表](https://github.com/olvqsk2upx/pregnancy-care-hub/blob/main/20260910poru/qduthsmlah.md)
- [少精弱精做人授还是试管好？女方情况是重要衡量标准](https://github.com/w4nejibsgs/mommy-baby-notes/blob/main/20260915twkm/nkskrzqgjz.md)
- [儿童髋关节脱位矫正支具](https://github.com/t57i648hhi/child-growth-notes/blob/main/20260915kass/ekalqdvsfk.md)
- [辽宁省计划生育科学研究院 高频电刀采购公告](https://github.com/ij0s3j0vss/family-health-notes/blob/main/20260916jiay/wjsimkhobh.md)
- [我想做试管婴儿生个男宝费用大概要多少钱(做试管婴儿三代试管的几率大吗)](https://github.com/iebkyzpjrn/baby-care-journal/blob/main/20260910eulh/varlwsgyxl.md)
- [女性激素六项检查多少钱?需要做什么准备?](https://github.com/t4im9r1jji/newborn-care-tips/blob/main/20260911xnkv/svzyqcrddh.md)
- [胎儿大小与孕周对照表](https://github.com/sa1ec5y0bz/pregnancy-care-hub/blob/main/20260915gnbd/cghdsbrbbr.md)
- [生化妊娠最明显症状](https://github.com/syevx32qjy/pregnancy-care-hub/blob/main/20260915ftfd/qdozdbjhwl.md)
- [陕西医保政策八月启航，九月无忧报销！](https://github.com/uyv65mt699/toddler-parenting-log/blob/main/20260916rdnh/olxvmyoabh.md)
- [成都做第三代试管婴儿要花多少钱！是一次交清吗？](https://github.com/a66uv6rprt/pregnancy-care-essays/blob/main/20260911dvtx/xoabmkpnmk.md)
- [三九贴敷，呵护冬夏健康](https://github.com/cwz1rtzls4/mommy-baby-notes/blob/main/20260916twpg/qegoretuyl.md)
- [生死抢救︱众志成城，多学科救治保母婴安全](https://github.com/hhd0wt4kzq/parenting-daily-tips/blob/main/20260916cnig/ywtepdfljd.md)
- [【睡眠管理】老年人失眠有什么特点？](https://github.com/bjpnmb0r46/child-care-diary/blob/main/20260916fnqn/kjgrmvkajo.md)
- [hpv阳性如何治疗](https://github.com/uyv65mt699/parenting-faq-hub/blob/main/20260915azdj/rmpnauitsx.md)
- [中医外治双法宝 | 耳穴压豆+穴位贴敷，守护健康&备孕更轻松](https://github.com/nih9jzz6yi/baby-care-journal/blob/main/20260916gwhu/tzoxcjdawu.md)
- [注射用甲泼尼龙琥珀酸钠作用](https://github.com/na1l60kg9l/toddler-parenting-log/blob/main/20260915gzse/tdokfaqjci.md)
- [男性难育什么是前列腺炎症？可以试管婴儿吗？](https://github.com/wgeyt0fbiv/baby-feeding-guide/blob/main/20260911yqza/ltkbnjhgva.md)

## 推荐站点

- [['https://www.bubustuff.com/22.html', '赣南医学院第一附属医院试管流程详解：赣州本地首选']](https://www.bubustuff.com/22.html)
- [专业供卵网&为什么备孕黑豆吃六天（小黑豆）](https://www.3899234.com/20250927-117.html)
- [促排比试管供卵地址安全，促排成功率高还是试管供卵地址成功率高？](https://www.syldezdhkj.cn/26567889157089.html)
- [['https://www.xcktgpm.cn/20250823-174.html', '乐宝得与果纳芬促排效果差异及试管助孕医院选择指南']](https://www.xcktgpm.cn/20250823-174.html)
- [['https://www.liangzimayi.com/108.html', '天门三代试管包男孩费用公开，价格透明无套路']](https://www.liangzimayi.com/108.html)
- [代生价格-子宫后位的最佳受孕姿势](https://www.dyokx.com/hangzhoudaihuaishiguan/458.html)
- [着床不稳的征兆](https://www.hs52.cc/sandaigongluandaihuai/75.html)
- [柳州三代试管医生精选：优选专家指南](https://www.vhpowpj.cn/20250821-168.html)
- [【全面解析】山东省立医院生殖医学科怎么样？第三代试管婴儿技术实力与就医指南](https://www.cndcxc.com/daiyunliucheng/20260902/16752.html)
- [['https://www.dzjiurunxcl.cn/15733929442900.html', '招远市试管婴儿成功率解析与优势']](https://www.dzjiurunxcl.cn/15733929442900.html)
- [包代生孩子-大连做试管婴儿哪家医院好？附试管婴儿费用明细！](https://www.sandwnot.com/221602724520.html)
- [详解杭州富阳区妇幼保健院供精人工授精费用及流程](https://www.cddyunw.com/419091239476.html)
- [济南三代助孕,济南省立医院试管婴儿主治医师好不好？详细花费明细！](https://www.sdxxy.cn/20250518-459.html)
- [南昌做试管婴儿流程需要多久？](https://www.hghbjm.com/89.html)
- [['https://www.wahuobao.com/110.html', '仙桃三代试管婴儿费用指南：深入了解代生套餐与供卵费用']](https://www.wahuobao.com/110.html)
- [['https://www.szgwzx.cn/171.html', '代孕准备事项与供卵试管费用解析及单身女性允许国家指南']](https://www.szgwzx.cn/171.html)
- [做试管怀孕后流产原因，做试管怀孕后流产原因是什么](https://www.jszgyh.com/302414660578.html)
- [专业代生子：3cb囊胚的质量差？移植3cb囊胚的成功率高不高？](https://www.cd-hssf.com/123690564297.html)
- [深圳供卵试管婴儿有包成功的吗](https://www.uueamru.cn/20250409-136.html)
- [试管代孕花费, 3bb囊胚移植成功关键是子宫内膜厚度控制在8-12mm吗？](https://www.bkudgf.cn/173.html)
- [2026年山东代孕风险警示与安全助孕选择指南](https://www.sdshunhezb.cn/310294377172.html)
- [【2026攻略】郑州大学第一附属医院供卵试管怎么做？挂号流程与等待时间详解](https://www.wqxmm.cn/107805903228.html)
- [HCG上升孕酮值下降怎么办](https://hangzhou.ccxwlkx.cn/395.html)
- [代怀孕网具体位置,代怀帮忙怀孩子,人工授精卵泡多大可以做试管 人工授精的卵泡多大就可以做了](https://www.anyhdlyb.cn/2571616301381.html)
- [['https://www.xczxcy.com/21.html', '北京神化代怀生殖商行靠谱吗？警惕试管包成功骗局']](https://www.xczxcy.com/21.html)
- [二胎备孕指南：2026年试管婴儿费用揭秘](https://www.monpun.com/1303200231489.html)
- [代生儿子电话:2026试管婴儿报销新政策，这个城市部分费用已进医保！](https://www.dygsdyw.com/221620323079.html)
- [高龄代怀生子:试管移植后怎么排除宫外孕_移植后怎样睡觉姿势不会宫外孕](https://www.mymydz.cn/119104914116.html)
- [揭秘：藏族同性伴侣如何通过辅助生殖技术实现为人父的梦想](https://www.szanguangkeji.cn/tongxingshiguanzhuyun/64.html)
- [成都试管助孕全攻略：详细解析助孕流程及常见问题](https://www.sasksjob.com/519663162385.html)
- [试管精子质量提高？试管怎样提高精子质量？](https://www.sgdaiyun.com/123605232017.html)
- [第三代试管婴儿PGT技术与性别选择的法律解读](https://www.apkbwvg.cn/danshenqiuzi/170.html)
- [什么体质容易怀龙凤胎（高龄女性怀孕）](https://www.cecigou.cn/daihuaiyunfuwu/20250928/15011.html)
- [解读已婚女性梦境：菩萨预示幸福与好运，或与胎梦相关](https://www.gaodunxinkj.cn/20250826-174.html)
- [借卵试管代怀：二甲双胍与空卵泡的调理及子宫穿孔风险](https://www.weywjei.cn/20250826-178.html)
- [深圳试管婴儿成功率最高吗？](https://www.gyzhixiao.cn/495.html)
- [易孕宫外孕试管多少钱一次 宫外孕患者做试管效果好吗](https://www.dyqlsu.com/20240906-29.html)
- [代孕公司有那些&42岁试管代孕成功案例, 如何从心肺功能检查判断小](https://www.dymgp.com/7990.html)
- [石家庄代生求子&孕宝代孕包儿子,石家庄市试管比较好的医院都有哪些？石家庄做试管婴儿最好的医院？](https://www.afa2019.com/200943309354.html)
- [昆明做靠谱供卵代生哪里最好(昆明哪里做靠谱供卵代生成功率高)](https://www.ppmaas.com/xuanxingbietaocan/437.html)
- [揭秘武汉协和医院试管移植：盲移与B超引导的差异](https://www.satghenga.cn/218390054041.html)
- [供卵需要的钱很多吗（做供卵需要多少钱）](https://www.phetpalace.com/262.html)
- [多囊卵巢综合征自己怎样调理](https://www.luruihang.com/2289.html)
- [河南借卵生男孩包成功费用详情，2026河南正规民营借卵机构排名 ,哪家医院提供正规代孕](https://www.bjwdzxkj.cn/2239169439834.html)
- [有供卵代孕公司吗-国内供卵公司电话, 去医院做试管婴儿咨询需要夫](https://www.jmxmintuhg.cn/20250518-172.html)
- [绝经后做代生宝宝服务成功率多少](https://www.sjb493.cn/32000333131272.html)
- [26岁女孩三促（促排流程） 不懂就问,代孕公司名称](https://www.dgshengxigongchengsl.cn/2883193204197.html)
- [合肥试管供卵流程, 合肥安医大一附院精子库自精保存怎么收费？](https://www.fmngst.com/1827237654261.html)
- [2026年泰国最好的三代佛山代生试管婴儿医院准备费用十万够吗(泰国三代佛山代生试管婴儿医院排名)](https://www.xmxinyhwzhs.cn/29851615523879.html)
- [['https://www.lianhuahushengqun.cn/215145445558.html', '天津三代试管代孕机构,天津做试管婴儿报销政策详解,解答您的后顾之忧']](https://www.lianhuahushengqun.cn/215145445558.html)
- [['https://www.airpoolmall.com/10.html', '30岁卵巢早衰怎么生孩子？供卵试管成功案例分享']](https://www.airpoolmall.com/10.html)
- [扬州三代试管条件正规医院联系方式,供卵代怀包成功](https://www.cmanrxrr.cn/1848427591374.html)
- [['https://www.hongyuhuagong.cn/35498083653913.html', '上海2026年优质生殖医院推荐与供卵代生费用解析']](https://www.hongyuhuagong.cn/35498083653913.html)
- [2026福州供卵的私立机构汇总，附供卵三代生男孩详细步骤](https://www.tjsjyongsheng.cn/210254439405.html)
- [上海九院试管花费明细：关于匡延平团队微刺激方案的性价比分析](https://www.njxxwcr.cn/shiguandaishenggongluan/173.html)
- [代孕包成功总费用与肾移植指南](https://www.chengyanghg.cn/320.html)
- [科学拦截异常基因：广州平衡易位试管案例，三代试管显神威](https://www.sdhuabenhuanbao.cn/shiduzhaorendaihuai/166.html)
- [高龄女性促排要注意什么](https://www.hg00fj88.com/2150.html)
- [浙江助孕有多少钱捐卵女孩子渠道知名代生价格表](https://www.bjjinyukechuangzdh.cn/202.html)
- [上海优质助孕机构推荐与试管前身体调理饮食指南](https://www.hbhuihaohb.cn/160.html)
- [代怀孕网费用](https://www.zhangruiqing.cn/112470743212.html)
- [南京辅助生育成功经验分享：一位40岁高龄准妈妈的真实助孕历程](https://www.huaiyunq.cn/214462229437.html)
- [江门机构医院供卵费用高吗？江门侨乡助孕收费标准分析](https://www.chengdusokh.cn/300202444168.html)
- [试管代孕前刮宫真不是人人做！多久可以促排还要看标准](https://www.vecsi.cn/shanxizhuyun/2732.html)
- [['https://www.btwtjx.cn/wuhangongluanshiguanzhongxin/20251014/6067.html', '孕酮低吃什么补得快？这六类食物的最好的选择']](https://www.btwtjx.cn/wuhangongluanshiguanzhongxin/20251014/6067.html)
- [秋季做台湾试管婴儿的成功率会更高吗？](https://www.haojiezhishi.cn/113.html)
- [['https://www.rongyixueyuan.com/102.html', '广州中山三院试管助孕成功率揭秘：详解三代试管费用与流程']](https://www.rongyixueyuan.com/102.html)
- [卵巢早衰合适做试管吗(卵巢早衰合适做试管吗多少钱)](https://www.mimi567.com/437.html)
- [取2个卵泡成功案例](https://www.bjfhyly.com/454.html)
- [北京卵巢amh低能恢复吗？amh低如何调理？](https://www.ewdboe.cn/227345796406.html)
- [特殊病例：感染过梅毒治愈后，通过三代试管能生出百分百健康的娃吗？](https://www.hflrwzhs.cn/167.html)
- [['https://www.cxit.com.cn/daiyunmama/14205.html', '泰国第三代试管_试管供卵合法,试管指南：做试管婴儿一次成功的机会大吗？']](https://www.cxit.com.cn/daiyunmama/14205.html)
- [代怀成功率最高&正规便宜包代怀生,琼海市中医院做一代试管婴儿助孕要准备多少钱](https://www.zrbbavaq.cn/27752445659151.html)
- [['https://www.zixigou.com/109.html', '弱精症怎么提升试管成功率？上海特定病症人群备孕案例分享']](https://www.zixigou.com/109.html)
- [上海有代孕成功的吗-哪里做代孕最专业,2026上海永远幸妇科医院试管婴儿明细表（附助孕成功率）](https://www.qumengru.com/128033703531.html)
- [孕妇能吃苦瓜炒鸡蛋吗_苦瓜_怀孕_怎么做](https://www.xnnpbhdz.cn/16826732032014.html)
- [代怀孕的价格:试管双胎胎停的症状(试管双胎停育一个征兆)](https://www.eduency.com/126631502123.html)
- [代生包儿子-试管知识：青岛三代试管婴儿多少钱.](https://www.skiguo.cn/20250927-320.html)
- [冻胚移植雌二醇越高越好，冻胚移植雌二醇多少能着床成功？](https://www.sdjiaxin.net/901.html)
- [['https://www.cheguangfu.cn/238.html', '世纪代孕官网,试管婴儿性别鉴定对胎儿有影响吗？']](https://www.cheguangfu.cn/238.html)
- [les试管婴儿的流程是怎样的？](https://www.qzmx56.com/461.html)

*本文整理自母婴健康资讯，仅供科普参考。*
