All The Leisures 1.0.6a · Eric Modified 修订版

适用环境：Minecraft Java 1.21.1 / NeoForge 21.1.241。
资源包格式：34。语言：简体中文（zh_cn）。

启用方法
1. 保持 ZIP 格式，将 ResourcePacksJustForATL-Modified.zip 放入当前实例的 resourcepacks 文件夹。
2. 在“选项 → 资源包”中启用本包，停用 ResourcePacksJustForATL.zip。
3. 将本包放在其他汉化包、模组默认资源的上方。资源包列表越靠上，覆盖优先级越高。
4. 在语言设置中选择“简体中文（中国）”。应用资源包后等待加载完成；已在游戏中时可按 F3+T 重载资源。

本包包含原资源包的自定义资源和针对本整合包版本核对的补充汉化。
它会覆盖同名语言键，因此加载顺序会影响最终显示。模组名、作者署名、音乐署名、代码标识和技术缩写按用途保留。

启用配置
资源包 ZIP 内无法修改实例的 options.txt，也不能使自身自动启用。
本次按“只修改 Modified”的要求，没有改动整合包目录中的 options.txt。
原导出配置仍引用 ResourcePacksJustForATL.zip，第一次使用修订版需按上述步骤切换。

若在游戏关闭时手工修改原导出配置，只需将 resourcePacks 列表中的
"file/ResourcePacksJustForATL.zip"
替换为
"file/ResourcePacksJustForATL-Modified.zip"
保留其他已启用资源包及其顺序；不要同时保留这两个条目。
针对原导出文件的完整替换行如下（已有不同配置时只替换上述文件名）：
resourcePacks:["serilum_mod_translations","vanilla","file/Minecraft-Mod-Language-Modpack-Converted-1.21.1.zip","fabric","mod_resources","moonlight:merged_pack","file/CreateStyle_of_RefinedStorage(with_ui).zip","file/ResourcePacksJustForATL-Modified.zip","mod/continuity:resourcepacks/default","mod/continuity:resourcepacks/glass_pane_culling_fix"]

修订内容
- 全面进行地道化与规范润色：
  - 清理繁体台译与直译（末地乐事全面消除'终界'、'歌莱'、'使者'、'蚌'，纠正'终珠莱茶'为'末影珍珠奶茶'、'无机化龙蛋'为'无法孵化的龙蛋'等）。
  - 纠正暮色森林木材与告示牌名（'天蓬木'→'苍穹木'、'采矿木'→'矿石木'、'时间木'→'时光木'、'变形木'→'变化木'，对齐原版告示牌语序）。
  - 统一葡园酒香深色樱桃木体系（根除'暗樱牌'、'暗樱舟'、'暗樱船装有箱子'等机翻，修正诡异白葡萄汁与群系名称）。
  - 纠正机械动力硬币商店及深海潜航机翻（'Interface'误译'正面'更正为'界面'、'Signs'误译更正为'告示牌'、'开具汇票'规范化、潜艇仪表'不吃压力'更正为'无水压'）。
  - 统一 Macaw 体系小径楼梯与基底命名（消除 52 处与方块割裂的楼梯名）、规范窗户系列与'双层厨房橱柜'。
  - 统一农夫乐事附属蔬果箱袋命名（对齐'箱装XX'/'袋装XX'规范）、豆腐工艺术语与锻造模板提示语序。
- 修复 9 条中文退回英文的覆盖和 3 处格式化参数错误。
- 修复半译、残留英文及缺失翻译，包括 Macaw + Oh The Biomes We've Gone 的 3894 个名称、家具、小径、FTB、Distant Horizons 等条目。
- 移除未安装模组的独立语言文件及无用兼容条目，合并公共标签，消除重复语言键。
- 修正资源包格式、优先级说明和启用方法。
- 保留原包贴图、模型、字体、音效等非语言资源。

验证范围
已检查 ZIP 完整性、JSON、重复键、格式化参数、结构标记及原资源保留情况。
尚未进行 Minecraft 游戏内实际显示测试。
此包只针对 All The Leisures 1.0.6a，后续升级模组时需重新核对语言键。

翻译来源与许可
除原包与当前模组版本自带汉化外，部分新增翻译参考了 CFPAOrg 的 Minecraft-Mod-Language-Package。
具体来源、修改说明和许可见 CREDITS-TRANSLATIONS.md 及 credits/ 目录。
