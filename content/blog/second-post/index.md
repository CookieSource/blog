+++
title = "Dotfiles and a clean terminal"
date = 2025-09-12
description = "My terminal stack and a few dotfile tips."
[taxonomies]
tags = ["dotfiles", "terminal"]
[extra]
hot = true
+++

Current terminal setup:

- Shell: bash/zsh (depending on the box)
- Prompt: simple, fast, minimal
- Editor: `vim` for quick edits, VS Code for longer sessions

Small dotfile tips:

- Keep OS-specific bits in separate files and source them conditionally
- Prefer clear names over cleverness; future-you will thank you
- Version your dotfiles but avoid secrets in the repo

I’ll publish more concrete snippets as I go.

```bash
# list hidden files and colors
ls -la --color=auto

# quick prompt example
PS1='[\u@\h \W]$ '
```

```rust
// basic rust demo
fn greet(name: &str) {
    println!("hi, {}!", name);
}

fn main() {
    greet("cookiesource");
}
```

 
