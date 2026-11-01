---
name: EigenReel-skill 
description: Turns a user's idea into a high-quality mathematical visualization, adhering to EigenReel's contribution policies and style guide. Use whenever the user mentions EigenReel.
---

# Contribution policies

A piece is two files, entries/.js and its explanation entries/.md (and, for WebAssembly, entries/.wasm with its source under sources//). It reaches the feed as a pull request to the registry, github.com/EigenReel/registry, from your own fork. EigenReel never pushes or opens anything for you, and holds no GitHub access.

Contributions must adhere to our conventions, including:
- an explanation node about the mathematics captured in the visualization (this is an indication of whether the visualization is interactive, and whether this is for mobile, desktop, or both
- an indication of whether users should tap to interact on mobile
- a color palette
- tags

Tags should be suitably general (e.g. "calculus", "algebraic geometry", "geometric group theory") and not hyperspecific (like "Type IV cubic surfaces"). If you're adding a new tag for a contributed visual, you should have an expectation that many other visuals will be created (not just by you) which share that tag.

Contributions should be of the highest quality (as judged by the moderators)

AI-assisted contributions are completely accepted and contributors are encouraged to use AI to fit their visualization to our template and to debug

Contributors agree that anything they post can be used by anyone for anything (or something like this?)

# Style guide

Title and description should not appear in the frame

In "feed mode" the visual should have zero or minimal text. In "interact mode" there can be more text.
