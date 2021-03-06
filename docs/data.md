# 资料添加/编辑教程

## 进入添加资料页面

要想进入添加资料的页面，有两种办法：

第一种是点击任意模组下 `MOD资料` 内的 `添加新资料` 按钮：

![new 1](https://cloud.githubusercontent.com/assets/5229241/12670160/27b12058-c6a1-11e5-89f2-235957d3a7d4.png)

第二种是到任意资料页面下点击 `添加资料` 按钮：

![new 2](https://cloud.githubusercontent.com/assets/5229241/12670252/c8d4744e-c6a1-11e5-8166-2a1f9e867770.png)

## 进入修改资料界面

先进入想要修改的资料，点击资料上方的 `编辑` 按钮：

![edit](https://cloud.githubusercontent.com/assets/5229241/12676654/da685d92-c6ce-11e5-91c0-b761871e5829.png)

## 资料类型

![type](https://cloud.githubusercontent.com/assets/5229241/12670291/1bd36f6a-c6a2-11e5-9b93-1c989d3ed2d9.png)

资料类型暂时一共有10种，分别为：

- **物品/方块**：例如石头、圆石、钻石等
- **生物群系**：即Biome，例如草原、森林、沼泽等
- **世界**：即维度(Dimension)，例如下界、末路之地、暮色森林等
- **生物**：即Mob(注意不是Entity，Entity内容会扩充很多比如雪球和点燃的TNT等)，Mob是有AI的，例如牛、爬行者、僵尸等
- **附魔**：即Enchantment，例如火焰保护、荆棘、时运等
- **BUFF/DEBUFF**：即状态效果(Status Effect)，例如急迫、速度、缓慢等
- **多方块结构**：由玩家搭建的多方块结构，搭建完成会形成一个整体工作，例如Thaumcraft 4中的炼狱熔炉、注魔台、荒古炼金炉等
- **自然生成**：在世界中自动生成的多方块结构，例如沙漠神殿、丛林神庙、地牢等
- **绑定热键**：即游戏的键位，例如跳跃、潜行、丢弃等
- **天气效果**：例如降雨、降雪、雷暴等

除了 `物品/方块` 类型外其它类型的资料均只有 `基本信息` 和 `官方信息` 两项。注意切换类型的时候部分资料会被清空。

## 基本信息

以下内容中 `[资料]` 代表所选类型名称，例如选中 `世界` 类型时，名称为 `世界名称`。

- **编辑器**：这里为资料的简介，请在这里描述资料的详细用途及数据。注意描述不要过于简单，一般情况下最好不要低于30个字。具体使用方法请查看[编辑器使用教程与准则](http://help.qwq.fun/1835006)。点击 `提交添加` 边上的 `预览内容` 可以预览编辑的结果。
- **[资料]名称**：这里一般为资料的中文译名，但在无译名或译名不通用的情况下可以直接填写资料的原名。此项为必填项。
- **[资料]原名**：这里为资料的原名，一般为英文。在资料名称已填写原名的情况下这一项可以空着不填。此项为选填项，但除了资料名称填写的是原名的情况以外，请务必认真填写，否则会对某些玩家产生误导。另外请注意原名一定要是原游戏中**显示**的名字，即大小写等格式要与游戏中一致。
- **[资料]引用**：该项用于引用其他资料内容，避免重复复制粘贴。框内填写资料ID，点击可开启搜索框，搜索框中输入资料名称，选择所需项即可。引用内容以浅色边框形式置于资料底部，合成表顶部。
- **[资料]封面**：此项仅在除 `物品/方块` 以外的类型中出现。这里填的是资料封面的地址，**请尽量使用百科站内地址**。封面分辨率为240x150，如果分辨率不对的话百科会自动进行拉伸。封面上传方式见下面的Note。生物的封面可以使用[ItemRender](https://www.mcmod.cn/class/175.html)进行导出，但是图片需要自己裁剪以符合分辨率，详细请见[ItemRender使用教程](http://help.qwq.fun/1835012)。此项为选填项，但为了资料的完善最好添加一下。
- **物品/方块分类**：此项仅在 `物品/方块` 类型下出现。在这里请根据资料的功能/状态/主题等进行分类，默认为未分类状态。如果已有分类无法满足条件需要新建分类，请滑动到最下方选择自定义，并在右方的方框中填写新的分类。在新建分类前请先检查当前资料是否能归属到已有分类当中。如果Mod中有对资料进行分类(创造面板或子Mod等),请按照Mod中的相应分类添加。

## 拓展信息

此项仅在 `物品/方块` 类型下出现。

- **矿物词典**：如果该物品支持Forge Oredict，请搜索并选择相应的矿物词典项。注意目前百科的矿物词典项并不完善，目前只能选择少数的几个矿物词典项，所以如果没有搜索到请空着或找编辑员添加。目前只有编辑员能够添加与修改矿物词典条目，所以如果想要添加矿物词典请联系编辑员。此项为选填项。
- **最大耐久**：此项为物品的最大耐久度，例如钻石剑为1562。该项可以用ItemRender导出之后查看导出json中物品的对应 `maxDurability` 项，具体请看[ItemRender使用教程](http://help.qwq.fun/1835012)。如果没有最大耐久可以留空，此项为选填项。
- **最大叠加**：该项为物品的最大叠加数，即一个格子内最多能放的物品数，例如石头为64，钻石剑为1。该项可以用ItemRender导出之后查看导出json中物品的对应 `maxStackSize` 项，具体请看[ItemRender使用教程](http://help.qwq.fun/1835012)。该项为选填项。
- **完整采集**：该项为最低能够完整采集物品而不会将其破坏掉的工具的ID。例如煤矿为木镐，铁矿为石镐。注意这里要填的不是工具名称而是ID，ID可在网址中找到，比如石头的网址为 `http://www.mcmod.cn/item/8.html`，那么石头的ID就为8。当然，此项自带了搜索框，你可以在搜索框中搜索资料的名称。在输入框右边有一个常用工具ID，在里面可以选择一些常用工具的ID从而加快效率。此项为选填项，如果没有特殊的工具要求请留空。
- **图标**：图标分为大图标和小图标，大图标为128x128，小图标为32x32。图标可用ItemRender导出，具体请看[ItemRender使用教程](http://help.qwq.fun/1835012)。非必填项。上传方式有两种：
	- 第一种方式为文件上传，步骤为 `选择文件` -> `打开`。如果使用ItemRender导出的话，小图标带 `_grid` 后缀，大图标无后缀。
	- 第二种方法为Base64码上传，步骤为 `显示base64` -> 粘贴Base64码。Base64码可使用ItemRender导出json之后在相应json文件内找到对应物品的 `smallIcon` 和 `largeIcon` 项。
	- 如果两个都传了，优先显示Base64的图标。因此如果出现上传图片但图标未更改，请优先检查base64码是否已清除。

## 官方信息

- **首次出现**：该资料首次出现时的MOD版本，如果没有找到相应的版本可以点击右边的 `添加MOD更新日志` 按钮添加新的日志，添加日志请看[日志添加/编辑教程](http://help.qwq.fun/1835009)。切勿无考据乱填。

## 仅编辑员

此项仅在 `物品/方块` 类型下出现，并且只有编辑员才能看到。

- **合并物品/方块**：这里填写合并**至**物品的ID，ID可在网址中找到，比如石头的网址为 `https://www.mcmod.cn/item/8.html`，那么石头的ID就为8。当然，此项自带了搜索框，你可以在搜索框中搜索资料的名称。如果当前资料与另外一个资料功能相近，这两个资料合并后将在合并**至**物品的页面中显示两个物品的介绍，在**被**合并物品页面中会显示合并**至**物品的链接。比如粉碎铜矿石可以合并至铜矿石，效果见[铜矿石](https://www.mcmod.cn/item/78.html)
- **另外版本(已移除)**：这里填写另外版本物品的ID，ID可在网址中找到，比如石头的网址为 `https://www.mcmod.cn/item/8.html`，那么石头的ID就为8。当然，此项自带了搜索框，你可以在搜索框中搜索资料的名称。如果资料为其它资料的另外一个版本(比如铀单元是单铀棒的另外版本)，填写另外版本之后会在**填写的资料**(不是正在编辑的资料)页面显示当前物品的资料。
