# allani's public website

## What is this?

it's the code to allani.ca 

## Recent Changes

### June 2024 Refactor

- Did a full cleanup and refactor of all CSS and HTML.
- Renamed all classes and IDs to be more modern and semantic.
- Grouped and commented the CSS so it's much easier to follow and maintain.
- Removed a bunch of old, unused, or redundant styles and markup.
- Made the HTML more readable and consistent across all templates.
- Navigation and layout are now standardized everywhere.
- Everything should be easier to extend and update going forward!

## How is it generated

By hand, no use of AI. With help from some friends and resources online.

## What SSG are you using?

Hey that's a good idea. Right now this is all done manually in vscode. The plan is to deploy this on cloudflare pages free tier, so it's easiest to develop this locally with an internal dns record pointing to my own server, then push to git and pull down on github. Maybe at some point I'll take a look at astro or write my own SSG. Right now I am enjoying the flexibility to have each page just be a standalone object.

## How is cloudflare pages anyways

They are fine. They let you host 25mb of content directly on their servers under the free plan. I might break some projects up in to small pages and make them subdomains to get around some of the space constraints. The models I plan to upload from autocad might be large enought to get their own subdomains.

## Credits and Sources

 * Website initial template from https://sadgrl.online/
 * Main font source: Sour Gummy https://fonts.google.com/specimen/Sour+Gummy
 * Current background image: https://codepen.io/sadness97/full/dPoEqNN ( cloudynite.gif )
 * ( I would like to find the actual source of this image, but so far I haven't had much luck )
 * Cat Ipsum Filler from http://www.catipsum.com/index.php