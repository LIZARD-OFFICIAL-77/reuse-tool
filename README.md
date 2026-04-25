<!--
SPDX-FileCopyrightText: 2017 Free Software Foundation Europe e.V. <https://fsfe.org>
SPDX-FileCopyrightText: 2026 LIZARD-OFFICIAL-77 <lizard.official.77@gmail.com>

SPDX-License-Identifier: CC-BY-SA-4.0
-->

# lizreuse

reuse-tool with my patches to it, because the original pissed me off very badly.

- Added .reuse/ignore support just like .gitignore
- If a file supports multi-line it now ALWAYS supports single-line
- Added support for dockerfiles as long as they're named either Dockerfile.SOMETHING or SOMETHING.Dockerfile
- Removed forced newlines inserted automatically between header and code (will be added as a CLI **option** later)