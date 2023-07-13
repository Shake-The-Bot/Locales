# Shake - Locales

This project is a community one for everyone who wants to help translating the official Shake Discord-Bot
This repository includes all current gettext translations and the template of them

[![Crowdin](https://badges.crowdin.net/shake-bot/localized.svg)](https://crowdin.com/project/shake-bot)

_Remember that any language can have errors or be incorrect, if something bothers you then read this_

## How to add a new language to Shake?

Download the shake.po template file, create a new file from the template file with a optional Translation Editor (like Poedit) set the translated text and send it back to @KidusTV on the official Shake Discord server

[![Button](https://readme-components.vercel.app/api?component=button&text=Join%20Developer%20Server&fill=6175f5&textfill=ffffff&size=small)](https://discord.gg/hMBPhYsXkc)

German example:

```po
#: classes/help/pagesource.py:360
#, python-brace-format
msgid "You can get more help if you join the official server [here](https://discord.gg/shake)"
msgstr "Weitere Hilfe erhalten Sie, wenn Sie dem offiziellen Server [hier](https://discord.gg/shake) beitreten"
```

## What should I do with ...

### ...placeholders?

Placeholders like `{member}` or `{value}` will be replaced with channel names, numbers and other information. You **should not** change them as they are still needed for the information and the bot can only read them this way

### ...newlines?

`\n` is the code for end-of-line and also **should not** be changed in locale files

### ...hyperlinks?

`[Text](url-link)` is a clickable text for an url. Its important that the brackets [ ]() stay together. The text inside of [ ] brackets should be translated but **not the () one**
