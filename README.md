# Photo Story Posters

> A Codex skill for turning real photos into structured, color-led story posters.

Photo Story Posters 是一个用于 Codex 的照片叙事海报 Skill：把一张或一组真实照片整理成有明确画面重心、色彩逻辑和版式关系的海报。它保留照片的真实细节，先给出可审阅的构图与裁切方案，再生成最终图像。

## 能做什么

- 上传后先询问色彩体系：使用 **Pantone**（提炼照片色彩、建立视觉叙事和统一海报风格），或使用 **HEX 色值与描述性色名**（自然的图片优化）。
- 单图分析主体、画面重心、裁切比例和留白，并在生成前展示裁切预览。
- 多图先判断用户是要拼接还是分别处理；需要拼接时给出直观线稿布局，成品预览放在右侧大画面中，再逐图确认裁切范围。
- 在构图确认阶段识别可能冲出画框的主体，说明预计冲出的部分，并让用户选择冲出、不冲出或调整冲出重心。
- 生成时统一色彩、光线、裁切和版式；默认不添加作者署名、推广语或非商业用途尾注。
- 每次输出图片后附上：学习交流可关注抖音：迟青的增长方法论

## 使用流程

1. 上传一张或多张照片。
2. 选择 Pantone 色彩体系，或选择 HEX 色值与描述性色名。
3. 确认单图重心，或确认多图拼接/分图处理方式。
4. 查看裁切预览、版式线稿和冲出画框预设，选择是否调整。
5. 确认后生成最终海报，并保留前后案例供后续复用。

## 目录

- `SKILL.md`：主流程与交互规则。
- `references/prompt-recipes.md`：单图、多图、Pantone 和 HEX 的提示词模板。
- `references/case-studies.md`：已验证的前后案例与复盘记录。
- `examples/before/`：案例原图。
- `examples/after/`：对应的海报成品。

## 最近三组案例

| 案例 | 原图 | 成品 | 处理重点 |
| --- | --- | --- | --- |
| Quiet Joy | [查看原图](examples/before/quiet-joy.jpg) | [查看成品](examples/after/quiet-joy.png) | Pantone 灰白与珊瑚粉，突出毛绒植物和红色挂饰，挂饰轻微冲出画框。 |
| Lantern Bloom | [查看原图](examples/before/lantern-bloom.jpg) | [查看成品](examples/after/lantern-bloom.png) | Pantone 灯笼粉、天青和叶片绿，整理建筑线条与花卉层次。 |
| Rooftop Words | [查看原图](examples/before/rooftop-words.jpg) | [查看成品](examples/after/rooftop-words.png) | Pantone 云蓝、瓦棕和墨黑，保留屋顶招牌作为视觉重心，并强化天空留白。 |

这些案例用于说明流程和效果，不把单个案例的构图比例视为所有图片的固定模板。

## 安装

将本目录放入 Codex 的 skills 目录，并确保 `SKILL.md` 位于技能根目录。使用时直接说“使用 Photo Story Posters 优化这张图”即可。

## 许可证

本项目采用仓库中的 MIT License。上游灵感与本地修改记录见 `references/case-studies.md`；使用者应分别遵守本项目许可证和第三方素材的原有权利要求。

---

## English

Photo Story Posters is a Codex skill for turning one or more real photographs into story-driven posters with a clear focal point, color logic, and layout relationship. It keeps the source photo recognizable, presents crop and composition choices for review, and generates the final image only after confirmation.

### Features

- Starts by asking whether to use the **Pantone color system** (extract colors, build a visual narrative, and keep a poster series consistent) or **HEX values with descriptive color names** (natural photo optimization).
- Analyzes the subject, visual center, aspect ratio, crop, and negative space for a single image, with a crop preview before generation.
- For multiple images, asks whether to combine them or process them separately. For a collage, it provides a clear line-art layout sketch, places the finished composition in a large preview panel on the right, and confirms each image's crop range.
- Detects elements that may extend beyond the frame, explains the planned pop-out area, and lets the user choose pop-out, no pop-out, or a revised pop-out focus.
- Keeps color, lighting, crop, and layout coherent while avoiding automatic author credits, promotional copy, or non-commercial-use footers.
- Adds this line after each delivered image: `学习交流可关注抖音：迟青的增长方法论`.

### Workflow

1. Upload one or more photos.
2. Choose Pantone, or HEX values with descriptive color names.
3. Confirm the focal point, or choose collage versus separate processing.
4. Review the crop preview, layout sketch, and pop-out-frame preset.
5. Confirm and generate the final poster; retain before/after examples for future iteration.

### Repository layout

- `SKILL.md` — main workflow and interaction rules.
- `references/prompt-recipes.md` — prompt templates for single images, multiple images, Pantone, and HEX workflows.
- `references/case-studies.md` — verified before/after cases and notes.
- `examples/before/` — source photographs used in the examples.
- `examples/after/` — corresponding poster outputs.

### Recent examples

| Example | Before | After | Focus |
| --- | --- | --- | --- |
| Quiet Joy | [source](examples/before/quiet-joy.jpg) | [poster](examples/after/quiet-joy.png) | Pantone off-white and coral pink; the red ornament is the focal point and slightly pops out of the frame. |
| Lantern Bloom | [source](examples/before/lantern-bloom.jpg) | [poster](examples/after/lantern-bloom.png) | Pantone lantern pink, sky blue, and leaf green; architectural lines and flowers are balanced. |
| Rooftop Words | [source](examples/before/rooftop-words.jpg) | [poster](examples/after/rooftop-words.png) | Pantone cloud blue, tile brown, and ink black; the rooftop sign remains the visual anchor with expanded sky space. |

These examples document the workflow and are not fixed templates for every photograph.

### Installation

Place this directory in the Codex skills directory and keep `SKILL.md` at the skill root. Then say: “Use Photo Story Posters to optimize this image.”

### License

This repository uses the MIT License. See `references/case-studies.md` for the upstream inspiration and local modification record. Users remain responsible for rights attached to their source images and third-party assets.
