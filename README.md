# 5e 2024 (5.5e) Statblock Template Guide
**Download & automatic installer instructions at the bottom!**

## The Template
- This template is designed for Atlas' native statblocks, which are currently an experimental feature. To enable it, open a scene, click the command button (⌘) in the toolbar, and search for "Experimental Features," then enable "Statblock editor."
- You can install the template and snippets automatically via the **Statblock Template Installer for Atlas** plugin (see [Automatic Installation](#automatic-installation-recommended) below), or manually place the `.atlastemplate` file inside a `statblock-templates` folder in your Obsidian vault. You can create statblocks based on the template by right-clicking any folder, choosing "New statblock here," and choosing this template.
- It is designed for D&D 5.5e, also called 5e 2024.
- It is included in this repository as `5e-2024-Character-Sheet.atlastemplate`.

### Points of Confusion
- Skill proficiency is denoted by the diamond next to each skill:
> ◇ = Not proficient
>
> ⬖ = Half-proficiency (e.g., Jack of All Trades)
>
> ◆ = Proficient
>
> ❖ = Expertise
- The spellcasting section stays hidden until a spellcasting ability is chosen to save space for non-spellcasters.
- Many fields are automatically calculated based on other fields, like the skills. Skills can be given a fixed value by using the `<skill>_override` field, but note that this will make the proficiency bonus not apply.
- The proficiency bonus can be applied to any roll by toggling the button next to the proficiency bonus field before the roll.

## Known Issues
- I have not tested the template with the closed beta feature of Atlas called Atlas Online, or the unofficial community plugin Connect for Atlas. I have received multiple reports of the template displaying badly in both of those, but I do not plan to investigate the issue until the official Online feature is in a full release for stability reasons.
- Atlas currently does not support adding dice rolls to other dice rolls with a button like the proficiency bonus. That means the bonus dice field cannot be automatically added to rolls.

## Additional Features
### Themes
- I have created multiple themes using Obsidian's built-in CSS snippets to make the statblock more visually appealing. All of these are optional and do not affect functionality, but I personally use the `5e-parchment.theme.css` snippet.
- If you use the automatic installer plugin, all themes are downloaded into `.obsidian/snippets/` automatically. To install them manually, download your theme(s) of choice from the tables below (or [here](https://discord.com/channels/1551361618305224816/1565541195189325984)). Open Obsidian's settings, click "Appearance," then click "CSS snippets," then click the folder icon to open the snippets folder. Drop the theme(s) you downloaded into that folder, refresh the Obsidian settings if needed, and toggle the snippet on. **Only use one theme at a time.**

### Functional Snippets
- I made a CSS snippet (`two-column-hover.css`) to force statblock previews (the ones that show up when you hover over a token in a scene) to have two columns for readability. Download it below or [here](https://discord.com/channels/1551361618305224816/1566157149279887531) and install it the same way as the themes.
- I made a CSS snippet (`spellcasting-metric-box.css`) to make the core spellcasting attributes of a character (ability, attack bonus, and save DC) appear in a box similar to the box that AC, initiative, and movement speed appear in. I haven't found a way to actually put them in the same type of box due to limitations with Atlas' statblock system, so this is a workaround for now. Download it below or [here](https://discord.com/channels/1551361618305224816/1562121042963472498/1572311872919830690) and install it the same way as the themes.
- I made a CSS snippet (`aligned-skills.css`) to make the skills section display more neatly, which is a workaround similar to the previous snippet. Download it below or [here](https://discord.com/channels/1551361618305224816/1562121042963472498/1572314007996600362) and install it the same way as the themes.

### Integrations
- This character sheet is the basis of [the D&D Beyond importer plugin](https://community.obsidian.md/plugins/dndbeyond-importer-for-atlas) by @young_george from the Discord.
- Also by @young_george, this repo is intended to work with the [Statblock Template Installer for Atlas](https://community.obsidian.md/plugins/statblock-template-installer-for-atlas). More about that below.

### Modified Sheets
- You can modify this sheet to play homebrewed or other modified versions of D&D like Mage Hand Press' sci-fi version, Dark Matter. I modified this template for Dark Matter already—it is included in this repository as `Dark-Matter-Character-Sheet.atlastemplate` (and posted [here](https://discord.com/channels/1551361618305224816/1572354559685435442)).

---

# Downloads

## Automatic Installation (Recommended)
If you use the **[Statblock Template Installer for Atlas](https://community.obsidian.md/plugins/statblock-template-installer-for-atlas)** community plugin, you can install and update all templates, layout snippets, and themes in one step:
1. Open Obsidian **Settings → Statblock Template Installer for Atlas**.
2. Click the **`+`** button next to **Templates**.
3. Paste this repository URL and click **Install**:
   ```text
   https://github.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet
   ```
4. All `.atlastemplate` files will be installed into `atlas-vtt/statblock-templates/`, and all `.css` files will be placed into `.obsidian/snippets/` (but will be disabled by default; enable your chosen layout snippets and **one** theme under **Settings → Appearance → CSS snippets**).
5. To check for updates later, click the **refresh (`↻`)** icon in the plugin's settings tab.

*(Note: If you previously installed files manually under different filenames, delete the old files before running the plugin so you don't end up with duplicates.)*

## Manual Downloads
> **How to download individual files:** Click **View** on any file below and press the **Download raw file** button (the downward arrow icon in the top-right corner of the code box), or right-click **Download** and choose **Save Link As...**. If you want everything at once, grab the ZIP from the [Releases](https://github.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/releases) page on the right sidebar.

### Statblock Templates
Place your chosen `.atlastemplate` file inside `<Your Vault>/statblock-templates/` (or `<Your Vault>/atlas-vtt/statblock-templates/`).

| Template | Ruleset | View File | Direct Download |
| :--- | :--- | :--- | :--- |
| **5e (2024) Core** | D&D 5.5e (SRD 5.2.1) | [5e-2024-Character-Sheet.atlastemplate](5e-2024-Character-Sheet.atlastemplate) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/5e-2024-Character-Sheet.atlastemplate) |
| **Dark Matter** | 5.5e + Mage Hand Press Sci-Fi | [Dark-Matter-Character-Sheet.atlastemplate](Dark-Matter-Character-Sheet.atlastemplate) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/Dark-Matter-Character-Sheet.atlastemplate) |

### Functional Layout Snippets (Optional; all are recommended)
Place inside `<Your Vault>/.obsidian/snippets/` and toggle on in **Settings → Appearance → CSS snippets**. You can enable any combination of these alongside a theme.

| Snippet | Purpose | View File | Direct Download |
| :--- | :--- | :--- | :--- |
| **Aligned Skills** | Aligns skill proficiency diamonds, names, and modifiers into tight columns | [aligned-skills.css](aligned-skills.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/aligned-skills.css) |
| **Spellcasting Metric Box** | Styles Ability, Save DC, and Atk Bonus to match the Combat & Defense box | [spellcasting-metric-box.css](spellcasting-metric-box.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/spellcasting-metric-box.css) |
| **Two-Column Hover Preview** | Forces token hover previews in scenes to render in two columns | [two-column-hover.css](two-column-hover.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/two-column-hover.css) |

### Visual Themes (Optional; enable only one)
Place inside `<Your Vault>/.obsidian/snippets/` and enable **one** theme at a time.

| Theme | Aesthetic | View File | Direct Download |
| :--- | :--- | :--- | :--- |
| **5e Parchment** | Classic PHB vellum & crimson ink | [5e-parchment.theme.css](5e-parchment.theme.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/5e-parchment.theme.css) |
| **Astral** | Navy & celestial gold | [astral.theme.css](astral.theme.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/astral.theme.css) |
| **Crystal** | Indigo & violet/cyan (suggested by @catapulttv in the Discord) | [crystal.theme.css](crystal.theme.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/crystal.theme.css) |
| **Gilded Obsidian** | Matte black & gold foil | [gilded-obsidian.theme.css](gilded-obsidian.theme.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/gilded-obsidian.theme.css) |
| **Gothic** | Crimson | [gothic.theme.css](gothic.theme.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/gothic.theme.css) |
| **Ice** | Glacial & cyan fractures | [ice.theme.css](ice.theme.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/ice.theme.css) |
| **Infernal** | Fiery ash & ember orange | [infernal.theme.css](infernal.theme.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/infernal.theme.css) |
| **Modern Blue** | Modern & sky-blue | [modern-blue.theme.css](modern-blue.theme.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/modern-blue.theme.css) |
| **Steampunk** | Metal & warm brass | [steampunk.theme.css](steampunk.theme.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/steampunk.theme.css) |
| **Sylvan Woodcraft** | Forest bark, moss & amber | [sylvan-woodcraft.theme.css](sylvan-woodcraft.theme.css) | [Download](https://raw.githubusercontent.com/ctrlaltransom/AtlasVTT-5e-2024-Character-Sheet/main/sylvan-woodcraft.theme.css) |
