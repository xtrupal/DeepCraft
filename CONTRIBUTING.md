# Contributing to the Deepcraft-Food

Thank you for helping build the first open-source Minecraft Food item image dataset! This guide explains how to contribute images and ensure your contributions align with the project’s goals.

## How to Contribute

1. **Fork the Repository**

   - Click the "Fork" button on the GitHub repository page to create your own copy.

2. **Clone Your Fork**

   - Run `git clone https://github.com/YOUR-USERNAME/minecraft-image-dataset.git` to download your fork locally.

3. **Add Images**

   - Place images in the correct folder under `/dataset/` (e.g., `/dataset/food/apple/`).
   - If the item category or item doesn’t have a folder, create one (e.g., `/dataset/food/Cookie/`).
   - Follow the [Image Guidelines](#image-guidelines) below.

4. **Commit Your Changes**

   - Use clear, descriptive commit messages. Examples:
     - `Add apple_002.jpg to food/apple`
     - `Add golden_carrot images`
     - `Create food/cookie folder with initial images`

5. **Push to Your Fork**

   - Run `git push origin main` to upload your changes to your GitHub fork.

6. **Submit a Pull Request (PR)**
   - Go to the original repository and click "New Pull Request."
   - Compare your fork’s branch to the main repo’s `main` branch.
   - Provide a clear title (e.g., “Add golden carrot images”) and a short description of what you added.

## Image Guidelines

To keep the dataset consistent and usable, please follow these rules:

- **Format**: `.jpg` only (no `.png`, `.jpeg`, or `.webp`).
- **Resolution**: Minimum 128x128 pixels; higher resolutions (e.g., 256x256) are welcome if clean and centered.
- **Naming**: Use `itemname_001.jpg`, `itemname_002.jpg`, etc. (e.g., `apple_001.jpg`).
- **Quality**:
  - Use official Minecraft item icons, clean in-game screenshots, or high-quality renders.
  - Ensure items are centered with a transparent or solid background (preferably transparent).
  - Avoid watermarks, UI elements, or unrelated textures.
- **Categories**:
  - This repo is only for **food items**. Carefully place images inside `/dataset/food/<item_name>/`.

## Examples

- Good: `/dataset/food/apple/apple_001.jpg` (128x128, clean icon of an apple).
- Bad: `/dataset/food/apple/random_apple.png` (wrong format, unclear name).

## Where to Find Images

- **Official Textures**: Extract from Minecraft resource packs (e.g., `assets/minecraft/textures/item/` in the game’s `.jar` file).
- **Screenshots**: Take clean in-game screenshots with a transparent or solid background.
- **Minecraft Wiki**: Use item images from the [Minecraft Wiki](https://minecraft.fandom.com/wiki/Minecraft_Wiki) (check licensing; prefer MIT-compatible sources).
- **Create Your Own**: Use tools like Blender or Photoshop to render high-quality item images.

## Code of Conduct

- Be respectful and collaborative.
- No memes, offensive content, or unrelated images.
- If unsure about an image’s quality or licensing, ask in the PR or an issue.

## Questions?

- Open an issue on the GitHub repo for questions or suggestions.
- Check the [README.md](README.md) for the project’s vision and structure.

Thank you for making this dataset awesome!
