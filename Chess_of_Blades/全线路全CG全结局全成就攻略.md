# Chess of Blades 全线路全CG全结局全成就攻略

> 含剧透；已补齐22成就逐项清单及四线收集流程。

# Chess of Blades 全线路、全结局与全画廊攻略

适用版本：本机 scripts.rpa（SHA-256 见补丁验收报告）。依据本机英文脚本和画廊解锁代码编写，含剧透。下列路线条件已经过脚本核对；没有声称人工从头游玩了所有路线。人物保留英文名，方便对照选项。

## 收集顺序与存档

建议顺序：Arden 好结局 → Sabre 好/坏结局 → Franz 好/坏结局 → Linnaeus 好/坏结局 → Arden 坏结局 → 共通坏结局。四条角色线可按喜好调整，但 Sabre 必须先完成 Arden 好结局。

每条好结局请播放至片尾并回到标题画面，保留 persistent 数据。回到标题画面点 New Game 开始下一轮。不要删除存档目录、不要使用清除 persistent 的工具。通关后 CG/音乐入口可在 Extras 中查看，画廊有分页，所有缩略图和翻页都要检查。

共通阶段共有 9 次选择。前 8 次后会检查是否有任一角色分数达到 4；全都低于 4，立即进入共通坏结局，第 9 次不会出现。存档 A：共通第 1 次选择前；存档 B：每条角色线最后一次关键选择前；存档 C：进入 Sabre 的分岔前；存档 D：Sabre 线第 1、2、3 次选择前。

## 共通选择表（按顺序）

|序号|英文选项一 / 中文|效果|英文选项二 / 中文|效果|
|---|---|---|---|---|
|1|Maybe some other time... / 也许改天吧|Arden +1|Dancing? How horrific. / 跳舞？太可怕了|Linnaeus +1|
|2|That little brat! / 那个小捣蛋鬼|Franz +1|She might get in trouble... / 她可能会惹麻烦|Arden +1|
|3|Who does this bastard think he is?! / 这混蛋以为自己是谁|Linnaeus +1|Maybe I should hear him out... / 也许该听听他怎么说|Franz +1|
|4|I remember / 我记得|Linnaeus +1|I can't recall it / 我想不起来|Arden +1|
|5|Follow Franz / 跟着 Franz|Franz +1|Stay in the crowd / 留在人群里|Arden +1，并设置 Hazel 条件|
|6|Accept his apology / 接受道歉|Linnaeus +1|What's done is done / 过去的就算了|Arden +1|
|7|Have some cake / 吃蛋糕|Franz +1|Have a proper meal / 吃正餐|Linnaeus +1|
|8|To success / 为成功干杯|Linnaeus +1|To love / 为爱情干杯|Franz +1|
|9|It was horrible / 糟透了|Franz +1|We should've eaten together / 本该一起吃饭|Arden +1|

第 9 次后：优先检查 Franz ≥5，然后 Linnaeus ≥5，然后 Arden ≥5 且第 5 次选 Stay in the crowd；否则进入 Franz。不要仅以好感最高来判断路线。

## Arden：好结局与坏结局

共通阶段依次：
1. Maybe some other time...
2. She might get in trouble...
3. Maybe I should hear him out...
4. I can't recall it
5. Stay in the crowd
6. What's done is done
7. Have some cake
8. To love
9. We should've eaten together

这样 Arden=6，进入 Arden 线。线上依次：
1. Follow the voice / 循声过去（Arden 路线分 +1）
2. Keep going / 继续走（不影响 Arden 好结局；此流程不会进入 Sabre）
3. Tease him / 逗逗他（+1）
4. Chat a little more / 再聊会儿（+1）
5. Sad / 有点伤感（+1）
6. 【存档 B】I have to think / 我得想一想 → 好结局；读档改选 I have to act / 必须行动 → 坏结局。

