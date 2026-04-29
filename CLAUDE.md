# CLAUDE.md

## Git 协作规范

1. **分支命名**：新功能分支必须以 `feat/` 开头，修复分支以 `fix/` 开头，后跟简短英文描述（如 `feat/user-login`）。
2. **Commit 规范**：严格遵守 Conventional Commits 格式：`<type>(<scope>): <subject>`，如 `feat(auth): add JWT validation`。
3. **提交前检查**：每次 commit 前，必须运行 `npm run lint` 修复代码格式，确保无报错。
4. **禁止行为**：严禁直接向 `main` 或 `master` 分支推送代码。
