# Copilot Instructions for Conventional Commits with Gitmoji

## Commit Message Format

Generate commit messages following the
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) standard.
This ensures consistency in the commit history and enables automated changelog generation.

### Commit Message Structure

- Use present tense for the description.
- Limit the subject line (first line) to 100 characters.
- Don't end the subject line with a period.
- Use the imperative mood in the subject line.
- Wrap the body at 72 characters.
- Use the body to explain what and why compared to how.
- A relevant Gitmoji **must** precede each commit message description.
- The commit message should adhere to the following structure:

  ```text
  <type>(optional scope): <Gitmoji> <description>

  [optional body]

  [optional footer(s)]
  ```

- The commit message might include a brief summary of the changes made
  in the optional body.
- The description should be clear and concise,
  providing enough context to understand the change.

### Example Commit Message

```text
feat(user-auth): ✨ add login functionality

Add a custom User source to Symfony's security configuration to handle
login requests.
```

### Commit Types

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that don't affect the meaning of the code
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `build`: Changes that affect the build system or external dependencies
- `ci`: Changes to CI configuration files and scripts

### Available Gitmoji Types

To standardize the use of Gitmojis,
here are some common Gitmojis and their meanings:

- 🎨 `art`: Improve structure / format of the code.
- ⚡ `zap`: Improve performance.
- 🔥 `fire`: Remove code or files.
- 🐛 `bug`: Fix a bug.
- 🚑️ `ambulance`: Critical hotfix.
- ✨ `sparkles`: Introduce new features.
- 📝 `memo`: Add or update documentation.
- 🚀 `rocket`: Deploy stuff.
- 💄 `lipstick`: Add or update the UI and style files.
- 🎉 `tada`: Begin a project.
- ✅ `white_check_mark`: Add, update, or pass tests.
- 🔒️ `lock`: Fix security issues.
- 🔐 `closed_lock_with_key`: Add or update secrets.
- 📦️ `package`: Release / Version tags.
- 📈 `chart_with_upwards_trend`: Add or update analytics or track code.
- ♻️ `recycle`: Refactor code.
- ➕ `heavy_plus_sign`: Add a dependency.
- ➖ `heavy_minus_sign`: Remove a dependency.
- 🔧 `wrench`: Add or update configuration files.
- 🔨 `hammer`: Add or update development scripts.
- 🌐 `globe_with_meridians`: Internationalization and localization.
- ✏️ `pencil2`: Fix typos.
- 💩 `poop`: Write bad code that needs improvement.
- ⏪️ `rewind`: Revert changes.
- 🔀 `twisted_rightwards_arrows`: Merge branches.
- 📦️ `package`: Add or update compiled files or packages.
- 👽️ `alien`: Update code due to external API changes.
- 🚚 `truck`: Move or rename resources (e.g.: files, paths, routes).
- 📄 `page_facing_up`: Add or update license.
- 💥 `boom`: Introduce breaking changes.
- 🍱 `bento`: Add or update assets.
- ♿ `wheelchair`: Improve accessibility.
- 🌱 `seedling`: Add or update seed files.
- 🚩 `triangular_flag_on_post`: Add, update, or remove feature flags.
- 🥅 `goal_net`: Catch errors.
- 💫 `dizzy`: Add or update animations and transitions.
- 🗑️ `wastebasket`: Deprecate code that needs cleaning up.
- 🛂 `passport_control`: Work on code relating to authorization, roles, and permissions.
- 🩹 `adhesive_bandage`: straightforward fix for a non-critical issue.
- 🧐 `monocle_face`: Data exploration/inspection.
- ⚰️ `coffin`: Remove dead code.
- 🧪 `test_tube`: Add a failing test.
- 🍻 `beers`: Write drunken code.
- 🔊 `loud_sound`: Add or update logs.
- 🔇 `mute`: Remove logs.
- 👥 `busts_in_silhouette`: Add or update contributors.
- 🚸 `children_crossing`: Improve user experience / usability.
- 🏗️ `building_construction`: Make architectural changes.
- 📱 `iphone`: Work on responsive design.
- 🤡 `clown_face`: Mock things.
- 🥚 `egg`: Add or update an easter egg.
- 🤖 `robot`: Add or update a code generator.
- 🧬 `dna`: Add or update mutation tests.
- 💡 `bulb`: Add or update comments in source code.
- 🧱 `bricks`: Infrastructure related changes.
- 🧑‍💻 `technologist`: Improve developer experience.

<!-- CSpell:ignore tada iphone -->

Refer to the [Gitmoji guide](https://gitmoji.dev/) for a full list of available
emojis and their purposes.

## Conclusion {#conventional-commit-conclusion}

By following these guidelines and applying the necessary tools,
you help create high-quality, user-friendly commit messages for your repository,
ensuring consistency and clarity in your project's history.

<!-- CSpell:ignore Gitmoji Gitmojis bento Symfony -->
