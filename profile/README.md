<p align="center">
  <img src="https://raw.githubusercontent.com/WebsiteGenerator/WebsiteGenerator/main/brand/Logo.png" alt="WebsiteGenerator" width="350">
</p>

<h1 align="center">WebsiteGenerator 🧱</h1>

<p align="center">
  Answer a few questions, get a website. My Python script from 2021, now in the browser. Part of Back from Zero.<br>
  <a href="https://websitegenerator.bf0.by0.link"><b>▶ Open it at websitegenerator.bf0.by0.link</b></a>
</p>

## The story

In June 2021 I was 13, called myself byZero and wrote `lol.py`, a Python script that asked you a few questions in the terminal and turned your answers into a personal website. The first commit was called *"First Commit ;D"*. One day later came v2.0 with social media icons and custom frames. Over the winter I added pronouns and image codes for the icons, and in January 2022 the project got this organization and a pip package. After that it went quiet. [Back from Zero](https://bf0.by0.link) is me switching my old byZero projects back on, and this is one of them.

## What it does

The browser version runs the questions from `lol.py` in a terminal window:

- It asks for your name, pronouns, a description, your domain, a profile picture and a thumbnail, then for as many cards and social media icons as you want. It still answers your name with *"Thanks! … is a really nice name. :D"*
- After every answer, your website updates in a browser window next to the terminal.
- Click any earlier answer to change it.
- For card and icon images you can type a URL or an image code. All 55 icons are clickable right in the terminal.
- At the end you download one `index.html` with the CSS built in, ready to host. The page is dark, shows your name, description, pronouns, cards and icons, and has a small "Made with WebsiteGenerator" at the bottom.

## Run it

**In the browser:** [websitegenerator.bf0.by0.link](https://websitegenerator.bf0.by0.link) (same thing on [GitHub Pages](https://websitegenerator.github.io/WebsiteGenerator/)). Nothing to install.

**In the terminal:** you need Python 3 and `requests`.

```bash
git clone https://github.com/WebsiteGenerator/WebsiteGenerator
cd WebsiteGenerator/src
pip install requests
python main.py
```

Your website lands in `src/web/index.html`. The script loads the CSS from this repo, so it needs internet. `main.py` is a cleaned-up version from 2026. The original `lol.py` is still in the [first commit](https://github.com/WebsiteGenerator/WebsiteGenerator/blob/891d9ba/lol.py).

## Repos

- [WebsiteGenerator](https://github.com/WebsiteGenerator/WebsiteGenerator): the generator. Browser version in `docs/`, terminal version in `src/`, icons in `icons/`.
- [resources](https://github.com/WebsiteGenerator/resources): the HTML pieces the old script downloaded in 2022. The current version doesn't need them anymore.

## Back from Zero

WebsiteGenerator is part of [Back from Zero](https://bf0.by0.link), together with [ZeroBot](https://github.com/EinfachRuwen/ZeroBot) and [Counter](https://github.com/EinfachRuwen/Counter).

Made by Ruwen, back then byZero · [focusonruwen.com](https://focusonruwen.com) · [@EinfachRuwen](https://github.com/EinfachRuwen)
