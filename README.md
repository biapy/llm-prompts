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
- [Designing tools for developers means designing for LLMs too @ encore](https://encore.dev/blog/llm-instructions).
  - [encore's TypeScript LLM instructions @ encore's GitHub](https://github.com/encoredev/encore/blob/main/ts_llm_instructions.txt).
  - [encore's Go LLM instructions @ encore's GitHub](https://github.com/encoredev/encore/blob/main/go_llm_instructions.txt).
- [Principled Instructions Are All You Need for Questioning LLaMA-1/2, GPT-3.5/4](https://arxiv.org/pdf/2312.16171).

### Courses

- [Modern-Day Oracles or Bullshit Machines ?](https://thebullshitmachines.com/).
- [Prompt Engineering Guide](https://www.promptingguide.ai/)
  ([Prompt Engineering Guide @ GitHub](https://github.com/dair-ai/Prompt-Engineering-Guide)).
- [Neural Networks: Zero to Hero @ GitHub](https://github.com/karpathy/nn-zero-to-hero).
- [Deep Dive into LLMs like ChatGPT @ Andrej Karpathy's YouTube](https://www.youtube.com/watch?v=7xTGNNLPyMI).

<!-- CSpell:ignore Andrej Karpathy -->

### Resources

- [Open LLM List homepage](https://openllmlist.com/).

### Miscellaneous

- [IndyDevDan @ YouTube](https://www.youtube.com/@indydevdan):
  - [Meta Prompting with o1, o1 Pro Mode, and ChatGPT Pro (Compute on Compute)
    @ IndyDevDan's YouTube](https://www.youtube.com/watch?v=yZGb9-Z9DG0).
    - [Meta Prompting @ disler's GitHub Gist](https://gist.github.com/disler/29ff18823670098c26fa370ad802fa96).
- [Best Prompt Techniques for Best LLM Responses @ Jules S. Damji](https://medium.com/the-modern-scientist/best-prompt-techniques-for-best-llm-responses-24d2ff4f6bca).
- [mdx-prompt: Composable LLM Prompts with JSX @ Ed Spencer's Blog](https://edspencer.net/2025/2/3/mdx-prompt-composable-prompts-with-jsx).
  - [mdx-prompt @ GitHub](https://github.com/edspencer/mdx-prompt)
- [You are using Cursor AI incorrectly... @ Geoffrey Huntley](https://ghuntley.com/stdlib/).
- [How I Won Singapore’s GPT-4 Prompt Engineering Competition
  @ towards data science](https://towardsdatascience.com/how-i-won-singapores-gpt-4-prompt-engineering-competition-34c195a93d41/#8f6a).
- [Je ne code plus, Cursor et ChatGPT le font à ma place ! 🤯 @ YoanDev :fr:](https://www.youtube.com/watch?v=k38deocrsDw).
- [My LLM codegen workflow atm @ Harper Reed's Blog](https://harper.blog/2025/02/16/my-llm-codegen-workflow-atm/).
- [How I program with LLMs @ Blog: David Crawshaw](https://crawshaw.io/blog/programming-with-llms).

<!-- CSpell:ignore disler Damji YoanDev codegen Crawshaw -->

## 🙇 Author

### Pierre-Yves LANDURÉ

- Homepage: [Biapy help-desk](https://howto.biapy.com/)
- Github: [@biapy](https://github.com/biapy)

<!-- CSpell:ignore Landuré Biapy -->

## ➤ License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
