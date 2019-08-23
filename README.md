# Resume
*A simple Jekyll + GitHub Pages powered resume template. Project cloned and adapted from https://github.com/jglovier/resume-template*

![img](social_preview.png)

## Changes to the Template

I made some changes to the structure of the content in `_data` and `_layouts/resume.html`.

The favicon is personalised using my avatar (the guy with beanie and tilted head LOL) and is loaded by Github Pages simply by updating line 17 in `_layouts/head.html`. Remember to remove the forward slash (`/`) when specifying the file name as [@LazaroIbanez](https://medium.com/@LazaroIbanez/how-to-add-a-favicon-to-github-pages-403935604460) pointed out in his Medium article.

The layout is slightly changed as well, with keys `environment`, `responsibilities` and `achievements` keys. Surely more verbose than what [@jglovier](https://github.com/jglovier/resume-template) did, but I think it's worth it. Because these fields are loaded conditionally in `_layouts/resume.html`, remember to change the key names there as well.

All hyperlinks in `_includes/icon-links.html` have `target="_blank"` in order to open new tabs and keep the reader focused.

Finally, I took a screenshot and cropped it to 1.6 ratio called `social_preview.png` which I then loaded in the homonym section in the repo settings. I suppose this is the magic that allows to load a preview when sharing the link on Slack/Telegram etc.

I removed the `gh-pages` branch and decided to work from master for the time being to k.i.s.s. :D


## Docs - Original from [@jglovier](https://github.com/jglovier/resume-template)

### Running locally

To test locally, run the following in your terminal:

1. Clone repo locally
1. `bundle install`
2. `bundle exec jekyll serve`
3. Open your browser to `localhost:4000`

### Customizing

First you'll want to fork the repo to your own account. Then clone it locally and customize, or use the GitHub web editor to customize.

#### Options/configuration

Most of the basic customization will take place in the `/_config.yml` file. Here is a list of customizations available via `/_config.yml`:

[...write these out...]

#### Editing content

Most of the content configuration will take place in the `/_layouts/resume.html` file. Simply edit the markup there accordingly

### Publishing to GitHub Pages for free

[GitHub Pages](https://pages.github.com/) will host this for free with your GitHub account. Just make sure you're using a `gh-pages` branch, and the site will automatically be available at `yourusername.github.io/resume-template` (you can rename the repo to resume for your own use if you want it to be available at `yourusername.github.io/resume`). You can also add a CNAME if you want it to be available at a custom domain...

### Configuring with your own domain name

To setup your GH Pages site with a custom domain, [follow the instructions](https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/) on the GitHub Help site for that topic.

### Themes

Right now resume-template only has one theme. More are coming :soon: though. :heart:

## Roadmap

A feature roadmap is [available here](https://github.com/jglovier/resume-template/projects/1). If you features suggestions, please [open a new issue](https://github.com/jglovier/resume-template/issues/new).

## Contributing

If you spot a bug, or want to improve the code, or even make the dummy content better, you can do the following:

1. [Open an issue](https://github.com/jglovier/resume-template/issues/new) describing the bug or feature idea
2. Fork the project, make changes, and submit a pull request

## License

The code and styles are licensed under the MIT license. [See project license.](LICENSE) Obviously you should not use the content of this demo repo in your own resume. :wink:

Disclaimer: Use of Homer J. Simpson image and name used under [Fair Use](https://en.wikipedia.org/wiki/Fair_use) for educational purposes. Project license does not apply to use of this material.
