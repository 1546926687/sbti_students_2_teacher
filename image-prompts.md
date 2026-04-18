# TBTI 导师人格 · 图像生成提示词

> 仿 SBTI 网站视觉风格，23 张方形海报，统一画风，放到 `/image/` 目录。
> 推荐模型：Midjourney v6 / Flux / 即梦 / 豆包 / Nano Banana / GPT-4o Image。

---

## 一、全局风格锚（每次生成时拼在前面）

**中文版**：
```
扁平卡通风格肖像，粗黑描边，色彩饱和度高，背景为单色或简单渐变，
构图居中半身/头部特写，正方形 1:1 画幅，类 SBTI 人格测试插画风，
有一点点表情包/梗图的幽默感，面部表情夸张、情绪强烈，
角色设定为大学导师/教授，通常穿休闲衬衫或毛衣，偶有眼镜。
禁止写实照片，禁止 3D 渲染，禁止恐怖元素。
```

**English**:
```
Flat cartoon portrait illustration, thick black outlines, highly saturated colors,
solid or simple gradient background, centered composition, bust/head close-up,
1:1 square aspect ratio, style similar to MBTI-parody character posters,
slight meme humor, exaggerated facial expressions, strong emotion,
character is a university professor/advisor, usually wearing casual shirt or sweater,
optional glasses. No photorealism, no 3D render, no horror elements.
```

**统一参数建议**：
- Midjourney：`--ar 1:1 --style raw --stylize 250`
- Flux / SDXL：`1024x1024, illustration, bold line art, cel-shaded`
- 负面词：`photo, realistic, 3d, blurry, horror, dark, nsfw, text, watermark`

---

## 二、23 张逐一提示词

### 1. GOD 学术菩萨
**标语**：你发不发论文都行，健康就好。
**Prompt**：
一位慈眉善目的中年男教授，光头或稀疏头发，半闭着眼睛微笑，双手合十于胸前，身披淡黄色僧袍式毛衣，身后有淡金色佛光光圈，背景浅米黄纯色。表情极度安详慈悲。

> A benevolent middle-aged bald professor with half-closed eyes and a serene smile, hands pressed together at chest, wearing a yellowish monk-like sweater, soft golden halo behind his head, pale beige background. Extremely peaceful expression.

---

### 2. CTRL+ 微操狂魔
**标语**：这个逗号，我建议改成分号。
**Prompt**：
一位瘦削中年男教授，戴金丝细框眼镜，眉头紧锁，右手食指夸张地指着一份被红笔密密麻麻批改的 A4 纸，纸上全是圈圈和箭头。西装衬衫扣到最上面一颗。背景为冷蓝灰色。

> A thin middle-aged professor with gold-rimmed glasses, frowning intensely, dramatically pointing his index finger at an A4 paper covered in red-pen corrections, circles and arrows everywhere. Shirt buttoned to the top. Cool blue-gray background.

---

### 3. GHOST 失联导师
**标语**：老师？老师在吗？……
**Prompt**：
一位半透明的教授虚影，身体呈幽灵状态，几乎要消失，表情茫然。背景是空无一人的办公室，办公椅空着，桌上堆满未读邮件。整体色调偏冷青灰，幽灵边缘有淡淡白光。

> A semi-transparent ghostly professor, body fading like a phantom, blank expression. Background is an empty office, empty chair, desk piled with unread mail. Cold cyan-gray tone, faint white glow around the ghost's edge.

---

### 4. KPI-R 指标机器
**标语**：下个月交不出数据，自己看着办。
**Prompt**：
一位机械化的教授，半边脸是人半边脸是金属齿轮机械结构，眼睛是发光的红色数字屏，正在吐出一条写满指标的纸带。背景是工业风蓝灰色，飘着「IF=15」「一作」「Q1」等字样。

> A mechanical-hybrid professor, half human face half metal gears and circuits, glowing red digital display eyes, spitting out a ticker tape of KPI numbers. Industrial blue-gray background with floating text like "IF=15", "first author", "Q1".

