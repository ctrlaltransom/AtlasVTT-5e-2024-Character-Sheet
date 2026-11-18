# 5e 2024 (5.5e) Statblock Template Guide
## The Template
- This template is designed for Atlas' native statblocks, which are currently an experimental feature. To enable it, open a scene, click the command button (⌘) in the toolbar, and search for "Experimental Features," then enable "Statblock editor." Create a folder in your Obsidian vault called `statblock-templates` and put the template file attached there. You can create statblocks based on the template by right-clicking any folder, choosing "New statblock here," and choosing this template.
- It is designed for D&D 5.5e, also called 5e 2024.
- It is attached as the file `5e (2024) Character Sheet.atlastemplate`.
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
- There currently is no support for proficiency in ability saves.
- Atlas currently does not support adding dice rolls to other dice rolls with a button like the proficiency bonus. That means the bonus dice field cannot be automatically added to rolls.

## Additional Features
### Themes
- I have created multiple themes using Obsidian's built-in CSS snippets to make the statblock more visually appealing. All of these are optional and do not affect functionality, but I personally use the 5e-parchment.css snippet.
- To use CSS themes, download your theme(s) of choice (mine are posted in this repo and [here](https://discord.com/channels/1551361618305224816/1565541195189325984)). Open Obsidian's settings, click "Appearance," then click "CSS snippets," then click the folder icon to open the snippets folder. Drop the theme(s) you downloaded into that folder, refresh the Obsidian settings if needed, and toggle the snippet on. Only use one at a time.
### Functional snippets
- I made a CSS snippet to force statblock previews (the ones that show up when you hover over a token in a scene) to have two columns for readability. Download it in this repo or [here](https://discord.com/channels/1551361618305224816/1566157149279887531) and install it the same way as the themes.
- I made a CSS snippet to make the core spellcasting attributes of a character (ability, attack bonus, and save DC) appear in a box similar to the box that AC, initiative, and movement speed appear in. I haven't found a way to actually put them in the same type of box due to limitations with Atlas' statblock system, so this is a workaround for now. Download it in this repo or [here](https://discord.com/channels/1551361618305224816/1562121042963472498/1572311872919830690) and install it the same way as the themes.
- I made a CSS snippet to make the skills section display more neatly, which is a workaround similar to the previous snippet. Download it in this repo or [here](https://discord.com/channels/1551361618305224816/1562121042963472498/1572314007996600362) and install it the same way as the themes.
### Integrations
- This character sheet is the basis of [the D&DBeyond importer plugin](https://community.obsidian.md/plugins/dndbeyond-importer-for-atlas) by @young_george. 
### Modified sheets
- You can modify this sheet to play homebrewed or other modified versions of D&D like Mage Hand Press' sci-fi version, Dark Matter. I modified this template for Dark Matter already. You can find it [here](https://discord.com/channels/1551361618305224816/1572354559685435442).
