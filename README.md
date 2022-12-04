# Shake - Locales
*Remember that any language can have errors or be incorrect, if something bothers you then read this*

## How to add a new language to Shake?
Download the shake.po template file, create a new file from the template file with a optional Translation Editor (like Poedit) set the translated text and send it back to @KidusTV on the [official Shake Discord server](discord.gg/hMBPhYsXkc).

Example: ```json
#: classes/help/pagesource.py:360
#, python-brace-format
msgid ""
"You can get more help if you join the official server at\n"
"[https://discord.gg/shake]({support_server})"
msgstr ""
"Weitere Hilfe erhalten Sie, wenn Sie dem offiziellen Server beitreten unter\n"
"[https://discord.gg/shake]({support_server})"
```

### What should I do with placeholders?
Placeholders like `{member}` or `{value}` will be replaced with channel names, numbers and other information. You **should not** change them as they are still needed for the information and the bot can only read them this way**

### What should I do with newlines?
`\n` is the code for end-of-line and also **should not** be changed in locale files

### What should I do with hyperlinks?
`[Text](url-link)` is a clickable text for an url. Its important that the brackets [ ]( ) stay together. The text inside of [ ] brackets should be translated **not the () one**.
