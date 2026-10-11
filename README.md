# MH3U Armor Skills Explained

Every armor skill in **Monster Hunter 3 Ultimate**: the game's own description, then a detailed explanation
of what the skill actually does — the exact amounts, what counts and what doesn't, the limits per weapon, how
it stacks with other skills, and what isn't confirmed yet. A "How skills activate" page covers points, Torso
Up and the 10-skill limit.

Live: https://armoredraven17.github.io/mh3u-armor-skills-explained/

## Where the numbers come from

The numbers were read from the game's own code and data (a personally-owned copy), not taken from guides, and
not carried over from the MHGU version of this page: Capcom changed things between the games. Community
figures were only used as a check. Where something could not be confirmed, the skill says so under "Not
confirmed yet".

## How it fits the family

Static site served from `docs/`, no build step, deployed to GitHub Pages on push to `master` by
[.github/workflows/deploy-pages.yml](.github/workflows/deploy-pages.yml). It shares the look of the sibling
apps (the MHFU font and the menu textures) and links to the other MH3U apps from the 🔗 button.

`docs/index.html` is generated (with the skill text embedded) from the research notes kept outside this
repository; edit those and regenerate rather than editing the page by hand.

See [NOTICE.md](NOTICE.md) for attributions. Code is MIT-licensed ([LICENSE](LICENSE)).
