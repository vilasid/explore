# Contributing### Keybase proof

I hereby claim:

  * I am vilasid on github.
  * I am vilasid (https://keybase.io/vilasid) on keybase.
  * I have a public key ASCqMvQ3ERN6c2LBOCy3rwpgQitulJplZvonqDzVn2OYDQo

To claim this, I am signing this object:

```json
{
  "body": {
    "key": {
      "eldest_kid": "0120aa32f43711137a7362c1382cb7af0a60422b6e949a6566fa27a83cd59f63980d0a",
      "host": "keybase.io",
      "kid": "0120aa32f43711137a7362c1382cb7af0a60422b6e949a6566fa27a83cd59f63980d0a",
      "uid": "f49a1a19a8a30af9e9273dd81f249e19",
      "username": "vilasid"
    },
    "merkle_root": {
      "ctime": 1568137992,
      "hash": "4e51cdd6989e84c3daba14dcd1aca5a9254197f5841b79a0f9440efed83f2d5eab65337bc395154beb47a87a9668e301214c93cd3e240437fe1e6cabea70e01b",
      "hash_meta": "2e286fb3e6c10d242eda780162f7fec946345d6ee07860958c69de9af3a81b35",
      "seqno": 6481522
    },
    "service": {
      "entropy": "gM0fiQMiW1j4KG79FGtwCXp+",
      "name": "github",
      "username": "vilasid"
    },
    "type": "web_service_binding",
    "version": 2
  },
  "client": {
    "name": "keybase.io go client",
    "version": "4.4.0"
  },
  "ctime": 1568138000,
  "expire_in": 504576000,
  "prev": "808333d0a4244147793db6cece083dfc4696a752cf46dbf05db7934d5fb04231",
  "seqno": 17,
  "tag": "signature"
}
```

with the key [ASCqMvQ3ERN6c2LBOCy3rwpgQitulJplZvonqDzVn2OYDQo](https://keybase.io/vilasid), yielding the signature:

```
hKRib2R5hqhkZXRhY2hlZMOpaGFzaF90eXBlCqNrZXnEIwEgqjL0NxETenNiwTgst68KYEIrbpSaZWb6J6g81Z9jmA0Kp3BheWxvYWTESpcCEcQggIMz0KQkQUd5PbbOzgg9/EaWp1LPRtvwXbeTTV+wQjHEIDyvoCS2NyC5zJE5AXTDxQTVM7KTim2wIs1zlyaeOPCDAgHCo3NpZ8RAXwhGXV1yfneZ0rqcNOelmlPnVhPRb44ElgN0J66bQwWfEqRl1y6dqRmSmIXoZEa/jxckP6fnPCqnnZSj8OZxAahzaWdfdHlwZSCkaGFzaIKkdHlwZQildmFsdWXEIJtftya+F4Q1nxmXhPyBMKEEBEa/5rA3K6Bghs7zS+yeo3RhZ80CAqd2ZXJzaW9uAQ==

```

And finally, I am proving ownership of the github account by posting this as a gist.

### My publicly-auditable identity:

https://keybase.io/vilasid

### From the command line:

Consider the [keybase command line program](https://keybase.io/download).

```bash
# look me up
keybase id vilasid
```

Hi there! We're excited you've got ideas to improve topics and collections. You're helping the community discover valuable information.

This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

There are a few ways you can contribute:

- Improving an existing topic or collection
- Curating a new topic or collection

As you write content, check out the [Style Guide](./docs/styleguide.md) to learn what each field means, and how they should be formatted. Following the style guide will improve the chances of your contribution being accepted.

Note: Updates won't immediately appear once we've merged your PR. We pull in these changes regularly to GitHub.

## Improving an existing topic or collection

If a topic or collection already exists, it will be listed in its respective directory:

- [topics/](https://github.com/github/explore/tree/master/topics)
- [collections/](https://github.com/github/explore/tree/master/collections)

The topic or collection name should match its URL, e.g. `https://github.com/topics/rails` corresponds to the [`topics/rails` directory](https://github.com/github/explore/tree/master/topics/rails).

To make an improvement, please **open a pull request** with your proposed changes:

### Update the image

To update the image, simply replace the image inside the directory for the topic or collection.

### Update text and links

To update text and links, edit the `index.md` inside the topic or collection's directory. These files are formatted using a combination of [Front Matter](https://jekyllrb.com/docs/frontmatter/) and simple body content.

For **topics**, you'll notice that, in examples like the topic "[algorithm](https://raw.githubusercontent.com/github/explore/master/topics/algorithm/index.md)," data like the its canonical URL, Wikipedia URL, or display name are called out in key-value pairs; while its detailed description is accounted for in the body of the document.

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

The [pull request template](./.github/PULL_REQUEST_TEMPLATE.md) also provides guidance on the information you need to include.

**Please fill out the pull request template completely.** If you do not fill out the template, your PR will be closed.

## Curating a new topic or collection

If a topic or collection is not yet curated, it will NOT be listed in its respective directory.

We are likely to consider suggestions to curate a topic or collection that is valuable to GitHub's community. Valuable topics, for example, include those that are already [widely used by repositories](https://help.github.com/articles/classifying-your-repository-with-topics/), or a topic that currently lacks important information. When suggesting content, please consider how to make your contribution broadly useful and relevant to others, rather than serving a specific use case.

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
