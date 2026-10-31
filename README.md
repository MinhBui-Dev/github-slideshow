# GitHub Learning Lab slideshow

A small Jekyll and reveal.js slide deck from GitHub's introductory Learning Lab. Slides are Markdown posts with YAML front matter. The [opening slide](_posts/0000-01-01-intro.md) shows the format, and the [slide layout](_layouts/) controls how the content is rendered.

## Preview the slides

From a clone with Git, Ruby, and Bundler installed:

```sh
sh script/setup
sh script/server
```

Open the local address printed by Jekyll. To add a slide, create a dated Markdown file in [`_posts/`](_posts/) with `layout: slide`, a title, and the slide text. The [setup script](script/setup) installs the gems and initializes the Git submodule.

<details>
<summary>Original Learning Lab notes</summary>

# Your GitHub Learning Lab Repository for Introducing GitHub

Welcome to **your** repository for your GitHub Learning Lab course. This repository will be used during the different activities that I will be guiding you through. See a word you don't understand? We've included an emoji 📖 next to some key terms. Click on it to see its definition.

Oh! I haven't introduced myself...

I'm the GitHub Learning Lab bot and I'm here to help guide you in your journey to learn and master the various topics covered in this course. I will be using Issue and Pull Request comments to communicate with you. In fact, I already added an issue for you to check out.

![issue tab](https://lab.github.com/public/images/issue_tab.png)

I'll meet you over there, can't wait to get started!

This course is using the :sparkles: open source project [reveal.js](https://github.com/hakimel/reveal.js/). In some cases we’ve made changes to the history so it would behave during class, so head to the original project repo to learn more about the cool people behind this project.

</details>
