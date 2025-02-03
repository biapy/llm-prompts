# LLM Prompts

Collection of prompts for GitHub Copilot and other LLMs.

## 🧑🏻‍💻 Installation

1. Download the relevant prompts from `src/` folder.
2. Place the Markdown files in the project `.github` folder.
3. Configure Visual Studio Code GitHub Copilot extension to load the instructions
   from custom files:

   ```json
     "github.copilot.chat.codeGeneration.instructions": [
       {"file" : "${workspaceFolder}/.github/conventional-commits-with-gitmoji.md" }
     ],
   ```

<!-- CSpell:ignore gitmoji -->

## 🛠️ Tech Stack

- [GitHub Copilot homepage](https://github.com/features/copilot).
- [GitHub Copilot @ Visual Studio's Marketplace](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot).
- [GitHub Copilot Chat @ Visual Studio's Marketplace](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat).
- [GitHub Copilot Chat in Visual Studio Code @ GitHub](https://github.com/microsoft/vscode-copilot-release).

## 🙇 Acknowledgements

- [GitHub Copilot in VS Code @ Visual Studio Code Docs](https://code.visualstudio.com/docs/copilot/overview).
- [Master the core principles of prompt engineering with GitHub Copilot
  @ Visual Studio Code's GitHub](https://www.youtube.com/watch?v=hh1nOX14TyY)

## 🙇 Author

### Pierre-Yves LANDURÉ

- Homepage: [Biapy help-desk](https://howto.biapy.com/)
- Github: [@biapy](https://github.com/biapy)

<!-- CSpell:ignore Landuré Biapy -->

## ➤ License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
