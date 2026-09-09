# Dune Dynamic Rulebook

A dynamic, integrated rulebook for Gale Force Nine's **Dune** board game and its expansions.

This project combines two excellent existing works:

- the [**Unofficial Revised Dune Rulebook v2.3**](https://boardgamegeek.com/filepage/196513/unofficial-revised-dune-rulebook-v23), published on BoardGameGeek, which integrates the rules from the base game and its expansions into a single comprehensive reference;
- the dynamic, configurable presentation model of [**BSGRulebook**](https://github.com/jbiatek/BSGRulebook), which allows rule content to be shown or hidden depending on the game setup.

The goal is simple:

> **The rulebook should describe the game you are actually playing, not every possible version of the game at once.**

## What this project does

Dune has a large number of faction-specific exceptions, expansion rules, optional modules, and interactions between them.

The original rules are spread across the base game and several expansions, which means players often need to remember:

- which faction modifies a general rule;
- which phase an ability affects;
- whether a rule changes when a specific faction is in play;
- which expansion introduced a given exception;
- which optional modules are currently active.

Dune Dynamic Rulebook aims to turn all of that into a single web-based reference.

Instead of treating faction rules and expansion rules as separate appendices, the rulebook integrates them directly into the relevant sections of play.

For example, a general rule can show the normal procedure while also displaying the exceptions that apply when specific factions are present.

## Dynamic content

The rulebook is designed so that game content can be enabled or disabled according to the current setup.

This makes it possible to hide rules that are irrelevant to a particular game and keep only the information that actually matters.

The long-term goal is to support dynamic filtering for things such as:

- factions;
- expansion content;
- optional modules;
- faction-specific advantages and exceptions;
- Karama-related abilities;
- other setup-dependent rules.

## Rules basis

The rules content is based on the excellent [**Unofficial Revised Dune Rulebook v2.3**](https://boardgamegeek.com/filepage/196513/unofficial-revised-dune-rulebook-v23) available on BoardGameGeek.

That document already does the difficult work of integrating the base game and expansion rules into a single reference.

Dune Dynamic Rulebook uses that integrated ruleset as its foundation and adapts it to a dynamic web format.

## Inspiration

The interaction model is inspired by [**BSGRulebook**](https://github.com/jbiatek/BSGRulebook) by jbiatek.

BSGRulebook demonstrates how a complex board game with multiple expansions can be represented as a single configurable rulebook whose contents adapt to the chosen game setup.

Dune Dynamic Rulebook applies the same basic idea to Dune.

## Credits

Almost all of the hard work behind this project was done by other people.

The rules content comes from the [**Unofficial Revised Dune Rulebook v2.3**](https://boardgamegeek.com/filepage/196513/unofficial-revised-dune-rulebook-v23) on BoardGameGeek.

The idea of a configurable, dynamic web-based rulebook comes from [**BSGRulebook**](https://github.com/jbiatek/BSGRulebook) by jbiatek.

My contribution has mainly been to combine those two pieces: taking the integrated Dune rules and presenting them through a dynamic rulebook interface.

All credit for the original rules research, editing, layout, and interaction concept belongs to their respective creators.

## Website

[Open Dune Dynamic Rulebook](https://lironcareto.github.io/DuneDynamicRulebook/).

The website is published with GitHub Pages from the `main` branch and the `/(root)` folder. Each push to `main` updates the website. The `.nojekyll` file serves the HTML and images directly without Jekyll processing.

## License

The original software code contributed to this project is licensed under the [MIT License](LICENSE).

This license applies only to original code, including the HTML structure, CSS, JavaScript, and project scripts. It does not cover game rules or rulebook text, artwork, images, logos, fonts, trademarks, or other third-party material, including such content embedded in `index.html`. Those materials remain subject to their respective owners' rights and any applicable licenses. No rights to third-party material are granted by this project's MIT license.

## Current status

This project is a work in progress.

The current version already includes:

- integrated advanced rules;
- faction-specific rules embedded directly in the relevant sections;
- faction symbols and visual markers;
- Karama indicators;
- dynamically generated Karama badges;
- faction reference sheets;
- responsive layouts for different screen sizes;
- multi-column presentation on larger displays.

More dynamic filtering and setup controls are still being added.

## Design goals

The project tries to follow a few simple principles:

- keep the rules close to the structure of the original Dune manuals;
- preserve the integrated work of the revised rulebook;
- show faction exceptions where the underlying rule appears;
- avoid forcing players to cross-reference several manuals;
- hide irrelevant information whenever possible;
- keep the interface useful during actual play;
- remain readable on both desktop and tablet screens.

## Disclaimer

This is an unofficial, non-commercial fan project created solely as a reference aid for owners and players of the game.

No profit is made from this project, and no commercial use is intended.

All trademarks, game rules, artwork, logos, and other intellectual property remain the property of their respective owners.

Any copyrighted material included in this project is used in good faith for purposes such as reference, commentary, preservation, and fan-created educational use, with the intention of remaining within applicable fair use / fair dealing principles where relevant.

This project is not affiliated with or endorsed by Gale Force Nine or any of the rights holders associated with Dune.

If any rights holder has concerns about the inclusion of specific material, please get in touch.