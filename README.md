## Astro Blog Template

View a preview of the most recent build [here](https://fisher60.github.io/astro-blog-template/)

## Features

- **Extended markdown with [Markdoc](https://markdoc.dev).** Type-safe custom components like YouTube embed, Twitter embed (or anything you want really) in your markdown (`.md`) files.
- **RSS feed**. Your blog has an RSS feed setup that can be accessed at `/rss.xml`.
- **SEO**. All pages are setup with all the SEO you might need.

## Adding Content

All the content is written in markdown (.md) and grouped as `blog` or `projects` in the `content` directory. All the default markdown syntax will work. You also have a few example custom markdown elements like _YouTube embed_, _Twitter embed_, etc. You can create your own custom components too in two easy steps.

1. Add a markdoc config. Check out the markdoc config in [src/lib/markdoc/config.ts](src/lib/markdoc/config.ts) to learn how to add custom components.
2. Add a component to render your custom component. Check out the Renderer in [src/components/Renderer.astro](src/components/Renderer.astro).

## Customization

- All content is static and everything is straight forward. Change whatever you need to change.
- Delete or update the content in `content/{content-group}`. `content-group` could be `blog`, `projects` or `anything`.
- (Optional) If you need more content types like _Notes_, just create a new dir in `content` and add a new frontmatter validator like [src/lib/markdoc/blog/frontmatter](src/lib/markdoc/blog/frontmatter).

## License

MIT © [Dinesh Pandiyan](https://github.com/flexdinesh)