好结局选项要求 Arden 路线分 ≥3；上述流程得 4 分。好结局到片尾会设置 persistent.ard_end，解锁下一轮进入 Sabre 的前置条件。其他选择可以有变化，不必所有加分项都正确；为方便收集，建议照表执行。

## Sabre：隐藏路线与两个结局

先完成 Arden 好结局并回到标题，然后 New Game。共通按上面的 Arden 流程重新进入 Arden 线。在 Arden 线前段改选：
1. Ignore the voice / 不理会声音（Sabre 分 +1）
2. Look back / 回头看（Sabre 分 +1）
3. 【存档 C】Split up and investigate more / 分头继续调查 → 进入 Sabre。另一个选项 I have a bad feeling / 我有不祥的预感，会继续 Arden 线。

出现隐藏分岔的准确条件：Sabre 分 ==2 且 persistent.ard_end ==True。没有先通 Arden 好结局就看不到这个菜单。

Sabre 线上：
1. I can't help but be involved / 我没法袖手旁观（+1；Play it off 不加分）
2. I'm the same as them / 我和他们一样（+1；I'm different 不加分）
3. 【存档 B】Shake my head / 摇头（+1）；Stay still / 不动（不加分）。

进入隐藏线时已经有 2 分，总分 ≥3 为好结局，<3 为坏结局。按前两项加分后，不论最后选哪个都是好结局。要看坏结局，必须从存档 D 或重开隐藏线，依次选 Play it off → I'm different → Stay still，总分保持 2。不能只在高分路线的最后一项改选来刷坏结局。

好结局另一种可作最终分歧存档的流程：Play it off → I'm different →【存档 B】Shake my head 得好结局，读档改 Stay still 得坏结局。首次进入时建议使用这个流程，一份末尾存档即可收集两个结局。

## Franz：好结局与坏结局

共通依次：Maybe some other time... → That little brat! → Maybe I should hear him out... → I can't recall it → Follow Franz → What's done is done → Have some cake → To love → It was horrible。

Franz 在第 8 次后 5 分，第 9 次后 6 分，稳定进入 Franz 线。线上：
1. Go to sleep / 睡觉（+1）
2. Try to get more information / 多问一些信息（+1）
3. He's my bodyguard / 他是我的护卫（+1）
4. Try to cheer him up / 让他振作起来（+1）
5. 【存档 B】There's one thing I know... / 有件事我很清楚 → 好结局；The kindest choice is... / 最仁慈的选择是 → 坏结局。

好结局选项要求 Franz 路线分 ≥3；上述流程得 4 分。注意 I shouldn't pry、I'm curious, too...、Press him further 都不加分。

## Linnaeus：好结局与坏结局

共通依次：Dancing? How horrific. → That little brat! → Who does this bastard think he is?! → I remember → Follow Franz → Accept his apology → Have a proper meal → To success → It was horrible。

Linnaeus 在第 8 次后 6 分，第 9 次保持 6 分，稳定进入本线。线上：
1. Look for a bench / 找张长椅：观看额外段落后也会回到散步主线；Keep walking 会跳过长椅段落。全 CG/剧情优先选择长椅，另存档再看继续走分支。
2. Speak up / 开口说话（路线分 +1）
3. The keys / 钥匙（路线分 +1；审判正确计数 +1）
4. The bottle's location / 瓶子的位置（路线分 +1；审判正确计数 +1）
5. 【存档 B】I can prove he wrote it / 我能证明是他写的 → 好结局；Search his room immediately! / 立刻搜他的房间 → 坏结局。

好结局选项要求路线分 ≥2。上述流程得 3 分；三条正确审判推理全部选对，还会满足 lin_trial==3 的审判成就条件。这里的审判计数与好感分是两个变量，不要混淆。

## 共通坏结局

从 New Game 开始，前 8 次依次：Maybe some other time... → That little brat! → Who does this bastard think he is?! → I remember → Stay in the crowd → What's done is done → Have some cake → To success。

检查时 Arden=3、Franz=2、Linnaeus=3，均低于 4，进入 day2_badend。该结局没有第 9 次选项，不设置四位角色的通关标记。

