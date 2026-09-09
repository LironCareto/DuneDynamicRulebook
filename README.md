# Dune Dynamic Rulebook

A dynamic, integrated rulebook for Gale Force Nine's **Dune** board game and its expansions.

This project combines two excellent existing works:

- the [**Unofficial Revised Dune Rulebook v2.3**](https://boardgamegeek.com/filepage/196513/unofficial-revised-dune-rulebook-v23), compiled by **Vantastic (Van Willis)** and published on BoardGameGeek, which integrates the rules from the base game and its expansions into a single comprehensive reference;
- the dynamic, configurable presentation model of [**BSGRulebook**](https://github.com/jbiatek/BSGRulebook) by **jbiatek**, which allows rule content to be shown or hidden depending on the game setup.

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

This project is based on—and pays tribute to—the excellent [**Unofficial Revised Dune Rulebook v2.3**](https://boardgamegeek.com/filepage/196513/unofficial-revised-dune-rulebook-v23), compiled by **Vantastic (Van Willis)** and published on BoardGameGeek.

That document already does the difficult work of integrating the base game and expansion rules into a single reference. His work is used with his permission.

Changes have been made to adapt the original PDF to this dynamic HTML format and provide additional features and clarifications. These changes reflect my best judgement and were made without input from Vantastic. He has neither reviewed the contents of this rulebook nor supervised the changes, and he is not responsible for any changes made to his original work.

Maintenance of this adaptation is my responsibility. Vantastic has no obligation to review, maintain, or update it.

## Inspiration

The interaction model is inspired by [**BSGRulebook**](https://github.com/jbiatek/BSGRulebook) by **jbiatek**.

BSGRulebook demonstrates how a complex board game with multiple expansions can be represented as a single configurable rulebook whose contents adapt to the chosen game setup.

Dune Dynamic Rulebook applies the same basic idea to Dune.

## Credits

Almost all of the hard work behind this project was done by other people.

The integrated rules compilation comes from the [**Unofficial Revised Dune Rulebook v2.3**](https://boardgamegeek.com/filepage/196513/unofficial-revised-dune-rulebook-v23) by **Vantastic (Van Willis)**.

The inspiration for the configurable, dynamic web-based presentation comes from [**BSGRulebook**](https://github.com/jbiatek/BSGRulebook) by **jbiatek**.

My contribution has mainly been to combine those two pieces: taking the integrated Dune rules and adapting them into a dynamic rulebook interface.

Credit for the original game, rules, compilation, artwork, and presentation inspiration belongs to their respective creators. I am grateful for their work.

## Website

[Open Dune Dynamic Rulebook](https://lironcareto.github.io/DuneDynamicRulebook/).

The website is published with GitHub Pages from the `main` branch and the `/(root)` folder. Each push to `main` updates the website. The `.nojekyll` file serves the HTML and images directly without Jekyll processing.

## License

The original software code contributed to this project is licensed under the [MIT License](LICENSE).

This license applies only to original code, including the HTML structure, CSS, JavaScript, and project scripts. It does not cover game rules or rulebook text, artwork, images, logos, fonts, trademarks, or other third-party material, including such content embedded in `index.html`.

The content adapted from Vantastic’s **Unofficial Revised Dune Rulebook v2.3** is used with his permission under the conditions agreed for this project, including free access, attribution, a link to the original work, and a clear statement that the adaptations are my responsibility. This permission does not place his work under the MIT License.

Third-party materials remain subject to their respective owners’ rights and any applicable licenses. No rights to those materials are granted by this project's MIT License. Vantastic’s permission concerns his contribution to the rulebook and does not grant rights to third-party artwork or other assets.

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

Access to the rulebook is free. No profit is made from this project.

All third-party trademarks, artwork, logos, rulebook content, and other protected materials remain the property of their respective rights holders.

Third-party artwork, images, and logos associated with Gale Force Nine and Dune are included in good faith for reference and fan-created educational use, with the intention of remaining within applicable fair use / fair dealing principles where relevant. No ownership of these assets is claimed, and no permission from their rights holders is implied. Vantastic’s permission to adapt his rulebook does not extend to these assets.

This project is not affiliated with or endorsed by Gale Force Nine or the rights holders associated with Dune. Vantastic has permitted the adaptation of his work as described above; he has not reviewed or approved the contents of this adaptation.

If any rights holder has concerns about the inclusion of specific material, please get in touch.