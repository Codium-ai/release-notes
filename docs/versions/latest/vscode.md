---
hide:
  - navigation
  - toc
title: Codiumate VScode Release Notes
subtitle: Codiumate plugin for JetBrains v0.7.30 Release Notes
---
#
<div class="centered" markdown>
![](../../assets/vscode.png){ class="no-border"}

### v0.9.14 | August 29, 2024

<div class="content" markdown>
<div class="bg-blue" markdown>
<div class="left-padding" markdown>

###
# **Codiumate:Chat:** Focus behavior now more intuitive!

Use Codiumate:Chat faster and more intuitively: **Focus is now your currently open file by default!**

When Codiumate:Chat is opened, it will automatically Focus on the file currently opened in your IDE.

##
**Automatic Secondary Focus:** Your Secondary Focus will automatically set as either:

1. **Selected Lines:** If you've highlighted specific lines in the file, these will be set as your Secondary Focus.
2. **No Selected Lines:** If no lines were selected, Codiumate will focus on the first component (like a function or class) within the file.
3. **No Component Found:** If no component is identified, Codiumate will focus on the entire file when possible.
4. **Fallback Option:** If none of the above criteria are met, Codiumate will prompt you to manually select lines to focus on.

## 
**Focus Lock mechanism:** As you navigate through different files in your IDE, Codiumate automatically updates its focus to match the current file - unless you've already started a conversation.

This keeps Codiumate in sync with your workflow until you're ready to lock in your focus for a specific conversation.

##
<div markdown class="centered">
![TestGeneration](../../assets/gifs/28.8.2024FocusDefault.gif)
</div>

##
**Codebase Selection:** For Enterprise RAG users, you can now **turn RAG usage on or off!**

If you don't want to use your entire codebase as context and look for something more specific, simply turn RAG off from the context selection menu.

#
# All-around **UI improvements**

We’ve been hard at work refining your experience in VSCode! In this release, we’ve introduced several key improvements:

- **New placement for the code snippet button** to enhance usability and allow easier access.
- **Labeled buttons** and refreshed **color schemes** for a cleaner, more intuitive UI.
- Upgraded **error messages** with clearer, more actionable instructions.

---

<div class="centered" markdown>

<div class="grid cards" markdown>
- ### [Full **CodiumAI** Release Notes Digest](../../index.md)
</div>

</div>

</div>
</div>
</div>
</div>
