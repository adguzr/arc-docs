# Contributing to the documentation

Anyone can suggest improvements to this documentation. Changes go through a quick review before they appear on the live site, so don't worry about breaking anything.

## Suggesting an edit to an existing page

The fastest way to fix a typo or improve a page:

1. Click the **pencil icon** (✏️) at the top right of any page.
2. GitHub will offer to **fork** the repository — click the green button to create your own copy.
3. Make your edits in the browser editor.
4. Click **Commit changes**, add a short note describing what you changed.
5. Click **Create pull request**.

That's it. A maintainer will review your suggestion and merge it. Once merged, the live site updates automatically within a minute or two.

## Adding a new page

1. Go to the [repository](https://github.com/adguzr/arc-docs) and open the `docs/` folder.
2. Navigate to the section where your page belongs (e.g. `docs/guides/hpc/`).
3. Click **Add file** → **Create new file**.
4. Name the file using lowercase and hyphens, ending in `.md` (e.g. `running-gpu-jobs.md`).
5. Write your content in Markdown.
6. Commit the change and open a pull request.

New pages are added to the navigation automatically based on their folder — no configuration needed.

## Writing tips

- Use clear, descriptive headings.
- Keep paragraphs short.
- Use [admonitions](https://squidfunk.github.io/mkdocs-material/reference/admonitions/) for notes, warnings, and tips:

```markdown
    !!! note
        Helpful information goes here.

    !!! warning
        Something to be careful about.
```

- Link to other pages with relative links: `[ARC Access](../resources/arc-access.md)`.

## Reporting a problem

If you have spotted an error but do not want to edit it yourself, [open an issue](https://github.com/adguzr/arc-docs/issues/new/choose) and describe what is wrong. We will take care of it.

## Questions

For anything else, contact the ARC team at [arc.support@ubc.ca](mailto:arc.support@ubc.ca).
