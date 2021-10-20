Contributing to Debatekeeper formats
====================================

Thank you for considering submitting a contribution to the official Debatekeeper debate formats repository!

This page has some information about what you agree to by submitting your debate format, and what you can expect to happen after your contribution is accepted ("merged").

> This page is primarily written for an audience not already familiar with open-source licences. If you're familiar with open source conventions, there's probably nothing new to you on this page.


Contributions of debate style format files
------------------------------------------

### Licence information

First, some legal stuff. By submitting to this repository, you're agreeing to have your contributions licensed under the MIT License. You can see the licence text in [the LICENCE.md](https://github.com/czlee/debatekeeper-formats/tree/main/LICENCE.md) file.

As a definitely-not-legal-advice summary, this licence allows anyone to use all code in this repository without restriction, subject only to a requirement to retain copyright and licence information. This _includes_ use for purposes other than Debatekeeper, and it _includes_ commercial uses. For example, if someone wants to use the format files in this repository in a new debating app, they're allowed to do so.

If you'd like to discuss any of this, please feel free to send me an email (probably somewhere on [my GitHub profile](https://github.com/czlee/).)

> Note that the [Debatekeeper app itself](https://github.com/czlee/debatekeeper) is licensed under a different licence (GPL-3.0).

### How to submit a new format

First, write your XML file [according to these specifications](https://github.com/czlee/debatekeeper/wiki/Writing-your-own-custom-debate-format-file), and test it by importing it into your phone and running it through a few debates.

1. **Fork** this repository (click the button in the top-right of this page).
2. In your fork, **add** your file to the "[v1/formats](https://github.com/czlee/debatekeeper-formats/tree/main/v1/formats)" directory.
3. Submit a **pull request** from your fork to this repository.

> A "fork" is a copy of a repository that you manage. A "pull request" is a proposed change.

It's helpful if you can provide a bit of information about where the league, circuit or tournaments where your format is used.

### What happens when you submit

This repository has some scripts that run automatically on all pull requests. These scripts
- check that the debate style format files are well-formed, and
- regenerate the list of formats that Debatekeeper first checks when a user opens the Downloads page in the app.

The pull request will show whether the checks succeeded.

_Note:_ Because this is the official repository, the scripts are stricter than the app. So the file might work on your device, but still fail the checks in this repository. If this happens, check the errors and see if you can fix them in your fork. If the errors are confusing to you, don't hesitate to ask by commenting on your pull request.

### When will my format become available on Debatekeeper?

After I merge your pull request, your format will become available via Debatekeeper's downloads function after GitHub Pages regenerates the website. This normally takes just 1–2 minutes.

Users do _not_ need to update the app before they can access the new file.

Depending on how busy I am with life, it might take a while for me to attend to your pull request. I apologise in advance. Before this repository was introduced in 2021, some contributions sat around for years; I'm hoping this new system will reduce to that a few days. Indeed, the purpose of the above scripts (and this online repository) is to make this a one-click process for me so that I can do it quickly.

Contributions of other code
---------------------------

Nothing of unusual significance here. All of the above also applies to new code—it's also licensed under the MIT License, and should be submitted in a pull request as usual. The main purpose of this page was to provide a guide for people who don't have an extensive coding background. 🙂