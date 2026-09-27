<p align="center"><img src="https://files.catbox.moe/qsvsvo.png" width="450"></p>
<h1 align="center">Tale Stars Language Files</h1>
<p align="center">
  <strong><a href="#translation-guidelines">Translation Guidelines</a></strong> •
  <strong><a href="#submitting-a-translation">Submitting a Translation</a></strong> •
  <strong><a href="#thanks-for-translations">Thanks for Translations</a></strong>
</p>

This repository contains Tale Stars’ language files in JSON format. You can contribute by translating Tale Stars into a new language or by fixing translation errors in the existing languages.

## Please Be Careful
Some sections are not included in `en.json`. For example, `modDescriptions` part for mod menu mod descriptions and `modNames` part for their localized names.
Please dont forget to use another language file as a reference for these missing sections and translate them accordingly.
For example:

```json
"modDescriptions": {
    "Locks onto enemies, even through bushes or invisibility": "Автоматически наводится на врагов, даже сквозь кусты или невидимость",
    "Boosts your speed": "Повышает вашу скорость"
    ...
}
```

`ru.json` is just an example here.

## Translation Guidelines
- Do not submit the entire language file to an AI and ask it to translate everything into another language. AIs often translate specific terms poorly.
- Try to keep the translated text reasonably close to the original character length, without making it significantly shorter or longer.
- Pay attention to uppercase and lowercase letters.
- Pay attention to punctuation.
- Do not remove color codes (like `<cff2600>`), `\n` line breaks, or placeholders such as `{value}`.
- If possible review your translation manually before submitting it.

## Submitting a Translation
Once your translation is complete, you can submit it by creating a pull request. If you dont know how to create one, check [GitHub’s guide to creating a pull request](https://docs.github.com/en/pull-requests/how-tos/create-pull-requests/creating-a-pull-request).

## Thanks for Translations
| Language | Contribution | Contributor | Pull Request |
|---|---|---|---|
| 🇷🇺 Russian | Edited Some Parts | [@bezdapb1-ctrl](https://github.com/bezdapb1-ctrl) | [#1](../../pull/1) |
| 🇰🇷 Korean | Completely Added | [@LTL325](https://github.com/LTL325) | [#2](../../pull/2) |
| 🇦🇪 Arabic | Completely Added | [@i32r](https://github.com/i32r) | [#3](../../pull/3) |
| 🇧🇷 Brazilian Portuguese | Completely Added | [@rwz0000](https://github.com/rwz0000) | [#4](../../pull/4) |
| 🇩🇪 German | Completely Added | [@m8rneco-a11y](https://github.com/m8rneco-a11y) | [#5](../../pull/5) |
| 🇨🇳 Chinese | Completely Added | [@Aur5411](https://github.com/Aur5411) | [#7](../../pull/7) |
| 🇫🇷 French | Completely Added | [@mydd7](https://github.com/mydd7) | [#10](../../pull/10) |
