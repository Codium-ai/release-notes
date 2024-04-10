<figure markdown="1">
![](../../assets/codium-logo.png){ class="no-border" width=200 }

![](../../assets/VSCode%20release%20notes.png){ class="no-border" width=780}
# March 28, 2024
### v.0.7.55
</figure>

## Add Context to Codiumate Chat

We're cooking up something exciting, and you'll hear about it soon. But in the meantime, we've introduced some really cool features that will enhance the existing ones and make them even more awesome! One of these enhancements includes... adding more context! 🍾

Codiumate chat now allows you to include more context when sending any command, ensuring you get better results. This context can be drawn from the current repository or any other repository you want!

In order to add more context, select a code snippet, right-click on it and choose `add to Codiumate as context`, or simply click on SHIFT+CMD+E in Mac or SHIFT+CTRL+E in Windows.

See how it works:

<figure markdown="1">
![VSCode Context](./assets/vscode-context.png){ width="700" }
</figure>

## Bug fixes

- We fixed the chat behavior when there's not file in focus.
- Fixed the context handling in the chat panel when there's no git context.
