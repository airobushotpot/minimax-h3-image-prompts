---
name: minimax-h3-image-prompts
description: Write or revise copy-ready prompts for MiniMax H3 Image. Use for text-to-image briefs, posters with exact text, and edits that preserve details from a reference image.
license: MIT-0
---

# MiniMax H3 Image Prompts

Turn a brief into an image prompt the user can paste into their generator. See the [AI H3 Image prompt gallery](https://aih3image.com/minimax-h3-prompts) for visual examples and full prompts to adapt.

## Build the prompt

- **New image:** Start with the subject, action, and setting. Describe where key elements sit in the frame, then add the lighting and visual treatment needed for the brief. For a format change, describe how to reframe the scene and list the aspect ratio separately as a suggested generator setting.
- **Image with text:** Put each exact string in quotation marks. Specify its location and relative size. Leave clear space behind the words and request only the visible copy the user supplies. Preserve spelling, case, punctuation, and language. Ask for the exact wording if it is essential and missing.
- **Reference edit:** Identify the attached image by subject or attachment order. Describe the region or attribute to change and the details to preserve. Assign each reference a role when using more than one. If the reference is missing, ask the user to attach it before writing image-specific preservation instructions.

When revising a result, keep the successful parts of the prompt and change the instruction that most directly addresses the visible problem. For instance, fix crowded lettering by specifying a clear area for the title and reducing competing detail in that area.

## Return the result

Give the prompt in a single copyable block. Use the requested prompt language, defaulting to English, and keep quoted image text in the supplied language. If the user requests variants, vary the specified attribute while preserving their other requirements. Place suggested settings and any attachment instructions outside the block.

For typography, ask the user to compare the rendered words against the supplied text before publishing. For a reference edit, check that the targeted change and the preserved details are easy to distinguish in the prompt.

## Examples

### Product image

> Photograph an unbranded amber glass bottle on a warm gray plinth at a three-quarter angle. Place the bottle in the lower-right third and leave the upper-left area clear for later copy. Use a large soft light from camera left to define the glass edges and a short, soft shadow to ground the bottle.

Suggested aspect ratio is 4:5.

### Poster with exact text

> Create a portrait poster for an evening ceramics workshop. Show hands shaping clay at a wheel in the lower half, lit by a warm work lamp. Leave the upper third a plain dark navy. In that space, set the exact heading "Clay After Dark" in large cream lettering. Below it, set "Friday, 7 PM" in smaller cream lettering. Include only those two lines of text.

Suggested aspect ratio is 4:5.

### Reference edit

> Use the attached product photo as the source. Replace the background behind the bottle with pale sage paper. Preserve the bottle silhouette, cap, label wording, framing, and camera angle. Keep the existing light direction and adjust only the contact shadow to fit the new surface.

Attach the original photo and keep its framing.