## 全结局清单与通关奖励

共 9 个脚本结局分支：共通坏结局；Arden 好/坏；Franz 好/坏；Linnaeus 好/坏；Sabre 好/坏。四个角色好结局各自设置 persistent.ard_end / franz_end / lin_end / sab_end；四项齐全后进入 thankyou 感谢画面并触发对应总通关成就条件。坏结局不会代替好结局标记。

此补丁不直接修改 persistent，不伪造已读、成就或画廊解锁。全收集按上述顺序正常游玩完成。

## CG 收集说明

当前安装的脚本 nsfw=True，包含附加场景分支。补丁遵循原脚本设置，不改变内容开关。如果使用的是另一种版本，其可见 CG 会不同。成人场景图片没有绘制文字翻译；其中对白按同一双语机制显示。主菜单、图片内文字、片头片尾影像不在本补丁对白翻译范围。

画廊共 39 个按钮：共通 3、Arden 10、Franz 10、Linnaeus 10、Sabre 6。多数按钮内含多幅差分，解锁按钮后继续点击画面浏览全部差分；不能只看缩略图。完成四条好结局和四条坏结局，并在 Linnaeus 线选择长椅段落，可覆盖下表列出的主线 CG 解锁位置。表中“位置”直接来源于脚本中的 show/scene 指令，便于定位遗漏；它记录解锁所需图片首次显示的位置，不表示只有这一处能够解锁。

以下为逐项清单。

|画廊按钮|解锁图片|所属路线 / 脚本段落|
|---|---|---|
|cg1|cg1|start|
|cg2|cg2_2|start；sabre_resume_2|
|cg3|cg3_1|day2_resume1；day2_resume2；day2_success；day2_love|
|sabre1|cg sabre1|sabre|
|sabre2|cg sabre2_1|sabre_resume_1|
|sabre3|cg sabre3|sabre_resume_2；sabre_good|
|sabre4|cg sabre4_1|sexytimes_sabre|
|sabre5|cg sabre5_1|sexytimes_sabre|
|sabre6|cg sabre6_1|sabre_end|
|ard1|cg arden1|arden1|
|ard2|cg arden2_1|arden_resume2|
|ard3|cg arden3_1|arden_resume2|
|ard4|cg arden4_1|arden_resume2|
|ard5|cg_arden_5|arden_resume3|
|ard6|cg arden6_1|arden_resume4|
|ard7|cg arden7|arden_resume4|
|ard8|cg arden8_1|sexytimes_ard|
|ard9|cg arden9_1|sexytimes_ard|
|ard10|cg arden10_1|arden_end|
|franz1|cg franz1_1|franz1|
|franz2|cg franz2|franz2|
|franz3|cg franz3_1|franz_resume_3|
|franz4|cg franz4_1|franz_resume_3；franz_press；franz_cheer|
|franz5|cg franz5_1|franz_resume_4|
|franz6|cg franz6_1|sexytimes_franz|
|franz7|cg franz7_1|sexytimes_franz|
|franz8|cg franz8_1|franzy_resume|
|franz9|cg franz9|franz_good|
|franz10|cg franz10_1|franz_good|
|lin1|cg lin1_1|lin_walk|
|lin2|cg lin2_1|lin_walk|
|lin3|cg lin3_1|lin_walk|
|lin4|cg lin4_1|linnaeus2|
|lin5|cg lin5_1|lin_silas_resume|
|lin6|cg lin6|lin_silas_resume；lin_1_1；lin_1_2；lin1_resume；lin2_1；lin2_2；lin2_resume；linnaeus_bad；linnaeus_good|
|lin7|cg lin7_1|lin_bench|
|lin8|cg lin8_1|sexytimes_lin|
|lin9|cg lin9_1|sexytimes_lin|
|lin10|cg lin10_1|lin_end|

