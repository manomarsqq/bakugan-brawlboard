# Brawl Board Builder

Make Bakugan brawl boards for your AO3 fic by clicking and typing — no code to write. It follows the *Battle Brawlers* rules: each brawler has three Bakugan, three Gate Cards and three Ability Cards.

## What it does

- Shows the whole brawl: a row of Gate Card spaces with each side's Bakugan standing on them, every brawler's plate (name, Bakugan balls, how many are left) and hand of cards, and an optional message box ("Gate Card, open!").
- Gate Cards can be set face-down or opened; Ability Cards can be in hand, activated (they glow) or used. A Bakugan can be ready, standing on a Gate Card, defeated, or lost to the Doom Dimension, and a badge can show that a Doom Card is set.
- **Battle meter:** pick the Gate Card the battle is on, and the board adds up each side's G-Power, shows who's ahead, and lists what the open Gate Card and the activated Ability Cards do.
- **Tag battles** (two against two): every brawler has their own Bakugan and cards; partners' strips sit on the outside, and each Bakugan on the field says whose it is. **Battle royale:** three or four brawlers, each with their own colour, everyone for themselves.
- **Look up** fills in a Bakugan from the [Bakugan Wiki](https://bakugan.fandom.com/): its attribute, G-Power, its abilities from the anime, and a choice of pictures from its page. One click gives those abilities to its brawler's Ability Cards. Typing a Gate Card's or Ability Card's name fills in its type, attribute and effect.
- Pointing at a Bakugan, one of its balls, or a face-up card (or tapping it on a phone) shows an info panel.
- A **battle log line** for the story between boards, with the G-Power change worked out for you.
- **Copy board code** gives you HTML to paste into your chapter (in AO3's HTML mode). Paste a board back in to keep editing it next round.

## Using it on AO3

1. **Once per work:** copy the Work Skin (the button in the builder), create it under *Dashboard → Skins → My Work Skins → Create Work Skin*, and select it on your work's Edit page.
2. Build your board, press **Copy board code**, and paste it into your chapter with the editor in **HTML** mode.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The builder. Everything it needs, including the commented Work Skin, is inside this one file. |

## Secret cards

Readers never see the names of cards still in a hand or set face-down. The names stay in the board's HTML, hidden, so the builder can load the board back in, which means anyone reading your chapter's HTML source could find them. To keep a card truly secret, leave its name empty until it's revealed.

## Pictures

AO3 can't store images, so boards link to pictures hosted elsewhere. Look up picks a picture from the Bakugan's wiki page, linked in the short form (without `/revision/latest…` on the end), which is the form the wiki lets other websites show. If you paste a wiki picture link with that ending, the builder shortens it for you.

The wiki could change what other websites may show at any time. To be safe, save the picture, upload it to an image host, and paste the **direct** link (it usually ends in `.png` or `.jpg`).

The wiki's text is shared under CC BY-SA. Bakugan and its pictures belong to their owners; this is a fan tool.