---

### 5. PUA-R 精神污染源
**标语**：你是我带过最差的一届。
**Prompt**：
一位阴郁的中年男教授，嘴角下撇，眼神冷漠略带讥讽，手指戳向画面前方（观众），身后弥漫着深紫色烟雾，烟雾中隐约浮现扭曲的文字「废物」「不行」。深紫黑背景。

> A gloomy middle-aged male professor with downturned mouth, cold mocking eyes, finger jabbing toward the viewer. Dark purple smoke swirls behind him with faintly visible distorted words "trash" "failure". Deep purple-black background.

---

### 6. DAD 学术慈父
**标语**：钱不够花跟我说。
**Prompt**：
一位和蔼的中年男教授，微胖，笑容温暖，穿着浅蓝色针织开衫，正从钱包里抽出几张钞票递出来，动作自然。背景为温暖的橙黄色，旁边有一杯热茶。

> A kind-faced chubby middle-aged professor, warm smile, wearing a light blue knit cardigan, pulling bills from his wallet and handing them out naturally. Warm orange-yellow background, a cup of hot tea beside him.

---

### 7. PIE-R 画饼大王
**标语**：跟我三年，保你进 top。
**Prompt**：
一位笑容灿烂、略带油腻的中年男教授，西装革履，双手夸张地比划，身前悬浮着一个巨大的金色大饼，饼上用卡通字体写着「MIT」「Nature」「教职」。背景是金光闪闪的渐变。

> A beaming, slightly oily middle-aged professor in a suit, gesturing dramatically with both hands. A giant golden pancake floats in front of him with cartoon text "MIT", "Nature", "Tenure". Glittering golden gradient background.

---

### 8. ZEN 佛系禅师
**标语**：一切随缘，顺其自然。
**Prompt**：
一位留着长白胡子的禅师风教授，穿宽松亚麻长袍，盘腿坐在蒲团上，端着一个冒着热气的茶杯，表情恬淡半眯着眼。背景是水墨风的淡绿色山水，一缕檀香烟缓缓升起。

> A Zen-style professor with a long white beard, wearing loose linen robes, sitting cross-legged on a cushion, holding a steaming tea cup, calm half-closed eyes. Ink-wash pale green mountain background with rising incense smoke.

---

### 9. KING 卷王领袖
**标语**：我 6 点到办公室，没看到你们。
**Prompt**：
一位精神抖擞的中年男教授，穿笔挺的西装，手里拎着公文包，眼神锐利如鹰，身后是还没亮透的清晨天空和办公楼，墙上的时钟指向 5:45。红色调整体偏冷，能量感极强。

> An energetic middle-aged professor in a crisp suit, holding a briefcase, eagle-sharp eyes, against a pre-dawn sky with an office building behind, wall clock showing 5:45. Cool red tones, intense energetic vibe.

---

### 10. STORM 情绪风暴
**标语**：上午夸你天才，下午骂你废物。
**Prompt**：
一位表情分裂的教授，画面从中间一分为二：左半边笑容灿烂阳光明媚；右半边怒目圆睁雷电交加。两边背景撞色（左边粉黄，右边深紫），中间有闪电分割线。

> A split-expression professor, image divided down the middle: left half beaming and sunny; right half furious with lightning. Contrasting backgrounds (left pink-yellow, right deep purple), lightning bolt dividing line.

---

### 11. BANK 资源大户
**标语**：经费管够，别心疼。
**Prompt**：
一位西装笔挺、气场强大的中年男教授，身后堆满成捆的现金、金条、文件袋，手里潇洒地挥着一张支票，表情自信从容。背景为深绿色带金色光斑，有种财富密码既视感。

> A confident middle-aged professor in a sharp suit, surrounded by stacks of cash, gold bars, file folders, casually waving a check, confident expression. Deep green background with golden light specks, wealthy vibe.

