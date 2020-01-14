# Shabad OS Tutorials

Shabad OS tutorials, powered by [Antora](https://docs.antora.org/antora/2.2/page/).

The folder `modules` contains asciidoc folders.

## Content Guidelines 

Each tutorial should first declare it's intended audience and purpose. Ideally each tutorial should end with related tutorials and links.

## File Structure

Add pages to `modules/nav.adoc`.

Each folder in the `modules` folder is known as a **module**.
Antora supports partials, images, examples, embedded videos, amongst other goodies, so please see https://docs.antora.org/antora/2.2/page/ for more information.

## Theming/UI

Edit the Antora UI theme in `ui`. 

Run `npm start` to run a development server with preview.

## Building

Run `npm install` in the root directory. This will install the npm modules for the root and `ui` directories.

Running `npm run build` in the root directory will automatically build the UI and docs.