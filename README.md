




> When GitHub initially introduced Copilot, I was suspicious. In addition to not understanding the technology, I was uncertain how it would affect my job and the industry. However, as I started to use Copilot, I gained an appreciation, understanding, and even eagerness about the future of AI pair programming tools ✈️. I’m passionate about Copilot because it helps increase my confidence and velocity as a programmer. I’ll share how you can use Copilot to enhance your developer experience too!
> 
> ## What is GitHub Copilot?
> [GitHub Copilot](https://github.com/features/copilot) is an AI pair programmer that helps you code faster with less work. The user experience is similar to the [Smart Compose](https://workspaceupdates.googleblog.com/2020/02/smart-compose-ga.html) feature within Google Docs and Gmail, which autocompletes sentences while the user is typing. Similarly, GitHub Copilot instantly draws context from comments and code and instantly suggests individual lines and whole functions instantly ⚡.
> 
> ## What is GitHub Copilot Labs?
> GitHub [Copilot Labs](https://githubnext.com/projects/copilot-labs/) is a separate extension that comes complimentary with GitHub Copilot. _Please keep in mind that Copilot Labs is an experimental extension developed by the GitHub Next team._ Currently, Copilot Labs consists of a VS Code sidebar that houses distinct features starting with “explain this code” and “translate this code.”
> 
> ## Is GitHub Copilot magic 🪄?
> Although Copilot feels like magic, it’s not. To suggest lines of code, Copilot needs a programmer's brain. Under the hood, GitHub Copilot is powered by OpenAI Codex. OpenAI is an AI research lab that developed Codex, a model that translates natural language into code. Codex is a version of GPT-3, another model developed by OpenAI. GPT-3 (Generative Pre-trained Transformer 3) uses deep learning to produce human-like text. Many of your favorite applications use GPT-3. For example, [Duolingo](https://blog.duolingo.com/test-creation-machine-learning/) specifically uses GPT-3 for French grammar correction. Codex also features natural language understanding but is fine-tuned for programming. By leveraging Codex, Copilot can help computers interpret people’s intent and empower developers to code with confidence.
> 
> ## Is GitHub Copilot perfect?
> GitHub Copilot does not always spit out perfectly well-written, up-to-date code. Occasionally, some of its suggestions are [downright hilarious](https://twitter.com/MikeMcQuaid/status/1542434802430873600?s=20&t=I134_uPpndaxzvKxA76j8g). However, it’s more commonly accurate, and it continues to improve 🚀. Here are some tips to ensure technologists receive their desired suggestions:
> 
> * **Tip [Welcome to GitHub product feedback #1](https://github.com/orgs/community/discussions/1)**: Try writing clear, understandable comments to get the best results from Copilot.
>   ![Country codes](https://user-images.githubusercontent.com/22990146/188703640-dfdaa243-9759-4b05-8dce-47acb6711e61.gif)
>         
>           [
>             
>           ](https://user-images.githubusercontent.com/22990146/188703640-dfdaa243-9759-4b05-8dce-47acb6711e61.gif)
>           
>               ![Country codes](https://user-images.githubusercontent.com/22990146/188703640-dfdaa243-9759-4b05-8dce-47acb6711e61.gif)
>             
>           
>             
>               
>                 
>               
>               
>                 
>                 
>               
>             
>             [
>               
>                 
>               
>             ](https://user-images.githubusercontent.com/22990146/188703640-dfdaa243-9759-4b05-8dce-47acb6711e61.gif)
> * **Tip [Feature Request: Select a column when adding an issue to a project #2](https://github.com/orgs/community/discussions/2)**: Prompt GitHub Copilot to give you other suggestions by using a few keyboard shortcuts. You can learn more about viewing multiple suggestions [here](https://docs.github.com/en/copilot/getting-started-with-github-copilot/getting-started-with-github-copilot-in-visual-studio-code#seeing-alternative-suggestions).
> 
> ![Copilot shortcuts](https://user-images.githubusercontent.com/22990146/201698438-ce4d7ce6-bb36-4551-aad5-b9743fc5bf89.png)
> 
> ## How does GitHub Copilot benefit developers?
> ### Coding faster
> Whether working as a software engineer or a developer advocate, I've found myself in moments where I'm writing code at the last minute 🕰️, or experiencing a coder's block. Reading suggestions from Copilot reminds me of how to solve common and not-so-common algorithms.
> 
> ![Image description](https://camo.githubusercontent.com/5894d875cd6c65ea0be1ecfe8c36847f63a0c8c0562c6ea94a88f5b211e87bf4/68747470733a2f2f6465762d746f2d75706c6f6164732e73332e616d617a6f6e6177732e636f6d2f75706c6f6164732f61727469636c65732f356e3131653431323839686a686a63373438656f2e706e67)
> 
> ![Image description](https://camo.githubusercontent.com/c00b0363a5de77926705799f283706df35546ddfad2bbe548baf2330587e9e9b/68747470733a2f2f6465762d746f2d75706c6f6164732e73332e616d617a6f6e6177732e636f6d2f75706c6f6164732f61727469636c65732f7472727a366e643338756d69786c3269723267382e706e67)
> 
> ![Image description](https://camo.githubusercontent.com/2d72e789aeab62efdb34c43c5b29fa37176e0237f1670c567d59a68c531628ac/68747470733a2f2f6465762d746f2d75706c6f6164732e73332e616d617a6f6e6177732e636f6d2f75706c6f6164732f61727469636c65732f64706565616b716c74637a317933797969756e382e706e67)
> 
> ### Writing tests
> While I understand that writing tests for your code are essential, I don't enjoy it. I often take forever to start – trying to remember the difference between keywords like `mock`, `nock`, `beforeEach`, and `afterAll`. Then, when I get the pattern down, it feels like a tedious process for me to reach a particular test coverage percentage. This is where Copilot can come in handy. I can write a few comments describing what I want to test; then, Copilot may suggest the code needed for the test. I can also start writing tests, and Copilot may provide anticipated code for other needed tests. Learn more by reading [Using GitHub Copilot to Automate Tests ](https://applitools.com/blog/using-github-copilot-to-automate-tests/)by [Colby Fayock](https://github.com/colbyfayock) and [Rewriting tests from Cypress to Playwright using GPT-3](https://contra.com/p/PWBcPYZc-rewriting-tests-from-cypress-to-playwright-using-gpt-3) by [Gajus Kuizinas](https://github.com/gajus).
> 
> ### Writing better comments
> Sometimes, writing great comments ends up on the back burner. There's a tendency to assume your code is clean, readable, and self-documenting until you return to your code the next day and you're unable to decipher the hieroglyphics. Since well-written comments tend to trigger better results from Copilot, I'm more motivated to write explicit, relevant comments.
> 
> **For example, Copilot can understand Spanish comments!**
> 
> ![spanish comment](https://user-images.githubusercontent.com/22990146/188705342-549cf999-ff2c-4b81-99c0-4e466ee7d8b4.gif) [ ](https://user-images.githubusercontent.com/22990146/188705342-549cf999-ff2c-4b81-99c0-4e466ee7d8b4.gif) ![spanish comment](https://user-images.githubusercontent.com/22990146/188705342-549cf999-ff2c-4b81-99c0-4e466ee7d8b4.gif) [ ](https://user-images.githubusercontent.com/22990146/188705342-549cf999-ff2c-4b81-99c0-4e466ee7d8b4.gif)
> 
> **Copilot can help you write Regex!**
> 
> ![validate phone number](https://user-images.githubusercontent.com/22990146/188703630-5a0b3b32-89b4-4937-864f-f24cb957c954.gif) [ ](https://user-images.githubusercontent.com/22990146/188703630-5a0b3b32-89b4-4937-864f-f24cb957c954.gif) ![validate phone number](https://user-images.githubusercontent.com/22990146/188703630-5a0b3b32-89b4-4937-864f-f24cb957c954.gif) [ ](https://user-images.githubusercontent.com/22990146/188703630-5a0b3b32-89b4-4937-864f-f24cb957c954.gif)
> 
> ### Pair programming with a coworker
> I'm not fantastic at pair programming, especially when I have less experience than my colleague. I also experience anxiety about people watching my every move while I code. What stops me in my tracks is that I often try to remember the syntax. With Copilot, my pair programming buddy spends less time watching me Google the "Reduce JavaScript array method" for the umpteenth time. Instead, GitHub Copilot suggests the correct syntax for me.
> 
> Using GitHub Copilot is a game-changer, but don’t take my word for it. In a recent [study](https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/), “60–75% of users reported they feel more fulfilled with their job, feel less frustrated when coding, and are able to focus on more satisfying work when using GitHub Copilot.”
> 
> ## How do I install it?
> GitHub Copilot is available in Visual Studio Code, JetBrains, and my favorite, Neovim. Copilot is available for developers today and is free for qualified teachers, students, and maintainers of popular open source libraries. [Sign up](https://github.com/features/copilot) for GitHub Copilot 👩‍✈️today!
> 
> ## What’s next?
> GitHub Copilot has inspired the evolution and development of other AI pair programming tools. It also enables developers and open source maintainers to think outside the box and create confidently. There is much more to share about GitHub Copilot and how it can improve our lives as developers, so stay tuned for my next post.
> 
> _If you have any questions or want to share your love for GitHub Copilot, feel free to comment below!_









<h2> 
<h2> 
<h2> 
_-_
<h2> 


  
  
  
  
  
  
  
# GitHub CLI

`gh` is GitHub on the command line. It brings pull requests, issues, and other GitHub concepts to the terminal next to where you are already working with `git` and your code.

![screenshot of gh pr status](https://user-images.githubusercontent.com/98482/84171218-327e7a80-aa40-11ea-8cd1-5177fc2d0e72.png)

GitHub CLI is available for repositories hosted on GitHub.com and GitHub Enterprise Server 2.20+, and to install on macOS, Windows, and Linux.

## Documentation

For [installation options see below](#installation), for usage instructions [see the manual][manual].

## Contributing

If anything feels off, or if you feel that some functionality is missing, please check out the [contributing page][contributing]. There you will find instructions for sharing your feedback, building the tool locally, and submitting pull requests to the project.

<!-- this anchor is linked to from elsewhere, so avoid renaming it -->
## Installation

### macOS

`gh` is available via [Homebrew][], [MacPorts][], [Conda][], [Spack][], and as a downloadable binary from the [releases page][].

#### Homebrew

| Install:          | Upgrade:          |
| ----------------- | ----------------- |
| `brew install gh` | `brew upgrade gh` |

#### MacPorts

| Install:               | Upgrade:                                       |
| ---------------------- | ---------------------------------------------- |
| `sudo port install gh` | `sudo port selfupdate && sudo port upgrade gh` |

#### Conda

| Install:                                 | Upgrade:                                |
|------------------------------------------|-----------------------------------------|
| `conda install gh --channel conda-forge` | `conda update gh --channel conda-forge` |

Additional Conda installation options available on the [gh-feedstock page](https://github.com/conda-forge/gh-feedstock#installing-gh).

#### Spack

| Install:           | Upgrade:                                 |
| ------------------ | ---------------------------------------- |
| `spack install gh` | `spack uninstall gh && spack install gh` |

### Linux & BSD

`gh` is available via:
- [our Debian and RPM repositories](./docs/install_linux.md);
- community-maintained repositories in various Linux distros;
- OS-agnostic package managers such as [Homebrew](#homebrew), [Conda](#conda), and [Spack](#spack); and
- our [releases page][] as precompiled binaries.

For more information, see [Linux & BSD installation](./docs/install_linux.md).

### Windows

`gh` is available via [WinGet][], [scoop][], [Chocolatey][], [Conda](#conda), and as downloadable MSI.

#### WinGet

| Install:            | Upgrade:            |
| ------------------- | --------------------|
| `winget install --id GitHub.cli` | `winget upgrade --id GitHub.cli` |

#### scoop

| Install:           | Upgrade:           |
| ------------------ | ------------------ |
| `scoop install gh` | `scoop update gh`  |

#### Chocolatey

| Install:           | Upgrade:           |
| ------------------ | ------------------ |
| `choco install gh` | `choco upgrade gh` |

#### Signed MSI

MSI installers are available for download on the [releases page][].

### Codespaces

To add GitHub CLI to your codespace, add the following to your [devcontainer file](https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/adding-features-to-a-devcontainer-file):

```json
"features": {
  "github-cli": "latest"
}
```

### GitHub Actions

GitHub CLI comes pre-installed in all [GitHub-Hosted Runners](https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners).

### Other platforms

Download packaged binaries from the [releases page][].

### Build from source

See here on how to [build GitHub CLI from source][build from source].

## Comparison with hub

For many years, [hub][] was the unofficial GitHub CLI tool. `gh` is a new project that helps us explore
what an official GitHub CLI tool can look like with a fundamentally different design. While both
tools bring GitHub to the terminal, `hub` behaves as a proxy to `git`, and `gh` is a standalone
tool. Check out our [more detailed explanation][gh-vs-hub] to learn more.

[manual]: https://cli.github.com/manual/
[Homebrew]: https://brew.sh
[MacPorts]: https://www.macports.org
[winget]: https://github.com/microsoft/winget-cli
[scoop]: https://scoop.sh
[Chocolatey]: https://chocolatey.org
[Conda]: https://docs.conda.io/en/latest/
[Spack]: https://spack.io
[releases page]: https://github.com/cli/cli/releases/latest
[hub]: https://github.com/github/hub
[contributing]: ./.github/CONTRIBUTING.md
[gh-vs-hub]: ./docs/gh-vs-hub.md
[build from source]: ./docs/source.md

  
  
  
  
  
  
  
  
  
  [up-for-grabs.net](https://up-for-grabs.net/)
![Continuous Integration status](https://github.com/up-for-grabs/up-for-grabs.net/workflows/Continuous%20Integration/badge.svg)
[![Netlify Status](https://api.netlify.com/api/v1/badges/0ee7bf9f-1aed-465b-8e9e-01de009a8a7e/deploy-status)](https://app.netlify.com/sites/up-for-grabs-test-bench/deploys)
[![All Contributors](https://img.shields.io/badge/all_contributors-11-orange.svg?style=flat-square)](#contributors)
================

<a href="https://up-for-grabs.net/"><img width="814" src="https://user-images.githubusercontent.com/359239/67390578-50f83a00-f573-11e9-835d-02eb9e019afb.png"></a>

This repository contains the content for the [Up-For-Grabs website](https://up-for-grabs.net/), a list of projects with curated tasks for new contributors.

## List your project

If you know of or own a project that should be listed on Up for Grabs,
[follow the instructions to open a pull request](docs/list-a-project.md).

## Contributing

If you would like to get involved with the project, please read the
[CONTRIBUTING.md](.github/CONTRIBUTING.md) file as it contains:

 - instructions about getting your environment setup
 - guidance for testing locally
 - commands to run to verify changes

## How does the site work?

If you want to learn more about the various parts of the Up-for-Grabs project,
the [How it works](docs/how-it-works.md) document is a good overview.

## Contributors ✨

Thanks to these wonderful people who have improved the code and documentation to help this project grow. ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/filipe-gomes"><img src="https://avatars1.githubusercontent.com/u/42053052?v=4?s=100" width="100px;" alt="Filipe Magalhaes Gomes"/><br /><sub><b>Filipe Magalhaes Gomes</b></sub></a><br /><a href="#content-filipe-gomes" title="Content">🖋</a></td>
      <td align="center"><a href="https://mkkhedawat.github.io/"><img src="https://avatars2.githubusercontent.com/u/5137374?v=4?s=100" width="100px;" alt="Manish Kumar Khedawat"/><br /><sub><b>Manish Kumar Khedawat</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=mkkhedawat" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/SpaceEEC"><img src="https://avatars1.githubusercontent.com/u/24881032?v=4?s=100" width="100px;" alt="SpaceEEC"/><br /><sub><b>SpaceEEC</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=SpaceEEC" title="Code">💻</a></td>
      <td align="center"><a href="http://www.joaomanoel.com.br"><img src="https://avatars0.githubusercontent.com/u/6238111?v=4?s=100" width="100px;" alt="João Manoel Lins"/><br /><sub><b>João Manoel Lins</b></sub></a><br /><a href="#content-JoaoManoel" title="Content">🖋</a></td>
      <td align="center"><a href="https://github.com/crystal-dawn"><img src="https://avatars3.githubusercontent.com/u/38540136?v=4?s=100" width="100px;" alt="Crystal Yungwirth"/><br /><sub><b>Crystal Yungwirth</b></sub></a><br /><a href="#content-crystal-dawn" title="Content">🖋</a></td>
      <td align="center"><a href="https://github.com/TeslaAdis"><img src="https://avatars1.githubusercontent.com/u/20220542?v=4?s=100" width="100px;" alt="Adis Talic"/><br /><sub><b>Adis Talic</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=TeslaAdis" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/AstroBoogie"><img src="https://avatars2.githubusercontent.com/u/18710598?v=4?s=100" width="100px;" alt="Nathaniel Adams"/><br /><sub><b>Nathaniel Adams</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=AstroBoogie" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center"><a href="http://ishan.co"><img src="https://avatars0.githubusercontent.com/u/1873271?v=4?s=100" width="100px;" alt="Ishan Sharma"/><br /><sub><b>Ishan Sharma</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=ishansharma" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/firfircelik"><img src="https://avatars0.githubusercontent.com/u/34511698?v=4?s=100" width="100px;" alt="Firat Celik"/><br /><sub><b>Firat Celik</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=firfircelik" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/phncosta"><img src="https://avatars0.githubusercontent.com/u/47827714?v=4?s=100" width="100px;" alt="Paulo H. Costa"/><br /><sub><b>Paulo H. Costa</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=phncosta" title="Documentation">📖</a></td>
      <td align="center"><a href="https://github.com/XxZhang2017"><img src="https://avatars2.githubusercontent.com/u/26696836?v=4?s=100" width="100px;" alt="XxZhang2017"/><br /><sub><b>XxZhang2017</b></sub></a><br /><a href="#content-XxZhang2017" title="Content">🖋</a> <a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=XxZhang2017" title="Code">💻</a></td>
      <td align="center"><a href="https://chadwhitacre.com/"><img src="https://avatars2.githubusercontent.com/u/134455?v=4?s=100" width="100px;" alt="Chad Whitacre"/><br /><sub><b>Chad Whitacre</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=chadwhitacre" title="Documentation">📖</a></td>
      <td align="center"><a href="https://github.com/Jai2305"><img src="https://avatars.githubusercontent.com/u/47395196?v=4?s=100" width="100px;" alt="Jai "/><br /><sub><b>Jai </b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=Jai2305" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/jalaniz1"><img src="https://avatars.githubusercontent.com/u/1664815?v=4?s=100" width="100px;" alt="James Alaniz"/><br /><sub><b>James Alaniz</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=jalaniz1" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/gewarren"><img src="https://avatars.githubusercontent.com/u/24882762?v=4?s=100" width="100px;" alt="Genevieve Warren"/><br /><sub><b>Genevieve Warren</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=gewarren" title="Documentation">📖</a></td>
      <td align="center"><a href="https://github.com/SaadAnsari17"><img src="https://avatars.githubusercontent.com/u/94478736?v=4?s=100" width="100px;" alt="Saad"/><br /><sub><b>Saad</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=SaadAnsari17" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/JeetPatel1016"><img src="https://avatars.githubusercontent.com/u/60153965?v=4?s=100" width="100px;" alt="Jeet Patel"/><br /><sub><b>Jeet Patel</b></sub></a><br /><a href="https://github.com/up-for-grabs/up-for-grabs.net/commits?author=JeetPatel1016" title="Code">💻</a></td>
    </tr>
  </tbody>
  <tfoot>
    
  </tfoot>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome!
  
  
  
  
  
  
<h2> 
<h2> 
<h2> 
_-_
<h2> 

  
  
  

  
  # python-action
Write GitHub Actions workflows using Python by running python scripts. The tool uses Microsoft Windows Server.
> Only supports Python 3. **Python 2 is [deprecated](https://www.google.com/url?sa=t&source=web&rct=j&url=https://www.python.org/doc/sunset-python-2/%23:~:text%3DWe%2520have%2520decided%2520that%2520January,as%2520soon%2520as%2520you%2520can.&ved=2ahUKEwiO7LKg37n1AhVCgv0HHd5rDq0QFnoECAQQBQ&usg=AOvVaw3VKra0lIbRuX6L4ED4iVcJ).**
## Usage
To use the workflow, there must be a `workflow.py` in the branch where you are trying to publish your action to Marketplace at. I reccommemd that your action runs on `Windows-latest` to ensure you are always running the latest version of Windows Server.
## Example

### `action.y(a)ml`
```yaml
name: Python Hello World

jobs:
  python3runner:
    runs-on: windows-latest
    steps:
      - uses: Tyler887/python-action@main
        with:
          path: .\ # Rest of the path to the folder
        env:
          OWNER: # Owner of the repository defined in REPO
          REPO: # Name of the repo (without "OWNER/")
          
```
### `workflow.py`
```python
print("Hello World")
```
  
  
  
    
  
  
  
  
<h2> 
<h2> 
<h2> 
_-_
<h2> 

  
  
  

  
  <div align="center">
  <img src="https://responsively.app/assets/img/responsively-logo.png" alt="Responsively Logo" width="150">
  <h1>Responsively App <a href="https://github.com/responsively-org/responsively-app/releases/latest" target="_blank"><img alt="GitHub release" src="https://img.shields.io/github/v/release/responsively-org/responsively-app"></a></h1>
  <strong>A must-have devtool for web developers for quicker responsive web development. 🚀</strong>
  <h6>Save time by becoming 5x faster!</h6>
</div>
<br>

<p align="center">
  <a href="https://twitter.com/ResponsivelyApp" target="_blank">
    <img src="https://img.shields.io/twitter/follow/responsivelyApp?color=26A0ED&label=Follow&logo=twitter&logoColor=white&style=flat" alt="Twitter">
  </a>
  
  <a href="#contributors-" target="_blank">
    <img src="https://img.shields.io/github/all-contributors/responsively-org/responsively-app?style=flat" alt="contributors">
  </a>
  
  

  <a href="https://responsively.app/join-slack" target="_blank">
    <img src="https://img.shields.io/badge/Join%20on-Slack-brightgreen?logo=slack" alt="Slack">
  </a>

  <a href="https://xscode.com/manojvivek/responsively-app" target="_blank">
    <img src="https://img.shields.io/badge/Available%20on-xs%3Acode-blue?style=?style=flat&logo=appveyor&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAMAAACdt4HsAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAAZQTFRF////////VXz1bAAAAAJ0Uk5T/wDltzBKAAAAlUlEQVR42uzXSwqAMAwE0Mn9L+3Ggtgkk35QwcnSJo9S+yGwM9DCooCbgn4YrJ4CIPUcQF7/XSBbx2TEz4sAZ2q1RAECBAiYBlCtvwN+KiYAlG7UDGj59MViT9hOwEqAhYCtAsUZvL6I6W8c2wcbd+LIWSCHSTeSAAECngN4xxIDSK9f4B9t377Wd7H5Nt7/Xz8eAgwAvesLRjYYPuUAAAAASUVORK5CYII=" alt="XS:Code">
  </a>

  <a href="https://github.com/responsively-org/responsively-app/issues" target="_blank">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat" alt="PRs Welcome">
  </a>
  
   <a href="https://opencollective.com/responsively" target="_blank">
    <img alt="Open Collective backers and sponsors" src="https://img.shields.io/opencollective/all/responsively">
  </a>
</p>

<p align="center">
  <a href="https://www.producthunt.com/posts/responsively?utm_source=badge-top-post-badge&utm_medium=badge&utm_souce=badge-responsively" target="_blank">
    <img src="https://api.producthunt.com/widgets/embed-image/v1/top-post-badge.svg?post_id=200375&theme=light&period=daily" alt="ProductHunt">
  </a>
</p>

<p align="center">
  Download Now (free!): <a href="https://responsively.app" target="_blank">
    responsively.app
  </a>
</p>
<br>

## Responsively App
>A modified browser built using [Electron](https://www.electronjs.org/) that helps in responsive web development. 
<br>

![Quick Demo](https://responsively.app/assets/img/responsively-app.gif)

## Features
1. Mirrored User-interactions across all devices.
2. Customizable preview layout to suit all your needs.
3. One handy elements inspector for all devices in preview.
4. 30+ built-in device profiles with option to add custom devices.
5. One-click screenshot all your devices.
6. Hot reloading supported for developers.

Please visit the website to know more about the application - https://responsively.app


## Download
The application is available for Mac, Windows and Linux platforms. Please download it from [the releases page](https://github.com/responsively-org/responsively-app/releases)

Alternatively, MacOS users can use [`brew`](https://formulae.brew.sh/cask/responsively) <a href="https://formulae.brew.sh/cask/responsively" target="_blank"> <img src="https://badgen.net/homebrew/cask/dy/responsively" alt="Homebrew installs"></a>
```bash
brew install --cask responsively
```

Also, Windows users can use [`chocolatey`](https://chocolatey.org/packages/responsively/) <a href="https://chocolatey.org/packages/responsively/" target="_blank"> <img src="https://img.shields.io/chocolatey/dt/responsively" alt="Chocolatey installs"></a> 
```bash
choco install responsively
```

or [`winget`](https://github.com/microsoft/winget-cli):
```bash
winget install ResponsivelyApp
```

Linux users using an RPM Package Manager can use `rpm`
```bash
sudo rpm -i https://github.com/responsively-org/responsively-app/releases/download/v[VERSION]/Responsively-App-[VERSION].x86_64.rpm
```

otherwise download an AppImage from [the releases page](https://github.com/responsively-org/responsively-app/releases)

Follow on Twitter for future updates - [![Twitter Follow](https://img.shields.io/twitter/follow/ResponsivelyApp?style=social)](https://twitter.com/ResponsivelyApp)

## Browser Extension

Install the handy browser extension to easily send links from your browser to the app and preview instantly.
- [Download for Chrome](https://chrome.google.com/webstore/detail/responsively-helper/jhphiidjkooiaollfiknkokgodbaddcj) <a href="https://chrome.google.com/webstore/detail/responsively-helper/jhphiidjkooiaollfiknkokgodbaddcj" target="_blank"><img alt="Chrome Web Store" src="https://img.shields.io/chrome-web-store/users/jhphiidjkooiaollfiknkokgodbaddcj"></a>
- [Download for Firefox](https://addons.mozilla.org/en-US/firefox/addon/responsively-helper/) <a href="https://addons.mozilla.org/en-US/firefox/addon/responsively-helper/" target="_blank"><img alt="Mozilla Add-on" src="https://img.shields.io/amo/users/responsively-helper"></a>
- [Download for Edge](https://microsoftedge.microsoft.com/addons/detail/responsively-helper/ooiejjgflcgkbbehheengalibfehaojn)

## Issues
If you face any problems while using the application, please open an issue here - https://github.com/responsively-org/responsively-app/issues

## Roadmap
Here is the roadmap of the desktop app - https://github.com/responsively-org/responsively-app/projects/12?fullscreen=true.

## Gold sponsors 🥇

<p>&nbsp;</p>

<p align="center">
  <a href="https://opencollective.com/responsively" target="_blank">
    <img src="https://user-images.githubusercontent.com/1283424/142834528-4cd5b8eb-eeae-4437-b749-d09c96dde160.png" height="120px" alt="Sponsor to add your company logo here">
  </a>
</p>


[Become a sponsor and have your company logo here](https://opencollective.com/responsively)

## Contribute
1. Ensure you have installed `node` and `yarn`
2. Go to `desktop-app` folder
3. Run `yarn` to install dependencies
4. Run `yarn dev`. This will start the app for local development with live reloading.

## Get in touch

Come say hi to us on [Discord](https://responsively.app/join-discord)! :wave:

## Contributors ✨

Thanks go to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://twitter.com/vivek_jonam"><img src="https://avatars1.githubusercontent.com/u/1283424?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Manoj Vivek</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=manojVivek" title="Code">💻</a> <a href="https://github.com/responsively-org/responsively-app/commits?author=manojVivek" title="Tests">⚠️</a> <a href="#projectManagement-manojVivek" title="Project Management">📆</a></td>
    <td align="center"><a href="https://github.com/esprush"><img src="https://avatars0.githubusercontent.com/u/26249498?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Suresh P</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=esprush" title="Code">💻</a> <a href="https://github.com/responsively-org/responsively-app/commits?author=esprush" title="Tests">⚠️</a> <a href="#projectManagement-esprush" title="Project Management">📆</a></td>
    <td align="center"><a href="https://github.com/sprabowo"><img src="https://avatars2.githubusercontent.com/u/11748183?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Sigit Prabowo</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=sprabowo" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/leon0707"><img src="https://avatars1.githubusercontent.com/u/523684?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Leon Feng</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=leon0707" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/kishoreio"><img src="https://avatars2.githubusercontent.com/u/30261988?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Kishore S</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=kishoreio" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://jjavierdguezas.github.io"><img src="https://avatars2.githubusercontent.com/u/13673443?v=4?s=100" width="100px;" alt=""/><br /><sub><b>José Javier Rodríguez Zas</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=jjavierdguezas" title="Code">💻</a> <a href="https://github.com/responsively-org/responsively-app/commits?author=jjavierdguezas" title="Tests">⚠️</a></td>
    <td align="center"><a href="https://github.com/romanakash"><img src="https://avatars1.githubusercontent.com/u/40427975?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Roman Akash</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=romanakash" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/RomainFrancony"><img src="https://avatars3.githubusercontent.com/u/22396965?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Romain Francony</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=RomainFrancony" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/AARYAN-MAHENDRA"><img src="https://avatars1.githubusercontent.com/u/64866670?v=4?s=100" width="100px;" alt=""/><br /><sub><b>AARYAN-MAHENDRA</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=AARYAN-MAHENDRA" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Nothing-Works"><img src="https://avatars3.githubusercontent.com/u/18606648?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Andy</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=Nothing-Works" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Kidcredo"><img src="https://avatars0.githubusercontent.com/u/15522605?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ryan Pais</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=Kidcredo" title="Code">💻</a> <a href="https://github.com/responsively-org/responsively-app/commits?author=Kidcredo" title="Tests">⚠️</a></td>
    <td align="center"><a href="https://grafikart.fr"><img src="https://avatars1.githubusercontent.com/u/395137?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jonathan</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=Grafikart" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/heygema"><img src="https://avatars1.githubusercontent.com/u/10743728?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Gema Anggada ✌︎</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=heygema" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/jonathanurias96"><img src="https://avatars2.githubusercontent.com/u/57416786?v=4?s=100" width="100px;" alt=""/><br /><sub><b>jonathanurias96</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=jonathanurias96" title="Code">💻</a></td>
    <td align="center"><a href="https://falecci.dev"><img src="https://avatars2.githubusercontent.com/u/17703824?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Federico Alecci</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=falecci" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://linkedin.com/in/muminjon-abduraimov/"><img src="https://avatars1.githubusercontent.com/u/24930020?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Abduraimov Muminjon</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=MuminjonGuru" title="Documentation">📖</a></td>
    <td align="center"><a href="https://www.vlazaro.es/"><img src="https://avatars1.githubusercontent.com/u/38981659?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Víctor Lázaro</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=vlazaroes" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/kvnam"><img src="https://avatars0.githubusercontent.com/u/3608742?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Kavita Nambissan</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=kvnam" title="Code">💻</a></td>
    <td align="center"><a href="https://twitter.com/PrashantPalikhe"><img src="https://avatars0.githubusercontent.com/u/2657709?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Prashant Palikhe</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=prashantpalikhe" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/jaunesarmiento"><img src="https://avatars1.githubusercontent.com/u/1166928?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jaune Sarmiento</b></sub></a><br /><a href="#content-jaunesarmiento" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/diego-vieira"><img src="https://avatars2.githubusercontent.com/u/930792?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Diego Vieira</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=diego-vieira" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/pajaydev"><img src="https://avatars0.githubusercontent.com/u/21375014?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ajaykumar</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=pajaydev" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/kirubakarthikeyan"><img src="https://avatars0.githubusercontent.com/u/38885946?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Kiruba Karan</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=kirubakarthikeyan" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/sebasrodriguez"><img src="https://avatars1.githubusercontent.com/u/1605931?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Sebastián Rodríguez</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=sebasrodriguez" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/karthick3018"><img src="https://avatars1.githubusercontent.com/u/47154512?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Karthick Raja</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=karthick3018" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/jzabala"><img src="https://avatars0.githubusercontent.com/u/1315054?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Johnny Zabala</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=jzabala" title="Code">💻</a></td>
    <td align="center"><a href="http://rossmoody.com"><img src="https://avatars0.githubusercontent.com/u/29072694?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ross Moody</b></sub></a><br /><a href="#design-rossmoody" title="Design">🎨</a></td>
    <td align="center"><a href="https://shokri.me"><img src="https://avatars1.githubusercontent.com/u/13661520?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mehrdad Shokri</b></sub></a><br /><a href="#infra-mehrdad-shokri" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
    <td align="center"><a href="https://github.com/abakermi"><img src="https://avatars1.githubusercontent.com/u/60294727?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Abdelhak Akermi</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=abakermi" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/crperezt"><img src="https://avatars0.githubusercontent.com/u/20329014?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Carlos Perez</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=crperezt" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/JayArya"><img src="https://avatars0.githubusercontent.com/u/42388314?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jayant Arya</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=JayArya" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/JohnRawlins"><img src="https://avatars3.githubusercontent.com/u/42707277?v=4?s=100" width="100px;" alt=""/><br /><sub><b>John Rawlins</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=JohnRawlins" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/lepasq"><img src="https://avatars3.githubusercontent.com/u/53230128?v=4?s=100" width="100px;" alt=""/><br /><sub><b>lepasq</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=lepasq" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/mrfelfel"><img src="https://avatars0.githubusercontent.com/u/19575588?v=4?s=100" width="100px;" alt=""/><br /><sub><b>mrfelfel</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=mrfelfel" title="Code">💻</a></td>
    <td align="center"><a href="https://twitter.com/gorogoroumaru"><img src="https://avatars3.githubusercontent.com/u/30716350?v=4?s=100" width="100px;" alt=""/><br /><sub><b>gorogoroumaru</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=gorogoroumaru" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://ruisaraiva.dev"><img src="https://avatars2.githubusercontent.com/u/7356098?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Rui Saraiva</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=ruisaraiva19" title="Code">💻</a></td>
    <td align="center"><a href="http://www.bakirci.nl"><img src="https://avatars2.githubusercontent.com/u/9880089?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mehmet Bakirci</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=MBakirci" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/JLambertazzo"><img src="https://avatars0.githubusercontent.com/u/42924425?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Julien Bertazzo Lambert</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=JLambertazzo" title="Code">💻</a></td>
    <td align="center"><a href="http://dbwriteups.wordpress.com"><img src="https://avatars3.githubusercontent.com/u/4656109?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dinesh Balaji</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=sidthesloth92" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/med1001"><img src="https://avatars3.githubusercontent.com/u/26111211?v=4?s=100" width="100px;" alt=""/><br /><sub><b>MedBMoussa</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=med1001" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://www.lucie.dev"><img src="https://avatars.githubusercontent.com/u/46979603?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Lucie Vrsovska</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=lucievr" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/jcabak"><img src="https://avatars.githubusercontent.com/u/1818155?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jakub Cabak</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=jcabak" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/durgakiran"><img src="https://avatars.githubusercontent.com/u/17452039?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Palakurthi Durga Kiran Kumar</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=durgakiran" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/karllabrador"><img src="https://avatars.githubusercontent.com/u/58193703?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Karl Labrador</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=karllabrador" title="Code">💻</a></td>
    <td align="center"><a href="http://rishikc.com"><img src="https://avatars.githubusercontent.com/u/26366288?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Rishi Kumar Chawda</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=rishichawda" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/crocarneiro"><img src="https://avatars.githubusercontent.com/u/10589421?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Carlos Rafael de Oliveira Carneiro</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=crocarneiro" title="Code">💻</a></td>
    <td align="center"><a href="http://zachos.tech"><img src="https://avatars.githubusercontent.com/u/50255197?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Zach Hoskins</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=zachOS-tech" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/kiwan97"><img src="https://avatars.githubusercontent.com/u/25267859?v=4?s=100" width="100px;" alt=""/><br /><sub><b>KIWAN KIM</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=kiwan97" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/agaertner"><img src="https://avatars.githubusercontent.com/u/13819164?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Andreas</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=agaertner" title="Code">💻</a></td>
    <td align="center"><a href="https://www.linkedin.com/in/panu-valtanen-446ba9108/"><img src="https://avatars.githubusercontent.com/u/28947061?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Panu Valtanen</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=p4nu" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://www.d19.ca"><img src="https://avatars.githubusercontent.com/u/8153796?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dustin Dauncey</b></sub></a><br /><a href="https://github.com/responsively-org/responsively-app/commits?author=d19dotca" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

  
  

  
  
  
  
  
  
<h2> 
<h2> 
<h2> 
_-_
<h2> 

  
  
  
  
  
  
  
  
  
  # 💫 About Me:
🤖 I'm currently working on Web3 Project<br>🤝 I'm looking to collaborate on tech workshops/events/content creation<br>📚 I'm currently learning anything that comes up to me on the way


## 🌐 Socials:
[![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/muminjon.abduraimov) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/abduraimovmuminjon) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/muminjon-abduraimov) [![Medium](https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white)](https://medium.com/@muminjonguru) [![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/7365716) [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/MuminjonGuru) [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/c/MuminjonGuru) 

# 💻 Tech Stack:
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Ruby](https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white) ![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=azure-devops&logoColor=white) ![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Rails](https://img.shields.io/badge/rails-%23CC0000.svg?style=for-the-badge&logo=ruby-on-rails&logoColor=white) ![ApacheCassandra](https://img.shields.io/badge/cassandra-%231287B1.svg?style=for-the-badge&logo=apache-cassandra&logoColor=white) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Sever-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) 	![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white) ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase) ![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white) ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=MuminjonGuru&theme=nightowl&hide_border=true&include_all_commits=true&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=MuminjonGuru&theme=nightowl&hide_border=true)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=MuminjonGuru&theme=nightowl&hide_border=true&include_all_commits=true&count_private=true&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=MuminjonGuru&theme=matrix&no-frame=true&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

### 😂 Random Dev Meme
<img src="https://random-memer.herokuapp.com/" width="512px"/>

---

  ## 💰 You can help me by Donating
  [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/MuminjonGuru) 

  <!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
  
  

  
  
  
  
<h2> 
<h2> 
<h2> 
_-_
<h2> 

  
  
  
  
  
  
  
  
  # A simple Timer app for Mac

<img src="/screenshots/light-mode.png?raw=true" width="262" align="right">

<img src="/screenshots/dark-mode.png?raw=true" width="262" align="right">

[Download here](https://github.com/michaelvillar/timer-app/releases)

Drag the blue arrow to set a timer. Release to start! Click to pause.

When the time is up, a notification will show up with a nice sound.

Create new timers with `CMD+N`.

Install as a [brew cask](https://caskroom.github.io) via 

```shell
brew install --cask michaelvillar-timer
```

Inspired by the **great** [Minutes widget](http://minutes.en.softonic.com/mac) from Nitram-nunca I've been using for years. But it wasn't maintained anymore (non-retina) + it was the only widget in my dashboard :)

Timer requires macOS 10.11 or later.

### Build

```
make
```

### Keyboard Shortcuts

Enter digits to set minutes. A decimal point specifies seconds so `2.34` is 2 minutes and 34 seconds.

<kbd>backspace</kbd> or <kbd>escape</kbd> to edit.
<kbd>enter</kbd> to start or pause the timer.
<kbd>cmd</kbd>+<kbd>n</kbd> to create a new timer.
<kbd>r</kbd> to restart with the last timer.
  
  
  
  
  
  
  
  
  
  
  
  
  
<h2> 
<h2> 
<h2> 
_-_
<h2> 

  
  
  
  
  
  
  
  
  
  
  
  # Visual Studio Code - Open Source ("Code - OSS")
[![Feature Requests](https://img.shields.io/github/issues/microsoft/vscode/feature-request.svg)](https://github.com/microsoft/vscode/issues?q=is%3Aopen+is%3Aissue+label%3Afeature-request+sort%3Areactions-%2B1-desc)
[![Bugs](https://img.shields.io/github/issues/microsoft/vscode/bug.svg)](https://github.com/microsoft/vscode/issues?utf8=✓&q=is%3Aissue+is%3Aopen+label%3Abug)
[![Gitter](https://img.shields.io/badge/chat-on%20gitter-yellow.svg)](https://gitter.im/Microsoft/vscode)

## The Repository

This repository ("`Code - OSS`") is where we (Microsoft) develop the [Visual Studio Code](https://code.visualstudio.com) product together with the community. Not only do we work on code and issues here, we also publish our [roadmap](https://github.com/microsoft/vscode/wiki/Roadmap), [monthly iteration plans](https://github.com/microsoft/vscode/wiki/Iteration-Plans), and our [endgame plans](https://github.com/microsoft/vscode/wiki/Running-the-Endgame). This source code is available to everyone under the standard [MIT license](https://github.com/microsoft/vscode/blob/main/LICENSE.txt).

## Visual Studio Code

<p align="center">
  <img alt="VS Code in action" src="https://user-images.githubusercontent.com/35271042/118224532-3842c400-b438-11eb-923d-a5f66fa6785a.png">
</p>

[Visual Studio Code](https://code.visualstudio.com) is a distribution of the `Code - OSS` repository with Microsoft-specific customizations released under a traditional [Microsoft product license](https://code.visualstudio.com/License/).

[Visual Studio Code](https://code.visualstudio.com) combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. It provides comprehensive code editing, navigation, and understanding support along with lightweight debugging, a rich extensibility model, and lightweight integration with existing tools.

Visual Studio Code is updated monthly with new features and bug fixes. You can download it for Windows, macOS, and Linux on [Visual Studio Code's website](https://code.visualstudio.com/Download). To get the latest releases every day, install the [Insiders build](https://code.visualstudio.com/insiders).

## Contributing

There are many ways in which you can participate in this project, for example:

* [Submit bugs and feature requests](https://github.com/microsoft/vscode/issues), and help us verify as they are checked in
* Review [source code changes](https://github.com/microsoft/vscode/pulls)
* Review the [documentation](https://github.com/microsoft/vscode-docs) and make pull requests for anything from typos to additional and new content

If you are interested in fixing issues and contributing directly to the code base,
please see the document [How to Contribute](https://github.com/microsoft/vscode/wiki/How-to-Contribute), which covers the following:

* [How to build and run from source](https://github.com/microsoft/vscode/wiki/How-to-Contribute)
* [The development workflow, including debugging and running tests](https://github.com/microsoft/vscode/wiki/How-to-Contribute#debugging)
* [Coding guidelines](https://github.com/microsoft/vscode/wiki/Coding-Guidelines)
* [Submitting pull requests](https://github.com/microsoft/vscode/wiki/How-to-Contribute#pull-requests)
* [Finding an issue to work on](https://github.com/microsoft/vscode/wiki/How-to-Contribute#where-to-contribute)
* [Contributing to translations](https://aka.ms/vscodeloc)

## Feedback

* Ask a question on [Stack Overflow](https://stackoverflow.com/questions/tagged/vscode)
* [Request a new feature](CONTRIBUTING.md)
* Upvote [popular feature requests](https://github.com/microsoft/vscode/issues?q=is%3Aopen+is%3Aissue+label%3Afeature-request+sort%3Areactions-%2B1-desc)
* [File an issue](https://github.com/microsoft/vscode/issues)
* Connect with the extension author community on [GitHub Discussions](https://github.com/microsoft/vscode-discussions/discussions) or [Slack](https://aka.ms/vscode-dev-community)
* Follow [@code](https://twitter.com/code) and let us know what you think!

See our [wiki](https://github.com/microsoft/vscode/wiki/Feedback-Channels) for a description of each of these channels and information on some other available community-driven channels.

## Related Projects

Many of the core components and extensions to VS Code live in their own repositories on GitHub. For example, the [node debug adapter](https://github.com/microsoft/vscode-node-debug) and the [mono debug adapter](https://github.com/microsoft/vscode-mono-debug) repositories are separate from each other. For a complete list, please visit the [Related Projects](https://github.com/microsoft/vscode/wiki/Related-Projects) page on our [wiki](https://github.com/microsoft/vscode/wiki).

## Bundled Extensions

VS Code includes a set of built-in extensions located in the [extensions](extensions) folder, including grammars and snippets for many languages. Extensions that provide rich language support (code completion, Go to Definition) for a language have the suffix `language-features`. For example, the `json` extension provides coloring for `JSON` and the `json-language-features` extension provides rich language support for `JSON`.

## Development Container

This repository includes a Visual Studio Code Dev Containers / GitHub Codespaces development container.

- For [Dev Containers](https://aka.ms/vscode-remote/download/containers), use the **Dev Containers: Clone Repository in Container Volume...** command which creates a Docker volume for better disk I/O on macOS and Windows.
     - If you already have VS Code and Docker installed, you can also click [here](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/microsoft/vscode) to get started. This will cause VS Code to automatically install the Dev Containers extension if needed, clone the source code into a container volume, and spin up a dev container for use.
- For Codespaces, install the [GitHub Codespaces](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces) extension in VS Code, and use the **Codespaces: Create New Codespace** command.

Docker / the Codespace should have at least **4 Cores and 6 GB of RAM (8 GB recommended)** to run full build. See the [development container README](.devcontainer/README.md) for more information.

## Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](LICENSE.txt) license.
