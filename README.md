# Commons Preservation License (CPL) v1.0

A share‑alike license for keeping knowledge, code, data, and AI‑derived systems
open and freely accessible.

---

## What is CPL?

The Commons Preservation License (CPL) is designed for people who want to share
useful work freely while preserving the same freedoms for everyone downstream.

CPL allows people to:

- Use the work
- Learn from it
- Modify it
- Share it
- Train AI on it

CPL requires that:

- Derivative works remain under CPL
- Source code (or equivalent “source” form) remains publicly available
- AI models trained on CPL‑covered work remain open
- The work is not enclosed behind proprietary or paywalled access barriers
- The work and derivatives are not used for commercial purposes

---

## How to use CPL in your project

Using CPL means two simple things:

- You include the CPL license with any copy of the work you distribute.
- You follow CPL’s rules when you modify, redistribute, or train AI on
  CPL‑covered work.

You do **not** have to register anywhere or link to any specific Git hosting
service for CPL to apply. The license travels with the work itself.

### 1. Include the license with your work

1. Add a `LICENSE` (or `LICENSE.txt` / `LICENSE.md`) file next to your source
   code, dataset, or model files.
2. Replace the placeholders in the license text:
   - `[YEAR]` → current year
   - `[AUTHOR]` → your name, handle, or organization
3. When you distribute your work (source archive, binary, model weights,
   dataset, etc.), make sure the `LICENSE` file is shipped in the same package,
   installer, or distribution bundle.

### 2. Make the license easy to find

In your README or main documentation, add a short section that points to the
local license file:

```md
## License

Commons Preservation License (CPL) v1.0  
See the LICENSE file included with this software for the full terms.
```

This works the same way whether your project is on GitHub, another forge,
a private server, or handed around as a zip/tarball.

### 3. When you build on CPL‑covered work

If you create a derivative of CPL‑covered work (modified code, a fork, a model
trained on CPL data, etc.) and distribute it:

- Keep your derivative licensed under **CPL v1.0** (or a later CPL version,
  if the original explicitly allows that).
- Include a `LICENSE` file with your distribution, containing the CPL text.
- Preserve attribution to the original author(s) where reasonable.
- Do **not** use the original work or your derivative for commercial purposes.
- If you train AI models on CPL‑covered work, keep the model, weights, and
  necessary training details openly available under terms compatible with CPL.

A minimal notice in a derivative project could look like:

```md
Based on work licensed under the Commons Preservation License (CPL) v1.0.  
This derivative is also distributed under CPL v1.0. See the LICENSE file for details.
```

### 4. Optional short reference text

If you want a compact snippet for source headers, splash screens, or
about dialogs:

```text
Licensed under the Commons Preservation License (CPL) v1.0.
The full license text is included in the LICENSE file distributed with this software.
```

---

## Files in this repository

- `LICENSE` — standard plain license file
- `LICENSE.md` — Markdown‑formatted version
- `LICENSE.txt` — plain text version

---

## Why CPL exists

Knowledge should be free. Tools should serve people, not profits.

CPL is meant to protect shared work from enclosure while still encouraging
learning, experimentation, and original innovation. It does not forbid people
from creating new things or benefiting from their own contributions. It is
meant to ensure that if someone builds directly on CPL‑covered work, the same
freedoms are preserved for others.

---

## Short boilerplate for projects using CPL

Projects using CPL may use the following short notice:

```text
Licensed under the Commons Preservation License (CPL) v1.0.
The full license text is included in the LICENSE file distributed with this software.
```