---

### 12. MIA 神隐大师
**标语**：出差半年，回来问课题做完了吗。
**Prompt**：
一位拖着行李箱的教授，手里拿着登机牌，正快步走向机场登机口，身上斜挎笔记本电脑包。背景是机场候机大厅，身影略带模糊动感。周围飘着各地标注：「北京」「纽约」「东京」。

> A professor pulling a suitcase, boarding pass in hand, striding toward an airport gate, laptop bag across his shoulder. Airport terminal background, figure slightly motion-blurred. City labels floating around: "Beijing", "NYC", "Tokyo".

---

### 13. SHOW 表演艺术家
**标语**：组会比春晚还精彩。
**Prompt**：
一位夸张地站在舞台聚光灯下的教授，一手拿麦克风一手指向天空，身后是巨大的华丽 PPT 投影屏，屏上图表花哨但内容空洞。背景是剧院红色帷幕，金色光束倾泻。

> A professor dramatically standing under a stage spotlight, microphone in one hand, other pointing skyward, huge flashy PPT slide projected behind him with fancy but empty charts. Theater red curtain background, golden spotlight beams.

---

### 14. CLAW 抢一作选手
**标语**：我指导了你，一作应该是我。
**Prompt**：
一位笑里藏刀的教授，伸出手准备从一个学生身影手中抽走一份写着「Paper · First Author」的论文。学生在画面角落一脸无奈。教授表情假笑，锐利的指甲像爪子。背景暗红色。

> A professor with a false smile, reaching to snatch a paper labeled "First Author" from a student's hand. Student stands in the corner looking helpless. Professor's fingernails sharpened like claws. Dark red background.

---

### 15. MOM 学术妈妈
**标语**：吃了吗？最近瘦了。
**Prompt**：
一位和蔼的中年女教授，围着小碎花围裙，双手端着一盘冒着热气的饺子递出来，笑容温柔慈爱。背景是温暖的厨房，柜子上摆着零食饮料。整体暖粉色调。

> A kind-faced middle-aged female professor wearing a floral apron, holding out a plate of steaming dumplings with a warm loving smile. Warm kitchen background with snacks and drinks on shelves. Warm pink tones overall.

---

### 16. POLI 政客型
**标语**：人情世故满分，科研指导 0 分。
**Prompt**：
一位八面玲珑的中年男教授，西装笔挺，正在与另一位模糊身影握手，面带完美社交笑容，胸前别满了各种头衔徽章和名牌。背景是会议厅红毯和条幅，中国风的金色雕花。

> A socially polished middle-aged male professor in a crisp suit, shaking hands with a blurred figure, wearing a perfect networking smile, multiple title badges pinned on his chest. Conference hall red carpet background with golden decorative patterns.

---

### 17. TIGER 老虎导师
**标语**：见面先骂，骂完请你吃饭。
**Prompt**：
一位有猛虎气质的中年男教授，半人半虎的拟人化造型，虎耳、虎纹点缀在脸颊，左手拍桌子一脸怒气，右手却端着一盘热腾腾的红烧肉。桌上同时摆着批评报告和饭菜。橙黑条纹背景。

> A tiger-spirit middle-aged male professor, anthropomorphic half-human-half-tiger design, tiger ears and stripes on cheeks, left hand slamming the table in anger, right hand offering a plate of braised pork. Critique report and meal both on table. Orange-black stripe background.

---

### 18. NERD 纯技术宅
**标语**：只会说代码，不会说人话。
**Prompt**：
一位瘦瘦的年轻教授，头发乱糟糟戴着厚黑框眼镜，穿格子衬衫，整个人被多个显示器包围，屏幕上全是代码和公式。他正盯着屏幕，对周围的世界毫无反应。蓝紫色赛博氛围背景。

