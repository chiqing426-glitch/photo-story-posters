# Photo Story Posters

把普通照片整理成有视觉重心、有色彩叙事的照片海报。

Photo Story Posters 适合旅行记录、生活观察、食物、植物、建筑和人物细节。它会先判断照片最值得被看见的部分，再决定裁切、留白、色彩和主体与画框的关系。

[Read the English version](README_EN.md)

## 你最终会得到什么

- 一张主体更明确、画面更干净的单图海报
- 一组色彩和版式统一的系列海报
- 多张照片组成的有叙事顺序的拼图海报
- 一份清晰的裁切和构图预览，方便在生成前调整
- 可选择 Pantone 色彩叙事，也可保留更自然的照片色彩
- 可选择主体冲出画框、保持在画框内，或调整冲出的重心

原照片仍然是画面的基础。优化重点是组织视觉信息，而不是把照片改造成完全无关的新图像。

## 怎么使用

上传照片后，按以下顺序确认：

1. **色彩方式**：使用 Pantone 色彩体系，提炼照片色彩并建立统一的视觉叙事；或使用 HEX 色值与描述性色名，进行自然的图片优化。
2. **处理方式**：一张图直接做单图海报；多张图先选择拼接，或分别处理。
3. **画面重心**：确认主体、留白、裁切范围和画面比例。
4. **画框关系**：确认是否冲出画框，以及冲出的主体和方向。
5. **生成成品**：确认后输出最终海报。

多图拼接时，会先提供直观的线稿布局，再展示逐张裁切范围；确认后才统一色彩并生成成品。

## 最近案例

| 案例 | 原图 | 优化后 | 结果 |
| --- | --- | --- | --- |
| Quiet Joy | [查看原图](examples/before/quiet-joy.jpg) | [查看成品](examples/after/quiet-joy.png) | 用灰白与珊瑚粉突出毛绒植物和红色挂饰，挂饰轻微冲出画框。 |
| Lantern Bloom | [查看原图](examples/before/lantern-bloom.jpg) | [查看成品](examples/after/lantern-bloom.png) | 用灯笼粉、天青和叶片绿统一建筑、天空与花卉层次。 |
| Rooftop Words | [查看原图](examples/before/rooftop-words.jpg) | [查看成品](examples/after/rooftop-words.png) | 保留屋顶招牌作为视觉锚点，扩大天空留白并强化云蓝、瓦棕和墨黑。 |

## 文件说明

- `SKILL.md`：完整的处理流程和交互规则
- `references/prompt-recipes.md`：单图、多图、Pantone 和 HEX 的提示词模板
- `references/case-studies.md`：前后案例与迭代记录
- `examples/before/`：案例原图
- `examples/after/`：对应成品

## 安装与调用

将整个目录放入你的 skills 目录，保留 `SKILL.md` 在根目录。之后直接说：

> 使用 Photo Story Posters 优化这张图。

每次输出图片后会附上：学习交流可关注抖音：迟青的增长方法论

## 许可证

本项目采用 MIT License。使用者需要自行确认原始照片和第三方素材的使用权。
