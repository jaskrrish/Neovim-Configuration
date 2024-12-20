# 🛠️ My Neovim Configuration

Welcome to my Neovim configuration repository! This setup is designed to enhance productivity and provide a smooth coding experience with modern plugins and beautiful aesthetics.

---

## 📖 Description

This is my personal Neovim configuration written in **Lua**, optimized for **performance** and **customizability**. It features a modular structure with organized files for settings, plugins, and customizations.

---

## 🧰 Requirements

- **Neovim** version `0.8+` (for Lua support).
- **Git** for plugin management.
- **Node.js**, **Python**,**JavaScript**, **TypeScript** and **Go** (for some LSP servers and plugins).

---

## 🚀 Installation

1. Clone the repository into your Neovim configuration directory:

   ```bash
   git clone https://github.com/your-username/your-repo-name ~/.config/nvim
   ```

2. Open Neovim and run the following to install plugins:

   ```bash
   :PackerSync
   ```

3. Restart Neovim, and you’re all set! 🎉

---

## 🌲 Configuration Structure

The configuration is modular and organized into the following structure:

```lua
lua
└── jaskrrish
    ├── core
    │   ├── colorscheme.lua   -- Theme settings
    │   ├── keymaps.lua       -- Custom keybindings
    │   └── options.lua       -- General settings and options
    ├── plugins
    │   ├── alpha.lua         -- Dashboard plugin
    │   ├── autopairs.lua     -- Auto-pairing for brackets
    │   ├── comment.lua       -- Commenting utility
    │   ├── floaterminal.lua  -- Floating terminal configuration
    │   ├── gitsigns.lua      -- Git integration
    │   ├── lsp
    │   │   ├── lspconfig.lua -- LSP server configurations
    │   │   ├── lspsaga.lua   -- Enhanced LSP UI
    │   │   ├── mason.lua     -- LSP server management
    │   │   └── null-ls.lua   -- Linters and formatters
    │   ├── lualine.lua       -- Status line configuration
    │   ├── nvim-cmp.lua      -- Autocompletion setup
    │   ├── nvim-tree.lua     -- File explorer setup
    │   ├── telescope.lua     -- Fuzzy finder
    │   └── treesitter.lua    -- Syntax highlighting and parsing
    └── plugins-setup.lua      -- Plugin manager and setup
```

---

## 🎨 Customization

To customize this configuration, modify the Lua files in the `~/.config/nvim` directory. Key files to explore:

- `lua/jaskrrish/core`: Contains core settings like options, keymaps, and colorscheme.
- `lua/jaskrrish/plugins`: Includes configurations for individual plugins.
- `lua/jaskrrish/plugins/lsp`: Dedicated settings for LSP, formatters, and linters.

---

## 🛠️ Troubleshooting

- **Plugins not loading?** Run `:PackerSync` to ensure all plugins are installed.
- **Errors on startup?** Check Neovim’s logs: `:help message`.

---

## 🌟 Contributing

Feel free to fork this repository, suggest improvements, or submit pull requests to make this configuration even better!

---

## 📜 License

This configuration is open-source and available under the [MIT License](LICENSE).

### How to Use

- Replace `your-username` and `your-repo-name` with your GitHub username and repository name.
- Add screenshots of your setup to the specified placeholders.
- Update descriptions for plugins or files if needed.

Let me know if you'd like further adjustments!
