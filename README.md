# Starpaw Arena

An early browser prototype from **RingGam Studio**.

Starpaw Arena is a colorful real-time card battler starring fantasy cats. Assemble an eight-card deck, spend regenerating Nyanergy to deploy units, buildings, and spells, and battle AI opponents across two lanes. Protect your towers while pushing toward the enemy Nyan Castle.

## Play

Play the prototype: https://ringgam-studio.upbeat-lime-9149.chatgpt.site/games/starpaw-arena/

Studio domain: https://ringgam.com (DNS connection pending).

Run locally with Python 3:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000/ in a desktop browser with a mouse and keyboard. JavaScript is required.

## What is in this build

- Customizable eight-card decks
- Fantasy cat units, buildings, and spells
- Two-lane tower battles against AI opponents
- Mouse-based card deployment and range previews

## Controls

| Input | Action |
| --- | --- |
| 1–4 | Select a card |
| Left mouse / drag | Deploy a selected card / drag a card into the arena |
| Right mouse | Cancel selection |
| Space (hold) | Show ranges |
| Esc | Cancel or pause |

Battles are against AI opponents. This prototype does not offer online multiplayer.

## Development status

Experimental prototype, shared as part of RingGam's early game development. The supplied HTML build was developed with an AI-assisted workflow including Claude. This repository publishes that build; it is not a claim that a commercial release or online service is available.

The games use browser-local storage for settings, saves, or records. Hosted web fonts may require an internet connection; fallback fonts are provided by the original build.

## Credits and permissions

RingGam Studio. Contact: founder1@ringgam.com.

No open-source license is granted for RingGam's original game code or artwork by this publication. Third-party software retains its own license; see `THIRD_PARTY_NOTICES.txt`.
