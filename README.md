# Jeremy's base Slidev talk deck

## Dependencies

- Slidev - https://sli.dev/
- 


## Using & Development

1. [Fork] (https://github.com/jerdog/jerdog-base-talk-slidev/fork) the repo to your organization

2. Clone the repo

```bash
git clone <your fork>
cd <your local fork directory>
```

3. Install dependencies and run the dev server

```bash
npm install
npm run dev
```

4. View the base: <http://localhost:3030>

5. Edit the [slides.md](./slides.md) file and then save to see the changes.

Learn more about Slidev at the [documentation](https://sli.dev/).

### Config items

#### Main presentation

For the presentation config, edit the specific YAML entries in the [slides.md](./slides.md) frontmatter:

- `theme:` by default using the `slidev-theme-the-unnamed` theme
- `title:` 
- `author:`
- `info:` this block is markdown and is where to put basic info (title, abstract, etc.)
- `conference:` put the conference name, which will be used in the left footer of the presentation
- `keywords:` put the keywords for the presentation
- `favicon:` put the favicon for the presentation, can be a local file or a URL

**Other config items**

- `fonts:` a list of values for the font types (sans, serif, mono) to use in the presentation
- `class:` the default class for the presentation
- `defaults:` default frontmatter for the presentation (layout, transition, etc.)

#### Presentation slides

The slides are written in markdown and HTML, and each slide begins with a `---` line. You can use frontmatter to add additional information to the slide by adding it after the `---` line, and then closing the frontmatter with another `---` line.

You can add specific config for each slide like class, layout, transition, etc.

## LICENSE

MIT License

Copyright (c) 2024-25 Jeremy Meiss.