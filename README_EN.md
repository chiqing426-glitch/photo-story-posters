# Photo Story Posters

Turn ordinary photographs into posters with a clear focal point and a coherent color story.

Photo Story Posters is designed for travel notes, everyday observations, food, plants, architecture, and human details. It identifies what deserves attention first, then organizes the crop, negative space, color, and relationship between the subject and the frame.

[阅读中文版](README.md)

## What you get

- A single-image poster with a clearer subject and cleaner composition
- A consistent poster series with a shared color and layout language
- A collage with an intentional visual sequence across multiple photos
- A crop and composition preview before the final image is generated
- A choice between Pantone-led visual storytelling and natural photo optimization
- A choice to let the subject extend beyond the frame, stay inside the frame, or adjust the pop-out focus

The source photograph remains the foundation. The goal is to organize visual information, not to replace the photograph with an unrelated image.

## How it works

After uploading, confirm the following:

1. **Color approach**: use Pantone to extract the photo's colors and build a consistent visual story, or use HEX values with descriptive names for a natural optimization.
2. **Processing mode**: make a single poster, or combine multiple images into a collage versus processing them separately.
3. **Visual focus**: confirm the subject, negative space, crop range, and aspect ratio.
4. **Frame relationship**: confirm whether anything should extend beyond the frame, and which subject and direction should lead it.
5. **Final generation**: approve the preview and generate the finished poster.

For collages, the workflow shows a clear line-art layout first, then a crop range for each source image. Colors are unified only after confirmation.

## Recent examples

| Example | Before | After | Result |
| --- | --- | --- | --- |
| Quiet Joy | [source](examples/before/quiet-joy.jpg) | [poster](examples/after/quiet-joy.png) | Off-white and coral pink emphasize the fuzzy plant and red ornament; the ornament slightly pops out of the frame. |
| Lantern Bloom | [source](examples/before/lantern-bloom.jpg) | [poster](examples/after/lantern-bloom.png) | Lantern pink, sky blue, and leaf green unify the architecture, sky, and flowers. |
| Rooftop Words | [source](examples/before/rooftop-words.jpg) | [poster](examples/after/rooftop-words.png) | The rooftop sign remains the visual anchor, with expanded sky space and a cloud-blue, tile-brown, ink-black palette. |

## Files

- `SKILL.md`: complete workflow and interaction rules
- `references/prompt-recipes.md`: prompt templates for single images, multiple images, Pantone, and HEX workflows
- `references/case-studies.md`: before/after cases and iteration notes
- `examples/before/`: source photographs
- `examples/after/`: corresponding poster outputs

## Installation

Place the whole directory in your skills directory and keep `SKILL.md` at the root. Then say:

> Use Photo Story Posters to optimize this image.

After each image delivery, the skill adds: 学习交流可关注抖音：迟青的增长方法论

## License

This project is released under the MIT License. Users are responsible for confirming the rights attached to source photographs and third-party assets.