CG 表中的 sexytimes_* 为原版附加场景，*_bad 是坏结局段落，*_good / *_end 为好结局及尾声，其他为途中剧情。画廊按图片是否见过来解锁，不要求逐幅差分都在主线看过。


---

# Chess of Blades 全成就攻略

> **含全路线与关键选择剧透。未开始收集前可关闭此文件。**

本攻略补齐全部 **22 项 Steam 成就**，按实际游戏脚本逐项核对，并与本机 Steam 公开成就定义缓存的22个内部ID一一对应。英文成就名沿用Steam定义，中文名称为本攻略辅助译名。

## 先看这里：旧攻略为什么会漏成就

原攻略围绕全路线、结局与CG编排，没有列出全部成就。**Go investigate、Try to stay awake、Keep walking、Let Linnaeus handle it** 等成就选项与原推荐流程不同，因此照旧推荐走可能漏项。本攻略提供完整成就路线，之后再按旧攻略补CG与坏结局。

## 存档与触发原则

- 从 Steam 库启动你购买的游戏，保持原游戏成就功能及 persistent 数据；本攻略与补丁不会代替你授予或清除成就。
- 每个选择后继续推进一段对白，等实际授予位置执行；不要选完立即退出或回读。
- 优先保留普通存档：共通第一选项前、每条线各菜单前、最终结局选项前。单项成就触发后可读回选择前的档，换回你的正常路线选项；本地成就后端采用持久化集合，不随普通剧情回滚清除。Steam弹出或到账情况以客户端实际记录为准。
- 通关成就需推进到片尾授予处；总通关成就还要继续到最后一条好结局的片尾后检查。不要删除/重置 persistent，也不要为“补成就”修改分数或通关变量。
- 成人内容开关不改变本文22项授予条件：两个开关状态下的四线流程均做了脚本模型验证。CG可见内容仍取决于原游戏版本。

## 全22项成就逐项清单

按此表逐项勾选。内部ID仅用于查错，对正常游玩无操作要求。

