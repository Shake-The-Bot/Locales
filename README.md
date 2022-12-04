# Shake - Locales
*Remember that any language can have errors or be incorrect, if something bothers you then read this*

## How to add a new language to Shake?
Download the shake.po template file, create a new file from the template file with a optional Translation Editor (like Poedit) set the translated text and send it back to @KidusTV on the [official Shake Discord server](discord.gg/hMBPhYsXkc).

### What should I do with placeholders?
Placeholders like `{member}` or `{value}` will be replaced with channel names, numbers and other information. You **should not** change them as they are still needed for the information and the bot can only read them this way**

### What should I do with newlines?
`\n` is the code for end-of-line and also **should not** be changed in locale files

Only edit the blue part:
```json
"example_text" : "This is an example! Following language has been added to TempVoice:{val1}. Take a look at the official [Website](www.tempvoice.xyz).",
What sh
```

### What should I do with hyperlinks?
`[Text](url-link)` is a clickable text for an url. Its important that the brackets [ ]( ) stay together. The text inside of [ ] brackets should be translated **not the () one**.
