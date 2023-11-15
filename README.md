# Intro to Kintone Slides

This is a slide deck for a quick introduction to Kintone. Perfect for a 5-10 minute presentation.

![Slide 1](screenshots/01.png)

| Item       | URL                                                                                                                                           |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Slide Deck | [ahandsel.github.io/kintone-quick-intro-slides](https://ahandsel.github.io/kintone-quick-intro-slides/)                     |
| Presenter  | [ahandsel.github.io/kintone-quick-intro-slides/presenter](https://ahandsel.github.io/kintone-quick-intro-slides/presenter/) |
| Markdown   | [slides.md](slides.md)                                                                                                                        |
| PDF        | [slides.pdf](slides.pdf)                                                                                                                      |
| PNG        | [screenshots](screenshots)                                                                                                                    |

## Kintone Resources

| Links to Resources                                                           | Description               |
| ---------------------------------------------------------------------------- | ------------------------- |
| [kintone.dev](https://kintone.dev/)                                          | Read API Docs & Tutorials |
| [forum.kintone.dev](https://forum.kintone.dev/)                              | Post Questions            |
| [@KintoneDeveloperProgram](https://www.youtube.com/@KintoneDeveloperProgram) | Watch Tutorials           |

## Repo Usage

The slide deck is built using [Sli.dev](https://sli.dev/).

How to open the slides locally:

1. `git clone`
1. `npm install`
1. `npm run dev`

* Slide deck: <http://localhost:3030/>
* Presenter mode: <http://localhost:3030/presenter/>

How to deploy on GitHub Pages:

1. Modify [package.json](package.json)'s `buildBase` to use your repo name - [Sli.Dev HelpDoc](https://sli.dev/guide/hosting.html#github-pages)
1. Commit changes to the `main` branch
1. From your GitHub Repo page: Repo `⚙️ Settings` > `Pages` > `Build and deployment` > Select `GitHub Actions` for Source
1. Finally, after all workflows are executed, a link to the slides should appear under Setting > Pages
