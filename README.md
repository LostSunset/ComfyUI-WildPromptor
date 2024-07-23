# WildPromptor

WildPromptor is a custom node collection for ComfyUI, designed to enhance prompt generation and management.

[English ](README.md) / [繁體中文 ](README.zh-tw.md) / [简体中文 ](README.zh-cn.md)

## Introduction

Ever felt like navigating ComfyUI’s wildcards was like juggling spaghetti? I did, and that’s why I created WildPromptor. Think of it as your keyword GPS, turning chaos into a breeze with an easy dropdown menu. No more forgetting wildcard names – just smooth, stress-free creativity.

WildPromptor is all about blending order and surprise. Organize your keywords neatly or let a bit of random magic inspire you with unexpected combinations. It’s your choice – plan meticulously or embrace serendipity.

Customization? We’ve got you covered. Modify categories, add new ones, or slot in your own preset prompts. WildPromptor adapts to your unique artistic needs, whether you’re a beginner or a seasoned pro.

In a nutshell, WildPromptor is your creative companion, making AI art fun, intuitive, and efficient. Say goodbye to wildcard headaches and hello to inspired prompts with WildPromptor!

## Structure and Features

### Data Organization
WildPromptor uses a flexible folder structure in the `data` directory:

- **Subject**: Keywords for characters, objects, and main subjects
- **Environment**: Keywords for settings, landscapes, and scenarios
- **Virtual**: Keywords for visual effects, camera settings, lighting, artists, and styles
- **Custom**: Pre-set comprehensive descriptions or story scenes
- **Styles**： Keyworks for Art styles and artists styles 
- **Negative**: Keywords for negative prompts

This structure is customizable, allowing users to add or modify folders as needed.

### Key Components
1. **Visual Keyword Selection**: Choose keywords from predefined categories using dropdown menus.
2. **Random Selection**: Option to randomly select keywords for unexpected creative combinations.
3. **Prompt Generation**: Combine selected keywords to create complete prompts.
4. **Dynamic Updates**: The node interface updates interactively based on folder content changes.
5. **Configurable Settings**: Use `config.json` to preset node parameters, display structure, server, and API data.

## How to Use

1. Place the WildPromptor folder in your ComfyUI's `custom_nodes` directory.
2. Organize your keywords into text files within the appropriate subfolders in the `data` directory.
3. Restart ComfyUI. The new nodes will appear under the "🧪 AILab/🧿 WildPromptor" category.
4. Add WildPromptor nodes to your workflow.
5. Configure node parameters:
   - Select keywords manually or use the "🎲 Random" option
   - Set the number of prompts to generate
   - Adjust the random seed for varied results
6. Connect WildPromptor nodes to other ComfyUI nodes in your generation pipeline.

## Customization

- Add new keyword files to existing folders or create new folders in the `data` directory.
- Modify `config.json` to adjust node settings, API connections, or display preferences.
- The node interface will automatically update to reflect changes in the folder structure and file contents.

## Benefits

- **Intuitive Interface**: Easily browse and select keywords without memorizing wildcard names.
- **Creativity Boost**: Random selection can lead to unexpected and inspiring prompt combinations.
- **Organized Workflow**: Keep your prompt creation process structured and efficient.
- **Highly Customizable**: Tailor the keyword categories and content to your specific needs.
- **Flexible Integration**: Seamlessly integrate with other ComfyUI nodes for diverse AI art generation workflows.

WildPromptor offers a balance between controlled input and serendipitous discovery in your AI art creation process, with the added benefit of easy customization and dynamic updates.