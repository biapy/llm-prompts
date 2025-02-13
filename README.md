# LLM Prompts

Collection of prompts for GitHub Copilot and other LLMs.

> prompting is actually not programming in English, it's programming in tokens.
>
> -- Ed Spencer, [mdx-prompt: Composable LLM Prompts with JSX](https://edspencer.net/2025/2/3/mdx-prompt-composable-prompts-with-jsx).

## 🧑🏻‍💻 Installation

1. Download the relevant prompts from `src/` folder.
2. Place the Markdown files in the project `.github` folder.
3. Configure Visual Studio Code GitHub Copilot extension to load the instructions
   from custom files:

   ```json
     "github.copilot.chat.codeGeneration.instructions": [
       {"file" : "${workspaceFolder}/.github/conventional-commits-with-gitmoji.mdx" }
     ],
   ```

<!-- CSpell:ignore gitmoji -->

## 🛠️ Tech Stack

- [MDX homepage](https://mdxjs.com/)
  ([MDX @ GitHub](https://github.com/mdx-js/mdx/)).
- [GitHub Copilot homepage](https://github.com/features/copilot).
- [GitHub Copilot @ Visual Studio's Marketplace](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot).
- [GitHub Copilot Chat @ Visual Studio's Marketplace](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat).
- [GitHub Copilot Chat in Visual Studio Code @ GitHub](https://github.com/microsoft/vscode-copilot-release).

## 🙇 Acknowledgements

- [Prompt engineering @ Anthropic](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview).
- [GitHub Copilot in VS Code @ Visual Studio Code Docs](https://code.visualstudio.com/docs/copilot/overview).
- [Master the core principles of prompt engineering with GitHub Copilot
  @ Visual Studio Code's GitHub](https://www.youtube.com/watch?v=hh1nOX14TyY).
- [mdx-prompt: Composable LLM Prompts with JSX @ Ed Spencer's Blog](https://edspencer.net/2025/2/3/mdx-prompt-composable-prompts-with-jsx).
  - [mdx-prompt @ GitHub](https://github.com/edspencer/mdx-prompt)
- [IndyDevDan @ YouTube](https://www.youtube.com/@indydevdan):
  - [Meta Prompting with o1, o1 Pro Mode, and ChatGPT Pro (Compute on Compute)
    @ IndyDevDan's YouTube](https://www.youtube.com/watch?v=yZGb9-Z9DG0).
    - [Meta Prompting @ disler's GitHub Gist](https://gist.github.com/disler/29ff18823670098c26fa370ad802fa96).
- [Designing tools for developers means designing for LLMs too @ encore](https://encore.dev/blog/llm-instructions).
  - [encore's TypeScript LLM instructions @ encore's GitHub](https://github.com/encoredev/encore/blob/main/ts_llm_instructions.txt).
  - [encore's Go LLM instructions @ encore's GitHub](https://github.com/encoredev/encore/blob/main/go_llm_instructions.txt).
- [Modern-Day Oracles or Bullshit Machines ?](https://thebullshitmachines.com/).
- [Open LLM List homepage](https://openllmlist.com/).
- [You are using Cursor AI incorrectly... @ Geoffrey Huntley](https://ghuntley.com/stdlib/).

<!-- CSpell:ignore disler -->

## 🙇 Author

### Pierre-Yves LANDURÉ

- Homepage: [Biapy help-desk](https://howto.biapy.com/)
- Github: [@biapy](https://github.com/biapy)

<!-- CSpell:ignore Landuré Biapy -->

## ➤ License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
