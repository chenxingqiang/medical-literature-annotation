第一步：标注实体
首先，请在文本中识别出两类特定的实体。
1. 选中实体文本：用鼠标划选出代表“致病菌”或“自身免疫性疾病”的词语。
2
. 选择标签：
B
acteria (致病菌): 蓝色标签，快捷键 b 。
示例： 幽门螺杆菌 、 普氏菌
Disease (自身免疫性疾病): 红色标签，快捷键 d 。
示例： 类风湿性关节炎 、系统性
红斑狼疮
第二步：标注证据和选择关系类型
接下来，找到描述第一步中两个实体之间关系的句子，
并定义这种关系的具体类型。
1. 标注证据 (Evidence)：
操作：用鼠标选中能够完
整描述
实体间关系的整个句子。
标签：选择 Evidence (证据)，黄色标签，快捷键 e 。
2
. 选择关系类型（可选，方便后续的关系分类） ：
操作：选中“证据”后，在下方"Evidence"处，会出现四种关系类型。请根据证据句
的语义，选择一种最合适的关系。
关系选项说明：
contributes_to (负面影响): 菌 导致、触发、加剧、促进 了疾病。
ameliorates (正面影响): 菌 改善、缓解、抑制、治疗 了疾病。
correlated_with (统计关联): 文本只描述
了菌的丰度与疾病相关（如：患者体
内该菌更多/更少） ，但未明确说明因果。
biomarker_for (应用功能): 菌可以作为疾病诊断、预测或分型的生物标志物。
第三步：关联实体到证据 (创建角色)
最后一步，将我们标注的“实体”和“证据”连接起来，明确谁是关系的主体，谁是客体。
1. 操作：点击实体，在界面右侧的 Info标注结果区 选者创建关系，然后再点击“证
据”区域便创建了关联，然后在右侧 Rela
tions处下拉框选择角色选项（如下图） 。
2
. 选择角色：
has_subject : 用 于 连 接 发 起方， 在 这里通 常 是 B
acteria ( 致 病 菌) 。
has_object : 用于连接承受方，在这里通常是 Disease (自身免疫性疾病)。
简单记法：菌 (Su
bject) -> 证据句 <- 疾病 (Object)