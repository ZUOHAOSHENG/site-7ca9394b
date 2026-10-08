# 李飞飞个人主页：内容与设计决定

## 定位与阅读路线
用户仅提供姓名「李飞飞」。按公开知名学者 Fei-Fei Li 定位，Stanford Profiles、Stanford HAI 与 ImageNet 团队页相互印证，论文署名包含 Li Fei-Fei / L. Fei-Fei。不声称用户就是本人，不添加官方授权声明。

她值得被记住的线索是：用 ImageNet 推动大规模视觉识别，将研究推进到视觉与语言、医疗环境智能，并倡导以人为本的 AI。目前的空间智能工作是这条脉络的延续。

采用连续叙述为主、论文索引为辅。首屏将姓名、教授身份、ImageNet 贡献、当前方向、真实肖像和资料入口聚合为完整人物介绍。下一段以「从识别物体，到理解世界」串起数据和视觉语义研究，Visual Genome 图 5 的区域标注帮助理解这一变化；并列介绍当前空间智能及 2026-07-27 政策简报，不为单条消息另设 News。然后切换到四篇跨阶段正式论文的稳定索引，最后呈现倒序任职、教育、少量荣誉及公开行政联系入口。无未核实的占位栏目。

## 成果选择
- ImageNet, CVPR 2009：标志性数据集工作；项目官网明确记录 2019 年回顾性影响力奖。与 ILSVRC 2015 不重复占据首页的有限精选名额。
- Deep Visual-Semantic Alignments, CVPR 2015：图像区域与自然语言对齐，展示从识别到描述的转变；不再列同题 2017 期刊版。
- Visual Genome, IJCV 2017：密集对象、属性与关系标注，把视觉与语言连接起来。
- Illuminating the dark spaces of healthcare with ambient intelligence, Nature 2020：明确为综述，体现视觉技术走向人类健康的方向。
完整成果入口指向 Stanford 公开论文列表。已尝试 Scholar，但超时，不展示引用数，也不把搜索摘要的引用统计写入页面。

## 视觉与素材决定
- 按用户本轮「配色不喜欢」调整为松绿、白与少量赭金：全宽松绿色顶栏（#176353）建立重心，链接和用途图标统一松绿；纯白底承载长文，研究区使用中性浅灰（#f4f6f5），联系区使用浅绿白（#eaf1ed）。少量赭金色标签（#89631e）区分当前方向与论文出处，导航选中线用浅金色。文字保持深灰，不改变字体、尺寸、内容、图片、区块顺序或布局；现有 CSS 变量名保留以避免扩大改动范围。
- 正文字体 Noto Sans SC 400/500/600；姓名与章节标题少量 Noto Serif SC 500。优先下载本页所需字符子集至 assets，系统中文字体作为回退。
- 无卡片式人物区。肖像约 300px 展示，保持完整头顶与肩部；首屏人物为主，研究图在后续工作叙述中出现。
- 肖像：Stanford HAI 人物页的公开实验室照片，944×944，清晰自然。原页 https://hai.stanford.edu/people/fei-fei-li ，图片 https://hai.stanford.edu/assets/images/2020-03/hai_1512feifei.png ，本地 assets/fei-fei-li-portrait.png。
- Visual Genome 图 3 场景图过密，放弃展示；改用正式论文图 5 的单幅图像与三条区域描述示例。原页 https://link.springer.com/article/10.1007/s11263-016-0981-7 ，图片 https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs11263-016-0981-7/MediaObjects/11263_2016_981_Fig5_HTML.jpg ，本地 assets/visual-genome-regions.jpg。桌面以 280px、手机以版心宽展示，可读到标注关系；图注说明原图来源，提供可打开的原图。
- 所有区块提供稳定 data-section-id、中文标题，文本、入口和图片提供 data-edit-id。390px 下单列，无额外框架依赖。

