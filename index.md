---
title: "Home"
summary: "Home"
date: 2024-06-01
layout: default
---
Hi :-) I am Michael Kang (Yuliang Kang) and this is my unfinished temporary personal website. 
I am a dream-to-be researcher(I feel that scientist is still too big a word for me). I am currently interested in bayesian statistics, representation learning, and diffusion. And you could kinda see from my interests: yes I am more of a fan of explainable AI.
I attempted a little in economics, more specifically game theory, which I have not yet gotten a good grasp of.
This website is currently only used for personal use: journaling my progress in academics and life. Blogs on research, readings, and fitness will be posted here.

[//]: # ()
[//]: # (## Features)

[//]: # (- Minimal, clean design)

[//]: # (	- CV-specific print-style)

[//]: # (- Responsive layout with collapsible sidebar-menu)

[//]: # (	- Hierarchical menu with deep linking)

[//]: # (- Site-wide search-system)

[//]: # (- Simple social sharing buttons)

[//]: # (- Optional MathJax for displaying mathematical notations)

[//]: # ()
[//]: # (## Setup)

[//]: # ()
[//]: # (1. Register an account with GitHub)

[//]: # (2. Fork `https://github.com/OleVik/personal-academic-website`)

[//]: # (3. Rename repository to `username.github.io`, where `username` is your GitHub-username)

[//]: # (4. Set `baseurl` to `username.github.io` in `_config.yml`)

[//]: # (5. Edit Markdown-files &#40;`.md`&#41;)

[//]: # ()
[//]: # (Edit the pages using any Markdown-editor &#40;see below&#41; or text-editor, then upload them.)

[//]: # ()
[//]: # (### Custom Domain)

[//]: # (If you want to use a custom domain, ie. not `username.github.io` but something like `mywebsite.com`, read [this guide]&#40;https://help.github.com/articles/using-a-custom-domain-with-github-pages/&#41;.)

[//]: # ()
[//]: # (## Workflow)

[//]: # (Pages are written Markdown and use FrontMatter. For Markdown, see [this cheatsheet]&#40;http://ricostacruz.com/cheatsheets/markdown.html&#41; or [this quick guide]&#40;https://milanaryal.com/2015/writing-on-github-pages-and-jekyll-using-markdown/&#41;. Alternatively, view the default "Hello"-document on [StackEdit]&#40;https://stackedit.io/editor&#41;.)

[//]: # ()
[//]: # (### FrontMatter)

[//]: # (Defines the settings for each page, using this format &#40;minimal requirements for each page&#41;:)

[//]: # ()
[//]: # (- Title: Double quote-encapsulated string naming the page)

[//]: # (- Summary: Double quote-encapsulated string describing the page)

[//]: # (- Date: Date for when the page was written &#40;YYYY-MM-DD&#41;)

[//]: # (- Layout: String governing layout to use, either "default" or "cv" &#40;no quotes&#41;)

[//]: # ()
[//]: # (For example:)

[//]: # ()
[//]: # (```)

[//]: # (---)

[//]: # (title: "About")

[//]: # (summary: "About this page.")

[//]: # (date: 2016-04-02)

[//]: # (layout: default)

[//]: # (---)

[//]: # (```)

[//]: # ()
[//]: # (More options are [available here]&#40;https://jekyllrb.com/docs/frontmatter/&#41;.)

[//]: # ()
[//]: # (Notes:)

[//]: # ()
[//]: # (1. Indentation, if used, must be two spaces &#40;not tabs&#41;.)

[//]: # (2. Colons &#40;`:`&#41; can only be used in strings if enclosed in quotes.)

[//]: # (3. Dashes can be used in strings, but should otherwise also be enclosed in quotes &#40;see [this]&#40;https://docs.saltstack.com/en/latest/topics/yaml/&#41;&#41;.)

[//]: # ()
[//]: # (### FrontMatter for the CV)

[//]: # (- Layout must be "cv" &#40;`layout: cv`&#41;)

[//]: # (- See `cv.md` for other variables)

[//]: # (- List-elements are the following: `experience, education, positions`)

[//]: # (	- These consist of nested lists in YAML, for example:)

[//]: # ()
[//]: # (```)

[//]: # (education:)

[//]: # (  - years: 2013-2015)

[//]: # (    name: Master’s Degree)

[//]: # (    location: University)

[//]: # (    description: Includes qualitative and quantitative methods.)

[//]: # (  - years: 2010-2013)

[//]: # (    name: Bachelor’s Degree)

[//]: # (    location: University)

[//]: # (    description: Includes statistics and maths.)

[//]: # (```)

[//]: # ()
[//]: # (To add other list-elements, edit `_layouts/cv.html`, and duplicate the blocks of code including a for-loop, changing the variable &#40;`page.variable`&#41; in:)

[//]: # ()
[//]: # (```)

[//]: # ({% raw %}{% for item in page.experience %})

[//]: # (	Various HTML code...)

[//]: # ({% endfor %}{% endraw %})

[//]: # (```)

[//]: # ()
[//]: # (To whatever you name the list.)

[//]: # ()
[//]: # (### Editors)

[//]: # (In order of most recommended for this workflow:)

[//]: # ()
[//]: # (- [Prose]&#40;http://prose.io/#about&#41;: "Simple content authoring environment for CMS-free websites", very easy to use for editing GitHub Pages.)

[//]: # (	- Direct editing, only requires GitHub authorization.)

[//]: # (- [StackEdit]&#40;https://stackedit.io/&#41;: Elegant interface with live preview and extensive features.)

[//]: # (	- Can publish to GitHub, saves documents in local browser storage or the cloud.)

[//]: # (- [DraftIn]&#40;http://docs.withdraft.com/&#41;: Also elegant and easy-to-use interface with extensive features.)

[//]: # (	- Requires signup &#40;e-mail&#41;.)

[//]: # (	- Handy [Chrome extension]&#40;https://chrome.google.com/webstore/detail/draft/amlbbbgcijmiooecobhkjblcdkjldmdk&#41; for editing text on any website.)

[//]: # ()
[//]: # (Or just edit pages directly on GitHub.)

[//]: # ()
[//]: # (#### Including files on pages)

[//]: # (PDF-files can be linked to from the GitHub Repository, but it is far easier to upload it to [Google Drive]&#40;https://drive.google.com/drive/&#41; and embed it &#40;or any other cloud storage that generates an `<iframe>`-embed tag&#41;.)

[//]: # ()
[//]: # (Procedure &#40;from [here]&#40;http://www.steegle.com/websites/google-sites-howtos/embed-drive-pdf&#41;&#41;:)

[//]: # ()
[//]: # (1. Find the PDF file in Google Drive.)

[//]: # (2. Preview the PDF file in Google Drive.)

[//]: # (3. Pop-out the Google Drive preview.)

[//]: # (4. Use the More actions menu and choose Embed item.)

[//]: # (5. Copy code provided.)

[//]: # (6. Paste it on a separate line in the Markdown-file, like this:)

[//]: # ()
[//]: # (```)

[//]: # (Paragraph...)

[//]: # ()
[//]: # (<iframe style="margin: 10px 0 40px 0;" class="pdf-iframe" src="https://drive.google.com/file/d/0B-xXQEsWEjrUUmpBdkhIVS10YjA/preview" width="100%" height="768"></iframe>)

[//]: # ()
[//]: # (Other Markdown and text.)

[//]: # (```)

[//]: # ()
[//]: # (#### Site settings)

[//]: # (The links in the menu, and their order, are edited through `_config.yml`. The format is also nested YAML lists, like the FrontMatter described above. **'baseurl' must be set to your repository &#40;eg. `baseurl: username.github.io`&#41;, or the build will fail.** The `name` and `description` variable should also be set, as well as `mathjax: true` if you need to render MathJax formulas on pages.)

[//]: # ()
[//]: # (The `markdown, encoding, locale` variables **should not be changed**.)

[//]: # ()
[//]: # (To find the right page-link &#40;`#somethingonthepage`&#41; you open the page, hover a heading so that the icon-link displays, right-click it and choose "Copy link". Everything after the `#` is the link for this specific title on the page.)

[//]: # ()
[//]: # (Note that these links must be encapsulated in quotes in the lists in `_config.yml`, or they will be interpreted as code-comments.)

[//]: # ()
[//]: # (### Development)

[//]: # (Written in [Jekyll]&#40;http://jekyllrb.com/&#41;, structured with [Bootstrap v4]&#40;http://getbootstrap.com/&#41;, styled with [plain CSS]&#40;http://www.css3-tutorial.net/introduction/what-is-css/&#41;. The Jekyll-output &#40;in the `_site`-folder when generated&#41; can be hosted anywhere &#40;static files&#41;. For further development, see [Jekyll Tips]&#40;http://jekyll.tips/&#41; and [GitHub Pages Setup Guide]&#40;http://jmcglone.com/guides/github-pages/&#41;.)
