# PS2 Hacks Wiki

This site uses [mkdocs.org](https://www.mkdocs.org) with the [Material](https://squidfunk.github.io/mkdocs-material/getting-started/) theme.

For a quick overview of how to configure pages and render Markdown content in Material, consult their [reference guides](https://squidfunk.github.io/mkdocs-material/reference/).

## Local previews

You can generate real-time local previews to see how your changes will affect the site. To set up local previews:

1. [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) this repository to create a local copy.

1. If you haven't already, [install Python](https://www.python.org/downloads/).

1. [Install MkDocs](https://squidfunk.github.io/mkdocs-material/getting-started/#installation).

1. In the CLI environment of your choice, navigate to the directory where you cloned this repository.

(If you're using VSCode, you can open the [integrated terminal](https://code.visualstudio.com/docs/terminal/basics) from the top menu bar by selecting **View > Terminal**. It'll automatically open the terminal in the correct directory.)

1. Run `mkdocs serve`.

1. MkDocs will generate a local preview of your site. Your CLI will return a message with a URL where you can view this preview—open this URL in your browser.

1. Every time you **save** changes to a file in your file editor, MkDocs will refresh the local preview in your browser to reflect those changes.

## Deploy previews

When you create a pull request, GitHub will automatically generate a deploy preview through Netlify. These deploy previews use the URL naming scheme `deploy-preview-XYZ--mywebsite.netlify.app/`.
