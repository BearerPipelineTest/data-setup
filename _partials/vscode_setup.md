### VS Code Extensions

Let's gain time now and add other extensions that will be helpful during your Bootcamp.
For each of these extensions:
- On the web page, click on `install`
- In the browser, accept to use VS Code to install the extension
- In VS Code, click on `install`

**Extensions**:
- [Sublime Text Keymap](https://marketplace.visualstudio.com/items?itemName=ms-vscode.sublime-keybindings)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- [Python Indent](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent)

### VS Code Settings
- Press `Ctrl` + `,` on your keyboard to open the settings
- In the search bar, type `emmet`
- Click on the first **`Edit in settings.json`** link


Paste the following just before the last `}`:

```bash
"emmet.triggerExpansionOnTab": true,
"emmet.includeLanguages": {
  "erb": "html"
},
```

It should look like this:

![vscode_emmet](images/vscode_emmet.jpg)

:warning: You should add a comma if there is none after the **`]`** like line 26 in the image above ☝️

:warning: Don't forget to save those changes!