|完成|分类|Steam英文名 / 中文辅助名|精确解锁方法|补漏与易错点|脚本依据|
|---|---|---|---|---|---|
|☐|共通|Not a Dancing Man / 不擅舞蹈<br>`1_dance`|共通第1次选择 Dancing? How horrific.（跳舞？太可怕了）。|选择前存档，选中后推进至该段对白，再读档换回所需路线选项。|intro.rpy:267|
|☐|共通|Look, Don't Touch / 只许看，不许碰<br>`2_touch`|共通第3次选择 Who does this bastard think he is?!（这混蛋以为自己是谁？！）。|不必进入某一角色线；选中后继续推进。|intro.rpy:903|
|☐|共通|Stick by Your Friends / 守在朋友身边<br>`3_friends`|共通第5次选择 Stay in the crowd（留在人群里）。|同时是阿登线路所需条件之一；弗朗茨/林奈流程可另读共通存档补。|day2.rpy:530|
|☐|共通|Sweet Tooth / 甜食爱好者<br>`4_sweets`|共通第7次选择 Have some cake（吃点蛋糕）。|不必吃正餐；全成就阿登/弗朗茨流程都会取得。|day2.rpy:1192|
|☐|阿登|No Man Left Behind / 不落下任何人<br>`a1_voice`|阿登线上第1次选择 Follow the voice（循声过去）。|Ignore the voice（不理会声音）用于隐藏路线前置，不会授予本项。|arden1.rpy:630|
|☐|阿登|Impatience / 迫不及待<br>`a2_impatience`|阿登线调查前选择 Go investigate（去调查）。|旧好结局攻略推荐 Chat a little more，会漏本项。换选会少1路线分，使用本文其余加分选项仍有3分。|arden2.rpy:419|
|☐|阿登|Mad After All / 终究还是疯了<br>`a3_mad`|庆典最后一天的情绪选项选择 Sad（伤感）。|Homesick 不触发。沿 arden_sad 段落推进后授予。|arden2.rpy:1372|
|☐|阿登|Always By Your Side / 始终在你身边<br>`a4_arden`|完成阿登好结局并推进到片尾前通关授予位置。|最后选 I have to think，且阿登路线分≥3；本文流程恰为3分。坏结局不授予。|arden2.rpy:2931|
|☐|萨布尔|Kick the Puppy / 狠心丢下小狗<br>`s1_puppy`|已通阿登好结局后再进阿登线：Ignore the voice → Look back → Split up and investigate more（分头继续调查）。|要求 sab_route_p == 2 且 persistent.ard_end == True；只选忽略声音或回头看尚未获得。|arden1.rpy:1225|
|☐|萨布尔|Dangerously Honest / 危险的坦率<br>`s2_honest`|隐藏线上第1次选择 I can't help but be involved（我没法袖手旁观）。|Play it off 不触发。成就在后续 sabre_earnest 段落授予。|sabre.rpy:406|
|☐|萨布尔|Special Snowflake / 与众不同<br>`s3_snow`|隐藏线上第2次选择 I'm different（我和他们不同）。|I'm the same as them 不触发；本项不增加路线分，但本文已有3分，仍可好结局。|sabre.rpy:1015|
|☐|萨布尔|Two Sides to Every Story / 故事的另一面<br>`5_twosides`|进入萨布尔线，继续到与黑兹尔相关的真相说明段落；脚本在 sabre.rpy:1749 自动授予。|单纯进入隐藏路线还不够，要继续读到该段；好坏结局前均经过。|sabre.rpy:1749|
|☐|萨布尔|Silly Little Peacock / 傻气的小孔雀<br>`s4_sabre`|完成萨布尔好结局并推进到片尾授予位置。|本流程选坦率→不同→Shake my head，最终4分，满足≥3。坏结局不授予。|sabre.rpy:3170|
|☐|弗朗茨|One Eye Open / 睁着一只眼睡觉<br>`f1_eye`|弗朗茨线首次夜宿选择 Try to stay awake（尽量保持清醒），并读过随后的警惕入睡段落。|旧攻略的 Go to sleep 不触发；换选会少1路线分，后续3个加分项全选仍能好结局。|franz1.rpy:542|
|☐|弗朗茨|He Guards My Body, All Right / 他的确护着我的身体<br>`f2_guard`|身份介绍时选择 He's my bodyguard（他是我的护卫）。|沿 franz_bodyguard 段落继续后授予。|franz2.rpy:456|
|☐|弗朗茨|...And Their Chocolates Suck / ……而且他们的巧克力也很难吃<br>`f3_chocolate`|谈到对方过去时选择 Try to cheer him up（试着让他振作起来）。|Press him further 会漏此项。选安慰后继续推进到相关对白。|franz2.rpy:1195|
|☐|弗朗茨|A King and His Knight / 国王与骑士<br>`f4_franz`|完成弗朗茨好结局并推进到片尾授予位置。|最后选 There's one thing I know...，且路线分≥3。本文前三个后续加分项都要选对。|franz2.rpy:2661|
|☐|林奈|I Don't Bench, Actually / 其实我不坐长椅<br>`l1_bench`|林奈线散步时选择 Keep walking（继续走）。|尤其容易选反：成就是不找长椅。CG收集仍需另读 Look for a bench 的额外段落，两者读档兼得。|linnaeus1.rpy:802|
|☐|林奈|He Knows What He's Doing / 他知道自己在做什么<br>`l2_glasses`|冲突中选择 Let Linnaeus handle it（交给林奈处理）。|Speak up 不授予。此选择不加路线分，之后两次证据题必须全对，才能显示好结局选项。|linnaeus2.rpy:363|
|☐|林奈|Rivian Wright / 里维安·赖特<br>`l3_wright`|依次选 The keys（钥匙）→ The bottle's location（瓶子的位置）→ I can prove he wrote it（我能证明是他写的），并继续庭审到 lin_trial == 3 的授予处。|路线分与庭审正确计数不同；仅到好结局并不自动保证本项。第三题的另一个选项会进坏结局。|linnaeus2.rpy:1687|
|☐|林奈|The Spring Thaw / 春日解冻<br>`l4_lin`|完成林奈好结局并推进到片尾授予位置。|路线分≥2且最后选 I can prove he wrote it；本文正好2分，不可再错前两道证据题。|linnaeus2.rpy:2664|
|☐|总收集|Grandmaster / 大师<br>`6_grandmaster`|四个角色好结局均播放至设置通关标记，完成最后一条后继续片尾，四项标记齐全且 persistent.seenall == False 时授予。|不要求9个好坏结局或39个画廊按钮全满。不要看见收尾画面就提前退出。若已全通但缺失，可重读一条好结局片尾；不要删除 persistent。|arden2.rpy:2941；franz2.rpy:2670；linnaeus2.rpy:2673；sabre.rpy:3179|

