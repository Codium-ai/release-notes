---
hide:
  - navigation
  - toc
title: CodiumAI Release Notes Digest
description: Latest release notes of Codiumate and PR-Agent
---
<div class="content" markdown>
<div class="bg-clear" markdown>
<div markdown class="centered">

![](./assets/title.png){ class="no-border";}

### August 26, 2024

</div>

<!-- PR-Agent 
:fontawesome-solid-robot:
-->

<div markdown class="bg-blue">
<h3 markdown class="top-left">

**[<b class="white"></b> PR<b class="green">-</b>Agent | v0.23](./versions/latest/pr-agent.md)**
</h3>

<div markdown class="centered">

# PR-Agent **Chrome Extension built-in Commands**


<div class="left-padding" markdown>

### 

Run PR-Agent commands **directly from the comment section of your pull request page!**

Use our newest PR-Agent Chrome Extension version to make your workflow smoother and more efficient.

##
<div markdown class="centered">
!!! imporant "Free feature!"
    This feature is **available for free** to all open-source projects!

    **Get PR-Agent Chrome Extension from the [<u>Chrome web store.</u>](https://chromewebstore.google.com/detail/ephlnjeghhogofkifjloamocljapahnl?hl=en)**
</div>
</div>

##
**For a full demonstration, check out our video guide:**

![type:video](https://www.youtube.com/embed/gT5tli7X4H4?si=84cs1O2bM5unLAWf){: style='width: 60%; height: 30.172vw'}

<div class="grid cards" markdown>
- [Read <b class="green">PR<b class="purple">-</b>Agent</b> full release notes](./versions/latest/pr-agent.md)
</div>

</div>
</div>


<!-- VSCode
:simple-vscode:
-->

<div markdown class="bg-black">
<h3 markdown class="top-left">

**[<b class="white"></b> Codiumate<b class="green">:</b>VSCode | v0.9.13](./versions/latest/vscode.md)**
</h3>

<div markdown class="centered">

# **Codiumate:Chat:** Focus behavior now more intuitive!

<div class="left-padding" markdown>

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
![TestGeneration](./assets/gifs/28.8.2024FocusDefault.gif)
</div>

##
**Codebase Selection:** For Enterprise RAG users, you can now **turn RAG usage on or off!**

If you don't want to use your entire codebase as context and look for something more specific, simply turn RAG off from the context selection menu.

</div>

<div class="centered" markdown>
<div class="grid cards" markdown>
- [Read <b class="green">Codiumate<b class="purple">:</b>VSCode</b> full release notes ](./versions/latest/vscode.md)
</div>
</div>
</div>
</div>


<!-- JB
:simple-jetbrains:
-->

<div markdown class="bg-blue">
<h3 markdown class="top-left">

**[<b class="white"></b> Codiumate<b class="green">:</b>JetBrains | v0.9](./versions/latest/jetbrains.md)**
</h3>

<div class="centered" markdown>

# **Task Planner Alpha**


<div class="left-padding" markdown>

We’ve introduced **Task planner alpha** in Codiumate Jetbrains!

Transform your tasks and TO DOs into structured, actionable plans with ease.

Simply select code snippets, describe your tasks, and Task planner generates a structured, step-by-step plan for you.

</div>

<div class="centered" markdown>

**For a full demonstration, check out our video guide:**

![type:video](https://www.youtube.com/embed/9dH3pUzsbig?si=8WG9Mu8bymDUg1C7){: style='width: 60%; height: 30.172vw'}

<div class="grid cards" markdown>
- [Read <b class="green">Codiumate<b class="purple">:</b>JetBrains</b> full release notes](./versions/latest/jetbrains.md)
</div>

</div>
</div>
</div>
</div>


<!-- FOOTER -->

<!-- What's cooking -->
<!-- 
<div markdown class="bg-blue">

<h3 markdown class="top-left">


</h3> -->


<!-- <div class="centered" markdown>
# What's **Cooking**?

<div class="left-padding" markdown>
!!! chat "Codiumate >> Chat History"
    We’re adding chat history features so you can easily access your previous conversations. We’re also enhancing the current work with threads to make managing and navigating through them more efficient and user-friendly.

!!! code "Codiumate:Test >> Improved test generation"
    These days we're working on improving the test quality - starting from a better context selection, project indexing for better mocking and learning from specific language best practices.

</div>
</div> -->
<!-- FOOTER -->

</div>
</div>