# I, Devangelist

![I, Devangelist logo](images/i-devangelist-logo.png)


## Why write the book

The role of a devangelist can be very wide and vary significantly in the minds of those who work in the role, those who work with them and those that interact with them.  So this is my hopefully not to biased view on what a devangelist is all about and where I feel the role can add real value.

I will include stories, tips and common practices used to help make the devangelist role more effective 

## Code of Conduct Safe

A [Code of Conduct](https://en.wikipedia.org/wiki/Code_of_conduct) is now used in most of the public events in the developer world.  It is a simple but important statement about respecting everyone during all interaction with other people, setting out expectations of a minimum level of positive behaviour towards each other.

You can of course be even nicer should you wish.

> "Be excellent to each other" - Bill S. Preston, Esq. - [Bill & Ted's Excellent Adventure](https://en.wikipedia.org/wiki/Bill_%26_Ted's_Excellent_Adventure)

Example code of conduct documents include

* [Battlehack Code of Conduct](http://hackcodeofconduct.org/battlehack_london) by [@CBetta](https://twitter.com/cbetta) - for the Battlehack world wide hackathon events
* [Major League Hacking code of conduct] - worldwide student hacking organisation
* [SkillsMatter Code of Conduct](https://skillsmatter.com/go/code-of-conduct) for all their conferences & community events
* RubyGirls Code of Conduct
* [ClojureBridge] - helping the diverse developer community learn and love Clojure


## Applying Lean Principles & Agile Techniques

Many of the principles and practices I applied as an Agile Coach & developer are equally applicable to developer evangelism.  I will cover these principles and practices throughout the book with examples of how they can be effective. 

## Name of the book

As you may have already guessed the title of the book is a homage to the novel **I, Robot**.  I also subttle draw themes and concepts from the novel [I, Claudius](https://en.wikipedia.org/wiki/I,_Claudius) by [Robert Graves](https://en.wikipedia.org/wiki/Robert_Graves).

## Geekiness throughout

Throughout the book I will also include many common (and possible a few obscure references) popular culture and science fiction works that many in the developer world relate to.  This is not just because I am geeky, but will hopefully help give a context feel less alien and help the reader relate to the concepts & practices covered.

## Audience for the book

This book shares all the experiences I can publicly share as a developer in the community and as a developer ambassador / advocate / evangelist.  Hopefully this will be useful to those:

  * currently working in an devangelist or community type role
  * looking to move into that role
  * wishing to hire a  devangelist team or their first devagelist or technical community focused role

This book is not about marketing or turning a developer into a marketeer.

My own personal view is that devangelists can benefit from marketing techniques to help them reach their audience more effectively, however they are only a complement to your main work.


## Book status

[![MegaLinter](https://github.com/practicalli/clojure/actions/workflows/megalinter.yaml/badge.svg)](https://github.com/practicalli/clojure/actions/workflows/megalinter.yaml)[![Publish Book](https://github.com/practicalli/clojure/actions/workflows/publish-book.yaml/badge.svg)](https://github.com/practicalli/clojure/actions/workflows/publish-book.yaml)
[![Publish Book](https://github.com/practicalli/clojure/actions/workflows/publish-book.yaml/badge.svg)](https://github.com/practicalli/clojure/actions/workflows/publish-book.yaml)
[![pages-build-deployment](https://github.com/practicalli/clojure/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/practicalli/clojure/actions/workflows/pages/pages-build-deployment)

[![Ideas & Issues](https://img.shields.io/github/issues/practicalli/clojure?label=content%20ideas%20and%20issues&logoColor=green&style=for-the-badge)](https://github.com/practicalli/clojure/issues)
[![Pull requests](https://img.shields.io/github/issues-pr/practicalli/clojure?style=for-the-badge)](https://github.com/practicalli/clojure/pulls)

![GitHub commit activity](https://img.shields.io/github/commit-activity/m/practicalli/clojure?style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/practicalli/clojure?style=for-the-badge&label=github%20contributors)

## Creative commons license

<div style="width:95%; margin:auto;">
  <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
  This work is licensed under a Creative Commons Attribution 4.0 ShareAlike License (including images & stylesheets).
</div>

## Contributing

Issues and pull requests are most welcome although it is the maintainers discression as to if they are applicable.  Please detail issues as much as you can.  Pull requests are simpler to work with when they are specific to a page or at most a section.  The smaller the change the quicker it is to review and merge.

Please read the [detailed Practicalli contributing page](https://practical.li/contributing/) before raising an issue or pull request to avoid disapointment.

* [Current Issues](https://github.com/practicalli/clojure/issues)
* [Current pull requests](https://github.com/practicalli/clojure/pulls)

[Practicalli Clojure CLI Config](clojure/clojure-cli/practicalli-config.md) provides a user level configuration providing aliases for community tools used throughout this guide.  Issues and pull requests can also be made via its GitHub repository.

By submitting content ideas and corrections you are agreeing they can be used in any work by Practicalli under the [Creative Commons Attribution ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/).  Attribution will be detailed via [GitHub contributors](https://github.com/practicalli/clojure/graphs/contributors).

## Sponsor Practicalli

[![Sponsor Practicalli via GitHub](https://raw.githubusercontent.com/practicalli/graphic-design/live/buttons/practicalli-github-sponsors-button.png)](https://github.com/sponsors/practicalli-johnny/)

All sponsorship funds are used to support the continued development of [Practicalli series of books and videos](https://practical.li/), although most work is done at personal cost and time.

Thanks to [Cognitect](https://www.cognitect.com/), [Nubank](https://nubank.com.br/) and a wide range of other [sponsors](https://github.com/sponsors/practicalli-johnny#sponsors) for your continued support


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=practicalli/clojure&type=Date)](https://star-history.com/#practicalli/clojure&Date)


## GitHub Actions

The megalinter GitHub actions will run when a pull request is created,checking basic markdown syntax.

A review of the change will be carried out by the Practicalli team and the PR merged if the change is acceptable.

The Publish Book GitHub action will run when PR's are merged into main (or the Practicalli team pushes changes to the default branch).

Publish book workflow installs Material for MkDocs version 9


## Local development

Install mkdocs version 9 using the Python pip package manager

```shell
pip install mkdocs-material=="9.5"
```

Install the plugins used by the Practicalli site using Pip (these are also installed in the GitHub Action workflow)

```shell
pip3 install mkdocs-material mkdocs-callouts mkdocs-glightbox mkdocs-git-revision-date-localized-plugin mkdocs-redirects pillow cairosvg
```

> pillow and cairosvg python packages are required for [Social Cards](https://squidfunk.github.io/mkdocs-material/setup/setting-up-social-cards/)

Fork the GitHub repository and clone that fork to your computer,

```shell
git clone https://github.com/<your-github-account>/<repository>.git
```

Run a local server from the root of the cloned project

```shell
make docs
```

The website will open at <http://localhost:8000>

If making smaller changes, then only rebuild the content that changes, speeding up the local development process

```shell
make docs-changed
```

> NOTE: navigation changes may not be correctly reflected without reloading the page in the web browser or carrying out a full `make docs` build