## 从零开始：四条完整流程收齐22项

推荐顺序：**阿登 → 萨布尔 → 弗朗茨 → 林奈**。每条都完整走到好结局片尾，保留持久化通关记录，再从 New Game 开始下一条。按下面流程走，四线合计覆盖全部22项。不是最短游戏时间的数学证明，而是已逐项验证的可执行四线方案。

共通选择按出现顺序列出；没有出现本文所列选项时先核对是否进入了正确路线。中文选项在不同补丁中措辞可能略有差异，以英文原文为准。

### 第1轮：阿登全成就流程

**共通线九次选择：**

1. **Maybe some other time...**
2. **She might get in trouble...**
3. **Maybe I should hear him out...**
4. **I can't recall it**
5. **Stay in the crowd**
6. **What's done is done**
7. **Have some cake**
8. **To love**
9. **We should've eaten together**

**进入角色线后：**

1. **Follow the voice**
2. **Keep going**
3. **Tease him**
4. **Go investigate**
5. **Sad**
6. **I have to think**

本方案将旧流程的 Chat a little more 改为 **Go investigate**。路线分为3，足够好结局；最后必须选 **I have to think**。继续到授予与片尾，才完成后续隐藏路线的前置。

本轮流程会执行的成就授予：Stick by Your Friends、Sweet Tooth、No Man Left Behind、Impatience、Mad After All、Always By Your Side。

### 第2轮：萨布尔全成就流程

**共通线九次选择：**

1. **Maybe some other time...**
2. **She might get in trouble...**
3. **Maybe I should hear him out...**
4. **I can't recall it**
5. **Stay in the crowd**
6. **What's done is done**
7. **Have some cake**
8. **To love**
9. **We should've eaten together**

**进入角色线后：**

1. **Ignore the voice**
2. **Look back**
3. **Split up and investigate more**
4. **I can't help but be involved**
5. **I'm different**
6. **Shake my head**

必须先完成上一轮阿登好结局。本文隐藏路线最终4分。**I'm different** 为成就选择，不要改成旧高分流程的 I'm the same as them。中途真相段落自动授予一项，需继续阅读。

本轮流程会执行的成就授予：Stick by Your Friends、Sweet Tooth、Two Sides to Every Story、Kick the Puppy、Dangerously Honest、Special Snowflake、Silly Little Peacock。

### 第3轮：弗朗茨全成就流程

**共通线九次选择：**

1. **Maybe some other time...**
2. **That little brat!**
3. **Maybe I should hear him out...**
4. **I can't recall it**
5. **Follow Franz**
6. **What's done is done**
7. **Have some cake**
8. **To love**
9. **It was horrible**

**进入角色线后：**

1. **Try to stay awake**
2. **Try to get more information**
3. **He's my bodyguard**
4. **Try to cheer him up**
5. **There's one thing I know...**

首个夜宿选 **Try to stay awake**，不是旧推荐的 Go to sleep。路线分最终3；后面的 **Try to get more information、He's my bodyguard、Try to cheer him up** 三项必须全部照选，最后选 **There's one thing I know...**。

