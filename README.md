# A Scribus Knowledge Base

Short "how to do" articles for Scribus

- set of markdown files (pages) be catogorised by tag.
- the user selects the tags to find the pages that can be helpful and click on the link to see the page.
- multilingual.
- the content is provided through git.

## Look at...

## Multilingual

- <https://learn.getgrav.org/content/multi-language#multiple-language-pages>

```
my-page/
    my-page.en.md
    my-page.fr.md
```

### Taxonomies

<https://learn.getgrav.org/content/taxonomy>

- use categories for normal website pages and the other pages
- use tags inside of categories

### Taxonomy list plugin

<https://github.com/getgrav/grav-plugin-taxonomylist> can be of inspiration to creat a plugin that makes a clickable filter of tags

### Git Sync

- https://github.com/trilbymedia/grav-plugin-git-sync for the main site
- the knowledge base items will have to be pulled in with from a different repository, with a different hook.

### Other links

- [Grav Knowledge Base with Git Sync Site](https://github.com/paulhibbitts/grav-skeleton-knowledge-base-with-git-sync-site) scheleton.
- [Learn2 with Git Sync](https://github.com/hibbitts-design/grav-skeleton-learn2-with-git-sync): Using a customized version of the Grav Learn2 theme, Learn2 with Git Sync is designed to help organizations or individual tech-savvy authors more easily share and collaboratively edit Markdown-based documentation.
