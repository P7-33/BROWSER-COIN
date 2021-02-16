

# Contributing

jasonlong/isometric-contributions
Hi there! We're excited you've got ideas to improve topics and collections. You're helping the community discover valuable information.

This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

There are a few ways you can contribute:

As you write content, check out the [Style Guide](./docs/styleguide.md) to learn what each field means, and how they should be formatted. Following the style guide will improve the chances of your contribution being accepted.

Note: Updates won't immediately appear once we've merged your PR. We pull in these changes regularly to GitHub.

## Improving an existing topic or collection

If a topic or collection already exists, it will be listed in its respective directory:

The topic or collection name should match its URL, e.g. `https://github.com/topics/rails` corresponds to th

To make an improvement, please **open a pull request** with your proposed changes:

### Update the image

To update the image, simply replace the image inside the directory for the topic or collection.

### Update text and links

To update text and links, edit the `index.md` inside the topic or collection's directory. These files are formatted using a combination of [Front Matter](https://jekyllrb.com/docs/frontmatter/) and simple body content.

For **topics**, you'll notice that, in examples like the topic "[algorithm](https://raw.githubusercontent.com/github/explore/master/topics/algorithm/index.md)," data like its canonical URL, Wikipedia URL, or display name are called out in key-value pairs; while its detailed description is accounted for in the body of the document.

_/topics/algorithm/index.md_:
```
---
aliases: algorithms
display_name: Algorithm
short_description: Algorithms are self-contained sequences that carry out a variety of tasks.
topic: algorithm
wikipedia_url: https://en.wikipedia.org/wiki/Algorithm
---
Algorithms are detailed sets of guidelines created for a computer program to complete tasks efficiently and thoroughly.
```

---

Similarly, **collections** like "[music](https://raw.githubusercontent.com/github/explore/master/collections/music/index.md)" call out things like their author and display name in Front Matter variables -- with a detailed description in the body of the document. Most importantly, though, collections identify their individual collection items in [a YAML list](https://en.wikipedia.org/wiki/YAML#Basic_components) for the key "items."

_/collections/music/index.md_:

```
---
items:
 - beetbox/beets
 - scottschiller/SoundManager2
 - CreateJS/SoundJS
 - musescore/MuseScore
 - tomahawk-player/tomahawk
 - cashmusic/platform
 - mopidy/mopidy
 - AudioKit/AudioKit
 - Soundnode/soundnode-app
 - gillesdemey/Cumulus
 - metabrainz/picard
 - overtone/overtone
 - samaaron/sonic-pi
display_name: Music
created_by: jonrohan
---
Drop the code bass with these musically themed repositories.
```
---
items:

 - Yatser/prettypullrequests
 - sanemat/do-not-merge-wip-for-github
 - jasonlong/isometric-contributions
 - ForbesLindesay/github-real-names
 - benbalter/github-mention-highlighter
 - sindresorhus/notifier-for-github
 - OctoLinker/OctoLinker
 - ProLoser/Github-Omnibox
 - Justineo/github-hovercard
 - panzerdp/clipboardy
 - zenorocha/codecopy
 - kamranahmedse/githunt
 - harshjv/github-repo-size
 - sindresorhus/refined-github
 - softvar/enhanced-github
 - bitoiu/markwrap
 - bitoiu/github-red-alert
 - Kibibit/achievibit
 - marpo60/github-compare-tags
 - cheshire137/hubnav
 - ryanflorence/github-plusone-extension
 - Mottie/GitHub-userscripts
 - rgehan/octolenses
 - homerchen19/github-file-icons
 - StylishThemes/GitHub-Dark
 - xthexder/wide-github
 - berzniz/github_pr_tree
 - n1ck/gifs-for-github
 - EnixCoda/Gitako
 - vladgolubev/quickreview-for-github
 - matthizou/github-show-avatars
display_name: GitHub Browser Extensions
created_by: leereilly
---
Some useful and fun browser extensions to personalize your GitHub browser experience.

---

The [pull request template](./.github/PULL_REQUEST_TEMPLATE.md) also provides guidance on the information you need to include.

**Please fill out the pull request template completely.** If you do not fill out the template, your PR will be closed.

## Curating a new topic or collection

If a topic or collection is not yet curated, it will NOT be listed in its respective directory.

We are likely to consider suggestions to curate a topic or collection that is valuable to GitHub's community. Valuable topics, for example, include those that are already [widely used by repositories](https://help.github.com/articles/classifying-your-repository-with-topics/) and could benefit from the addition of important information. When suggesting content, please consider how to make your contribution broadly useful and relevant to others, rather than serving a specific use case.

Please note that all suggestions must adhere to GitHub's [Community Guidelines](https://help.github.com/articles/github-community-guidelines/) and [Terms of Service](https://help.github.com/articles/github-terms-of-service/). Per our Terms of Service, [you are responsible](https://help.github.com/articles/github-terms-of-service/#d-user-generated-content) for the content you contribute, and you must have the rights to use it.

To propose a new topic or collection, please **open a pull request** with your proposed additions. The [API docs](./docs/API.md) and [style guide](./docs/styleguide.md) provide guidance on the information you need to include and how it should be formatted.

This repository includes [a list of the most-used GitHub topics that don't yet have extra context](topics-todo.md). If your pull request adds one of these topics, please update topics-todo.md so that the topic is checked (marked complete).

**Please fill out the pull request template completely.** If you do not fill out the template, your pull request will be closed.

## Guidelines

* Avoid conflicts of interest. Maintainers of a project cannot add a topic or collection for their own project. If a topic is popular enough to warrant inclusion, someone else will add or improve it.

## Running tests

There are some lint tests in place to ensure each topic is formatted in the way we expect. Travis
CI will run the tests automatically. If you want to run the tests yourself locally, you will need
Ruby and Bundler installed.

You can run the tests using:

```bash
script/cibuild
```
Skip to content
github
/
explore
Code
Pull requests
2
Actions
Security
Insights
explore/collections/probot-apps/index.md
@brandonrosage
brandonrosage updated img reference
 1 contributor
 59 lines (59 sloc)  2.48 KB
 
items	display_name	created_by	image
https://probot.github.io/apps/wip/

https://probot.github.io/apps/todo/
https://probot.github.io/apps/welcome/
https://probot.github.io/apps/settings/
https://probot.github.io/apps/request-info/
https://probot.github.io/apps/delete-merged-branch/
https://probot.github.io/apps/unfurl-links/
https://probot.github.io/apps/no-response/
https://probot.github.io/apps/move/
https://probot.github.io/apps/sentiment-bot/
https://probot.github.io/apps/commitlint/
https://probot.github.io/apps/triage-new-issues/
https://probot.github.io/apps/semantic-pull-requests/
https://probot.github.io/apps/weekly-digest/
https://probot.github.io/apps/support/
https://probot.github.io/apps/update-docs/
https://probot.github.io/apps/pr-triage/
https://probot.github.io/apps/ooo/
https://probot.github.io/apps/auto-assign/
https://probot.github.io/apps/remove-outside-collaborators/
https://probot.github.io/apps/background-check/
https://probot.github.io/apps/close-issue/
https://probot.github.io/apps/similar-code-searcher/
https://probot.github.io/apps/duplicator/
https://probot.github.io/apps/deploy/
Probot apps
brandonrosage
probot-apps.png
Use these pre-built apps to extend GitHub and automate your workflow.

© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
