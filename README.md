# Hearts of Iron IV - Hatsune Miku Custom Focus Tree Mod
# 《钢铁雄心4》初音未来主题通用国策树模组

[![HOI4 Version](https://img.shields.io/badge/HOI4-v1.18.2-blue.svg)](https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/)
[![Mod Version](https://img.shields.io/badge/version-v1.6.0-green.svg)](#)
[![Steam Workshop](https://img.shields.io/badge/Steam-Workshop-red.svg?logo=steam)](https://steamcommunity.com/sharedfiles/filedetails/?id=3707210439)

这是一个为《钢铁雄心4》（Hearts of Iron IV）设计的高自由度、全国家通用的**初音未来（Hatsune Miku）**主题国策模组。

---

## 🌟 核心特色 (Key Features)

### 1. 全国家通用（无国家 TAG 限制）
* **动态替换机制**：本模组没有固定的国家限制。进入游戏后，**任意国家**均可通过点击专属的决议（Decision），动态将本国原有的国策树替换为精心设计的初音未来主题国策树。
* 无论你选择大国还是小国，都能体验到这套完整的工业与政治升级路线。

### 2. 专属定制国策树 (Focus Tree)
国策树包含四大核心板块，提供了极高的成长感和可玩性：
* **政治路线 (Political Branch)**：拥有四条互斥的政治主线——中立主义（Despotism）、民主主义（Conservatism）、法西斯主义（Nazism）以及共产主义（Marxism）。在后期阶段，根据所选路线提供征服宣战、阵营动态修正或长效五年计划加成。
* **工业路线 (Industrial Branch)**：从初期的生产惩罚逐步过渡到后期的基建爆发，提供额外的科研槽解锁（最高可达 5~6 个科研槽）和丰厚的国家资源开发。
* **军事路线 (Military Branch)**：涵盖陆、海、空三军技术蓝图。通过完成前置测试国策，可依次升级 `mikufans` 系列强力陆海空国家精神。

### 3. 官方标准角色系统 (Modern Character System)
本 Mod 已完全重构并适配《钢铁雄心4》官方推荐的**统一角色系统（Character System）**，杜绝了旧版动态创建指令导致的运行冲突：
* **多重定位**：初音未来（Miku）同时具备国家领袖、陆军将军/元帅、政治顾问、军事理论家四重身份。
* **UI 深度优化**：内阁顾问与军事参谋头像均已适配 **156x210** 标准物理分辨率，经过精准的缩放与微调，完美契合原版游戏内阁 UI，无任何拉伸或溢出问题。

### 4. 专属领袖特质 (Custom Leader Traits)
* 🎤 **政治顾问特质《世界第一的歌姬》 (`miku_political_trait`)**：
  提供 +15% 每日政治点获取、+10% 国家稳定度、-5% 消费品民用工厂需求，以及民用工厂、军用工厂、基础设施建造速度各 +10% 的全方位工业与建设支持。
* 🎵 **军事理论家特质《电子歌姬的协奏》 (`miku_military_trait`)**：
  降低陆、海、空三军学说研发成本各 10%，并提升三军学说精通度（Mastery）获取速度与每日经验加成各 15%。

---

## 🛠 运行与安装说明 (Running & Installation)

### 推荐运行环境
* **游戏本体版本**：`v1.18.2` 兼容。
* **推荐 DLC**：支持全 DLC 运行。建议开启《绝不退让（No Step Back）》及后续相关 DLC，以获得完整的军官团、学说精通度与角色系统加成。

### 创意工坊订阅
你可以直接在 Steam 创意工坊订阅本 Mod 体验最新内容：  
🔗 [初音未来专属通用国策树 - Steam 创意工坊链接](https://steamcommunity.com/sharedfiles/filedetails/?id=3707210439)

### 本地手动安装（开发者/手动安装玩家）
1. 下载本项目的所有代码及资源文件。
2. 将文件解压到您的本地 Mod 路径中（通常位于 `C:\Users\您的用户名\Documents\Paradox Interactive\Hearts of Iron IV\mod`）。
3. 确保 `.mod` 文件中的 `path` 路径指向您解压后的文件夹路径。
4. 在 Paradox 游戏启动器中激活本 Mod 即可。

---

## 📈 版本历史 (Changelog)

### v1.6.0 (当前更新)
* **[重构]** 废弃了旧版 `create_corps_commander` 与 `create_country_leader` 动态创建指令，将 Miku 角色重构为统一角色文件（Character files）。
* **[新增]** 新增自定义政治顾问特质 `miku_political_trait`，全面替代原版 `captain_of_industry`。
* **[新增]** 新增自定义军事理论家特质 `miku_military_trait`，提供三军学说成本降低、精通度获取速度加成及三军每日经验加成。
* **[修复]** 修复了内阁小头像在界面上由于分辨率不适配（使用了非标准的正方形）导致拉伸变形、比常规内阁大一圈的视觉 Bug。通过调整物理分辨率为 **156x210**，辅以精细的局部特写裁剪，使其与原版内阁视觉高度统一。

### v1.0.0 ~ v1.5.0
* 搭建国策树基础框架，加入基础工业、政治、军事加成，添加 Miku 基础头像资源及对应的国家精神。

---

## 🔮 未来计划 (Future Plans)
* 计划在后续版本更新中引入更多深度互动内容（如专属决议面板、世界巡演互动事件等），敬请期待。