本轮流程会执行的成就授予：Sweet Tooth、One Eye Open、He Guards My Body, All Right、...And Their Chocolates Suck、A King and His Knight。

### 第4轮：林奈全成就流程

**共通线九次选择：**

1. **Dancing? How horrific.**
2. **That little brat!**
3. **Who does this bastard think he is?!**
4. **I remember**
5. **Follow Franz**
6. **Accept his apology**
7. **Have a proper meal**
8. **To success**
9. **It was horrible**

**进入角色线后：**

1. **Keep walking**
2. **Let Linnaeus handle it**
3. **The keys**
4. **The bottle's location**
5. **I can prove he wrote it**

**Keep walking** 和 **Let Linnaeus handle it** 是两项分支成就所需选项，不能照旧推荐改回长椅或主动发言。之后 **The keys → The bottle's location → I can prove he wrote it** 三项都选对，路线分2、庭审正确计数3。作为第四条好结局完成后，继续片尾，检查总通关成就。

本轮流程会执行的成就授予：Not a Dancing Man、Look, Don't Touch、Grandmaster、I Don't Bench, Actually、He Knows What He's Doing、Rivian Wright、The Spring Thaw。

## 兼顾全CG、全结局：必须另外做的补充

1. **林奈长椅CG**：在 Keep walking / Look for a bench 的选择前存档，先选 Look for a bench，读完额外段落再读回，改 Keep walking 取得成就并继续本文路线。仅按本文主流程一直走会跳过这段CG。
2. **四条角色坏结局与共通坏结局**：并非22项成就的额外要求，但全结局与相关CG仍需取得。按同目录《全线路全CG全结局全成就攻略》的结局部分补；不要把“22成就全齐”当成“画廊全满”。
3. **萨布尔坏结局**：本文好结局流程前两项后已达3分，最后改 Stay still 仍是好结局。要补坏结局，从隐藏线首项前读档，依次 Play it off → I'm different → Stay still，保持2分。
4. **阿登和弗朗茨坏结局**：最终分歧前存档，按综合攻略换坏结局选项即可；再读回好结局继续完成持久化通关记录。
5. **林奈坏结局**：最终菜单选 Search his room immediately!；完成后读回，改 I can prove he wrote it 继续好结局与庭审成就。

## 已通关玩家：快速补漏

只缺个别项，优先读到对应菜单之前的旧档，并按逐项表操作。最常见遗漏是上述四个与旧推荐不同的选择。只缺庭审成就时，需从第一次证据选择前重答三题；只读到最后菜单无法补回前两道错误。

只缺总通关项时，先确认四个角色的**好**结局都读到片尾授予处。保留所有持久化数据，重读最后一条好结局片尾。若仍缺，检查原游戏的Steam连接与成就同步状态；本攻略没有进行你账号的在线成就写入或测试，不保证客户端一定即时弹窗。

## 核对依据与验证范围

- 主依据：本机原游戏解出的不可变脚本快照，25处 achievement.grant 调用合并为22个不同ID；其中总通关ID在四线片尾重复出现。
- 名称依据：Steam 本地公开定义缓存 `appcache/stats/UserGameStatsSchema_618550.bin`，不读取玩家成就进度或账号私密信息。该缓存可能随平台更新；本版记录的是读取时定义。
- 上述四线在成人开关开/关两种状态逐次模拟，沿实际赋值、条件与菜单执行，合计22个ID均出现；同时验证3/3/2/4路线分及庭审3题正确。
- 这是**静态脚本控制流验证**，不是全路线实机通关，也不是Steam账号22项到账实测。未修改原游戏、原英文、存档或成就状态。
- 官方商店入口：[Chess of Blades](https://store.steampowered.com/app/618550/Chess_of_Blades/)；[Steam全局成就入口](https://steamcommunity.com/stats/618550/achievements/)。本轮网页成就列表无法抓取，故名称以本机Steam定义缓存核对，解锁条件以原脚本为准。