## 核实字段与来源（2026-10-08）
| 字段 | 采用值 | 原文来源 |
| --- | --- | --- |
| 姓名 | 李飞飞 / Fei-Fei Li；论文署名 Li Fei-Fei | 用户姓名；https://profiles.stanford.edu/fei-fei-li |
| 任职 | Stanford 计算机科学系 Sequoia 教授、HAI 创始主任 | https://hai.stanford.edu/people/fei-fei-li |
| 当前产业任职 | World Labs 联合创始人兼 CEO，空间智能与生成式 AI | https://profiles.stanford.edu/fei-fei-li |
| 研究 | 计算机视觉、深度学习、机器人学习、空间智能、医疗环境智能 | https://profiles.stanford.edu/fei-fei-li |
| ImageNet 贡献 | ImageNet 与 ImageNet Challenge 发起者；项目 PI | https://hai.stanford.edu/people/fei-fei-li ; https://www.image-net.org/about.php |
| Stanford 任职起点 | 2009 年加入 | https://hai.stanford.edu/people/fei-fei-li |
| SAIL | 2013–2018 年主任 | https://profiles.stanford.edu/fei-fei-li |
| Google 兼任 | 2017–2018，Google 副总裁、Google Cloud AI/ML 首席科学家 | https://profiles.stanford.edu/fei-fei-li |
| 较早任职 | Princeton 2007–2009；UIUC 2005–2006 | https://hai.stanford.edu/people/fei-fei-li |
| 学位 | Caltech 电气工程 PhD 2005、Master 2001；Princeton 物理 B.A. 1999 | https://profiles.stanford.edu/fei-fei-li |
| 荣誉 | 2025 QEPrize；2024 VinFuture；2020 NAE 与 NAM 当选 | https://profiles.stanford.edu/fei-fei-li |
| AI4ALL | 联合创始人及董事会主席，推动 AI 教育的包容与多元 | https://hai.stanford.edu/people/fei-fei-li |
| CV | 官方公开 PDF 入口 | https://cap.stanford.edu/profiles/viewCV?facultyId=15052&name=Fei-Fei_Li ，由 Stanford Profiles 链出 |
| 联系方式 | Harini Sreepathi，行政助理，harinis@stanford.edu；不冒充本人邮箱 | https://profiles.stanford.edu/fei-fei-li |
| 最新工作 | 2026-07-27，与同事共同发布世界模型与空间智能治理政策简报 | https://hai.stanford.edu/policy/the-world-model-and-spatial-intelligence-era-governing-ai-beyond-language |
| ImageNet 论文 | J. Deng, W. Dong, R. Socher, L.-J. Li, K. Li, L. Fei-Fei；CVPR 2009；题名 ImageNet: A Large-Scale Hierarchical Image Database | https://www.image-net.org/about.php ; https://www.image-net.org/static_files/papers/imagenet_cvpr09.pdf |
| 图文对齐论文 | Andrej Karpathy, Li Fei-Fei；CVPR 2015, 3128–3137；Deep Visual-Semantic Alignments for Generating Image Descriptions | https://openaccess.thecvf.com/content_cvpr_2015/html/Karpathy_Deep_Visual-Semantic_Alignments_2015_CVPR_paper.html |
| Visual Genome | R. Krishna, Y. Zhu, O. Groth, J. Johnson, K. Hata, J. Kravitz, S. Chen, Y. Kalantidis, L.-J. Li, D. A. Shamma, M. S. Bernstein, L. Fei-Fei；IJCV 123, 32–73 (2017) | https://profiles.stanford.edu/fei-fei-li ; https://link.springer.com/article/10.1007/s11263-016-0981-7 |
| 医疗综述 | Albert Haque, Arnold Milstein, Li Fei-Fei；Nature 585, 193–202 (2020)；Illuminating the dark spaces of healthcare with ambient intelligence | https://www.nature.com/articles/s41586-020-2669-y |

## 信息边界
HAI 与 Profiles 对主任表述不同，页首采用 HAI 当前页面的「创始主任」，不推断现任管理职责。教育只采用明确学位记录，省略有内部年份冲突的荣誉博士。未采用无法打开的书籍页面，不堆新闻奖项填充动态。近期检索先以姓名加 2026 宽泛查找，再以 HAI 官方政策页确认日期。人物身份、肖像授权、公开联系安排仍需用户在发布前集中确认。

## 实现与验收
字体通过 Google Fonts text 子集接口获取本页字符并本地保存，四个实际字重单独声明。图标来自 lucide-static 0.468.0（ISC 许可）。无外部运行时请求。已检查 1440px 整页、1920px 首屏与 390px 手机截图；依据截图增加手机任职与肖像图注间距，提高正文和论文元数据可读性，并加深低对比度辅助文字。导航锚点、邮件链接、论文外链均为真实目标。
