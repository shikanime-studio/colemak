# colemak

Nix modules for Colemak keyboard layout (NEUI cluster optimization).

**Language:** Nix

**Structure:** `modules/{helix,zed-editor,neovim}.nix` — editor configs; `flake.nix` — exposes all

**Commit style:** Plain-text capitalized title, no prefix. Body with labels: `Design:`, `Related:`, `Closes #`.

**Stack:** 1 commit == 1 PR via ghstack. Amend + `ghstack` to resubmit. `ghstack land` on head PR to land stack. Never `gh pr merge`. Never force-push.

**Protect `main`:** 1 review, linear history, signed commits, squash+rebase only.

*Apache-2.0. Maintain cross-platform parity*
