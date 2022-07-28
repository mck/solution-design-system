# Starter Figma Tokens

This starter kit is for users that want to use [Figma Tokens Plugin](https://www.figma.com/community/plugin/843461159747178978/Figma-Tokens) in [Figma](https://www.figma.com/) as a starting point to build their Design System.
This kit shows an automated workflow, where your design tokens source of truth is in the Figma Tokens Plugin.
Whenever you update the tokens and push to GitHub, the coded components inside Backlight will automatically update, in a pull request!

<iframe width="560" height="315" src="https://www.youtube.com/embed/MKg1CGxtl3s" title="YouTube Figma Tokens teaser video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Full documentation about setting up this workflow can be found in our [Figma Tokens Docs](https://backlight.dev/docs/figma-tokens) soon.

If you are starting with [Backlight](https://backlight.dev), check the links below:

- [Explore starter kits](https://backlight.dev/starterkits)
- [Backlight documentation](https://backlight.dev/docs)
- [Join chat](https://discord.gg/XkQxSU9)

## Workflow Summary

- Designer changes some tokens in Figma Tokens Plugin and pushes the changes to GitHub.
- A pull request is created automatically in GitHub through GitHub Actions
- Style-Dictionary is ran and results are added to this PR automatically through GitHub Actions
- A Backlight preview link will appear in the PR
- Designers (& optionally developers) can see visual changes and review + approve
- Changes are merged into main

Code & Design, will be in sync 🎉 and designers will have more autonomy.
