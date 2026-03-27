# Kindle-Transformation
Elegantly transform Kindle exported HTML notes into beautifully formatted Obsidian markdown files.

# Kindle Transformation for Obsidian 📖✨

Elegantly transform your Kindle exported HTML notes into beautifully formatted Obsidian markdown files. 

This plugin is designed with a focus on aesthetics, smooth user experience (UI/UX), and highly customizable note formatting.

## ✨ Key Features

- **Drag & Drop Interface**: A premium, macOS-inspired UI. Simply click or drag your Kindle `.html` file into the modal to instantly generate your notes.
- **Custom Callout Mapping**: Take full control of your highlights! Map default Kindle colors (Yellow, Aqua, Pink, Orange, Blue, Green) to any Obsidian Callout type you prefer (e.g., `quote`, `important`, `question`, `attention`, `success`).
- **Nested Blockquotes**: Highlights are automatically formatted as nested blockquotes (`> > `) to create a beautiful visual hierarchy, distinguishing the book's text from your personal notes.
- **Smart Formatting**: Automatically cleans up excessive line breaks and structurally organizes your notes by chapters. 
- **Auto-Routing**: Specify a default folder for your imported notes. If the folder doesn't exist, the plugin will automatically create it for you.

## 🚀 How to Use

1. Export your notes from the Kindle app (iOS/Android) to your email and download the `.html` file.
2. Open Obsidian and click the **Book** (📖) icon in the left ribbon (or use the Command Palette: `Run Kindle Transformation`).
3. Drag and drop your `.html` file into the upload box.
4. Click **Start Transformation**. Your perfectly formatted Markdown note is ready!

## ⚙️ Settings

Go to `Settings` -> `Kindle Transformation` to configure:
- **Save Folder**: Define where your new notes should be saved (e.g., `Reading/Kindle`). Leave it blank to save in the root vault.
- **Callout Color Mapping**: Type in your preferred Obsidian callout name for each Kindle highlight color.

## 🙏 Credits

This plugin is deeply inspired by and upgraded from the excellent work of [l2xu/kindle_html_importer](https://github.com/l2xu/kindle_html_importer). Special thanks to the original author for providing the foundational logic for parsing Kindle HTML exports!
