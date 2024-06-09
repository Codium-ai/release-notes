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
### May 30, 2024
![](./assets/title.png){ class="no-border";}
</div>
</div>

<!-- VSCode -->

<div markdown class="bg-black">
<h3 markdown class="top-left">
**[<b class="white">:simple-visualstudiocode:</b> Codiumate<b class="green">:</b>VSCode | v0.9][def]**
</h3>

<div class="centered" markdown>
We're excited to unveil Codiumate v0.9, featuring a **redesigned interface**, enhanced project indexing, and intuitive navigation with new shortcuts like `@` and the + button. You can now add context to your requests with code snippets, files, folders, or **entire projects**, and activate the new coding-agent with a click for expert assistance. 

The update also incorporates **GPT-4o** for smarter test generation and adds the **Vitest framework** to our supported testing frameworks for JavaScript and TypeScript. 

**[Read More](./versions/latest/vscode.md)**

### **🤩 See how it looks:**

#### Choose focus
![](./versions/latest/current-file.gif){width=50%}

#### Add Extra Context
![](./versions/latest/extra-context.gif){width=50%}


</div>

<div class="left-padding" markdown>


</div>
</div>


<!-- COVER-AGENT -->

<div markdown class="bg-blue">
<h3 markdown class="top-left">

**[<b class="white">:simple-visualstudiocode:</b> Cover<b class="green">-</b>Agent | v0.1]()**

</h3>

<div class="centered" markdown>
# Introducing [**Cover-Agent**](https://github.com/Codium-ai/cover-agent)!

### We're excited to announce  [**Cover-Agent**](https://github.com/Codium-ai/cover-agent) - our new open-source tool to simplify increasing test coverage!

![type:video](https://www.youtube.com/embed/fIYkSEJ4eqE?si=vp5SnbQOPJp9Ak51){: style='width: 50%; height: 25.172vw'}


<div class="grid cards" markdown>

-   🔍 Boost Your Tests

    ---

    Say goodbye to the monotony of managing test coverage. With Cover-Agent, you can effortlessly handle essential tasks, starting with regression tests, to ensure your codebase remains robust and well-tested.

-   🧠 Advanced AI

    ---

    Inspired by Meta’s TestGen-LLM, Cover-Agent ensures generated tests compile, run properly, and add value.

-   🌟 Contribute and Collaborate

    ---

    As an open-source project, we invite you to contribute and help us enhance  [**Cover-Agent**](https://github.com/Codium-ai/cover-agent). Your input is invaluable in refining this tool to meet the real-world needs of developers like you.

</div>

Discover more about Cover-Agent in our detailed [**blog post**](https://www.codium.ai/blog/we-created-the-first-open-source-implementation-of-metas-testgen-llm/)

[Explore Cover-Agent](https://github.com/Codium-ai/cover-agent){ .md-button }


</div>

</div>


<!-- JB -->

<div markdown class="bg-black">
<h3 markdown class="top-left">

**[<b class="white">:simple-jetbrains:</b> Codiumate<b class="green">:</b>JetBrains | v0.7.38](./versions/latest/jetbrains.md)**
</h3>

![type:video](https://www.youtube.com/embed/EjrgjBOLPGc?si=6ls9f4MMLuOKcayn){ align=right}


<div class="centered" markdown>
# **Full Chat** support!
</div>

<div class="left-padding" markdown>

Codiumate plugin now supports comprehensive chat functionalities in JetBrains! This includes workspace mode, file mode, and free chat, supporting all commands to streamline your coding sessions.

**What can you do with Codiumate Chat?**

📄 File Mode - Choose any code in your project and explore the different commands - explain the code, improve the quality, write tests, add docstring, and more.

🗂️ Workspace Mode - Choose a changeset (local or committed changes) and improve your code before you commit or push - get a recap of your changes, find and fix issues in your diff, get a code review, update the changelog, and more.

💬 Free Chat - Chat about any code-related subject, with your code as context.


**[Learn more about Codiumate Chat](https://codiumate-docs.codium.ai/chat/)**

</div>
</div>

<!-- PR-Agent -->

<div markdown class="bg-blue">

<h3 markdown class="top-left">

**[<b class="white">:fontawesome-solid-robot:</b> PR<b class="green">-</b>Agent | v0.22](./versions/latest/pr-agent.md)**
</h3>

<div markdown class="centered">


<div class="left-padding" markdown>

### Apply Code Suggestion with **One Click**

In the latest PR-Agent Pro we've introduced a new way of improving your code:

You can now Interactively convert a specific suggestion to a committable one, with just checking the check-box inside each suggesion!


---

### **Chrome Extension** v1.15 🕵️‍♂️


![type:video](https://www.youtube.com/embed/v9bJ1frtPcg?si=8dgarF21BWqKBjr9){ align=left}


<div class="left-padding" markdown>

### The new PR-Agent Chrome Extension version now added 2 new features:

- PR-Agent **Filters** - Easily switch between PR-Agent comments, Non-PR-Agent comments, and all comments to focus on what matters.

- **Enhanced** Code Suggestions - Use the new quote button to add specific code suggestions as comments and tag your teammates for seamless collaboration.


<div markdown class="centered">
**[Download Chrome Extension](https://chromewebstore.google.com/detail/pr-agent-chrome-extension/ephlnjeghhogofkifjloamocljapahnl)**
</div>

</div>
</div>
</div>


<!-- FOOTER -->

<!-- What's cooking -->

<div markdown class="bg-black">

<h3 markdown class="top-left">


</h3>


<div class="centered" markdown>
# What's **Cooking**?

<div class="left-padding" markdown>
!!! jetbrains "Codiumate:JetBrains >> Code Completion"
    Code Completion is already available for Codiumate:VSCode, and we're diligently integrating it into Codiumate:JetBrains for an enhanced coding experience. 
    
    Our Code Completion feature is designed to expedite your coding process by intelligently analyzing code context and intentions. It seamlessly suggests relevant code snippets, allowing you to swiftly accept them with a simple tab click.

    **[Read More about Code Completion](https://codiumate-docs.codium.ai/code-completion/)**

!!! code "Codiumate:Test >> Improved test generation"
    These days we're working on improving the test quality - starting from a better context selection, project indexing for better mocking and learning from specific language best practices.

</div>
</div>

</div>


<!-- FOOTER -->

<div class="centered" markdown>
### Read full Release Notes:


<div class="grid cards" markdown>

- [<b class="white">:simple-jetbrains:</b> **<b class="green">Codiumate<b class="purple">:</b>JetBrains**</b>](./versions/latest/jetbrains.md)
- [<b class="white">:simple-visualstudiocode:</b> **<b class="green">Codiumate<b class="purple">:</b>VSCode**</b> ][def]
- [<b class="white">:fontawesome-solid-robot:</b> **<b class="green">PR<b class="purple">-</b>Agent**</b> ](./versions/latest/pr-agent.md)


</div>
</div>
</div>


[def]: ./versions/latest/vscode.md