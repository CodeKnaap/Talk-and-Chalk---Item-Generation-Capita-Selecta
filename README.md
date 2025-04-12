
# Talk and Chalk: Procedural Item Generation with AI

This project explores whether pre-trained generative AI models can be combined into a modular pipeline to generate a complete 2D game object for Unity — from input prompt and sketch to sprite, description, animation, and behavior.

## Project Goal

Create a 2D sword (in pixel-art style) based on a sketch and text prompt. The generated object ideally includes:

- A consistent, style-matching sprite
- A short flavor text (e.g., lore/description)
- A simple attack animation
- Unity-ready code defining the object’s functionality

## What Was Done

- ✅ **Prompt + sketch input** via Gradio interface
- ✅ **Sprite generation** using ControlNet + PixelArt SDXL
- ❌ **Unity C# code generation** attempted via StarCoder/Gwen2 but not successful
- 🔍 **Flavor text and animation generation** were researched but not implemented

## ⚠Challenges

- Code generation proved difficult without structured constraints
- LLMs often reproduced prompts verbatim or generated invalid code
- Fine-tuning and stricter templates likely needed for consistent Unity integration


See the full [Notion article](https://woozy-caraway-36e.notion.site/Talk-and-Chalk-Item-Generation-Capita-Selecta-1b6bc1a1c780803d9444f4b292accc52?pvs=74) 

