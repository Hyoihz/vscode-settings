# 🛠️ My VSCode Development Environment

## 📄 Description
Highly customized VSCode configuration optimized for web development with Vim-inspired workflow.

## 📂 Repository Contents
- `settings.json`: VSCode user settings
- `keybindings.json`: Custom keyboard shortcuts
- `style.css`: Custom UI styling
- `script.js`: Additional UI customizations
- `fonts/`: Custom typography resources

## 🚀 Setup Steps
1. Copy `settings.json`:
   - **Windows**: `%APPDATA%\Code\User\`
   - **macOS**: `~/Library/Application Support/Code/User/`
   - **Linux**: `~/.config/Code/User/`

2. Copy `keybindings.json`:
   - **Windows**: `%APPDATA%\Code\User\`
   - **macOS**: `~/Library/Application Support/Code/User/`
   - **Linux**: `~/.config/Code/User/`

3. Install extensions:
   - [Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
   - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
   - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
   - [Codeium](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium)
   - [Custom CSS & JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)
   - [Catppuccin Theme](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc)
   - [JetBrains Icon Theme](https://marketplace.visualstudio.com/items?itemName=chadalen.vscode-jetbrains-icon-theme)
   - [Fluent Icons](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.fluent-iconsS )

4. Adjust custom CSS paths:
   ```json
   "vscode_custom_css.imports": [
     // Windows path
     "file:///C:/Users/YourUsername/Desktop/style.css",
     
     // macOS path
     "file:///Users/YourUsername/Desktop/style.css",
     
     // Linux path
     "file:///home/YourUsername/Desktop/style.css"
   ]
   ```

5. Update Live Server browser path:
   ```json
   "liveServer.settings.AdvanceCustomBrowserCmdLine": "PATH_TO_YOUR_PREFERRED_BROWSER"
   ```

6. Install custom fonts from `/fonts/`

## 🎨 Key Features
- **UI**: Catppuccin Mocha theme, minimalist design
- **Editor**: Relative line numbers, format on save
- **Vim**: Custom leader key, extensive keybindings
- **Workflow**: Auto-import management, Codeium AI
- **Browser**: Live Server with custom browser support

## 📝 Notes
Personalized configuration. Continuously evolving.