> A skinny young professor with messy hair and thick black-framed glasses, wearing a plaid shirt, surrounded by multiple monitors filled with code and formulas. Staring blankly at screens, oblivious to the world. Blue-purple cyber ambient background.

---

### 19. VAMP 吸血鬼
**标语**：学生是燃料，我才是主角。
**Prompt**：
一位苍白优雅的教授，穿黑色高领毛衣，微微咧嘴露出一对尖牙，手里举着一管红色液体试管（标签写「学生」），表情享受。背景为暗红色哥特式图案，有蝙蝠剪影飘过。

> A pale elegant professor in a black turtleneck sweater, slightly parted lips revealing fangs, holding a red-liquid test tube labeled "student", savoring expression. Dark red gothic pattern background with bat silhouettes floating by.

---

### 20. SALT 咸鱼导师
**标语**：我已经躺了，你也来吧。
**Prompt**：
一位完全躺平的中年男教授，真的变成了一条拟人化的大咸鱼，穿着教授西装，瘫在办公椅上，嘴里咬着泡面，手里拿遥控器看电视。办公桌上堆着泡面盒和漫画书。浅灰蓝背景。

> A totally zoned-out middle-aged male professor, anthropomorphized as a giant salted fish, wearing a professor suit, sprawled on an office chair, instant noodles in mouth, TV remote in hand. Desk piled with instant noodle boxes and comics. Pale gray-blue background.

---

## 三、兜底 + 隐藏人格（3 张）

### 21. WTF 玄学导师
**标语**：你这导师，没法归类。
**Prompt**：
一位面部模糊、无法看清五官的教授，身上穿的衣服一半是西装一半是道袍一半是睡衣（三合一），周围漂浮着问号、太极图、神秘符号。背景是彩色迷幻漩涡，像开盲盒的感觉。

> A professor with blurred indistinguishable features, wearing a bizarre mashup outfit (half suit, half Taoist robe, half pajamas), surrounded by floating question marks, taichi symbols, mystical glyphs. Psychedelic colorful spiral background, mystery-box vibe.

---

### 22. BOSS-X 包工头
**标语**：周末来家里帮我看下孩子作业。
**Prompt**：
一位中年男教授打扮成工地包工头样子，头戴黄色安全帽但穿着西装，手里拿着一份写着「任务清单」的纸，上面列着「接孩子」「做饭」「陪酒」等。背景是脚手架和工地围栏，对比强烈。

> A middle-aged male professor dressed as a construction site foreman, wearing a yellow hard hat over his suit, holding a "task list" paper with items like "pick up kid", "cook", "drink with me". Scaffolding and construction fence background, strong contrast.

---

### 23. DRUNK-P 酒蒙子教授
**标语**：喝了这杯，什么都好说。
**Prompt**：
一位脸色通红、醉眼朦胧的中年男教授，领带歪斜，手里举着一个大茶杯（里面明显是白酒而不是茶），桌上摆满各种白酒瓶（茅台、五粮液）。背景是红灯笼高挂的饭局包间。

> A red-faced middle-aged male professor with glazed drunk eyes, tie askew, raising a large tea mug (clearly filled with baijiu not tea), table covered with liquor bottles (Moutai, Wuliangye). Private dining room background with hanging red lanterns.

---

## 四、使用建议

1. **先出一张试水**：挑 CTRL+ 或 PUA-R 这种视觉特征最明显的，跑出来看画风是否满意，再批量生成。
2. **保持画风一致**：同一提示词模板、同一模型、同一 seed 参考（如 Midjourney 用 `--sref` 参数）。
3. **不要在 prompt 里写中文字**：AI 生成的中文字基本全是乱码，建议**图纯画面**，文字（人格名、标语）**后期用 PS / Figma 叠加**。
4. **导出规格**：1024×1024 PNG，单张 ≤ 200KB（可用 tinypng 压）。
5. **命名规则**：`image/CODE.png`，注意 `CTRL+` 建议存成 `CTRL-PLUS.png`（URL 安全）。
