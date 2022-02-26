# smix-post-creator
A Python CLI utility to create ready-to-edit Markdown files for your [Smix Eleventy blog](https://github.com/hirusi/smix-eleventy-starter).

## Commands

### `smix-kit new`

Input:

- Select post type using your space bar key (article, note, image, reply)
  - In case of reply, be able to paste reply context.
  - In case of note, skip title input and generate a random short string. Option to leave it empty.
  - In case of article, ask for a post title.
  - In case of article, ask if a featured image is required. Use the same flow as the next bullet point for images.
  - In case of image, navigate your `~` and select one or more images. Images should be copied to a pre-configured directory and downsized to a pre-configured width. Markdown text for images should be pre-included in the body of the generated file.
- `content-description` for all posts.
- Date (pick from now or custom input written in plain language: `22 Feb 2022`)
- Tags
  - Pre-configure the utility and point it to a JSON file where tags are. Then be able to select one or more using your space bar key.

Output:

- A new Markdown file.
- Code editor opened to continue editing it.

### `smix-key image`

Select images to copy to a directory, compressed in size and shrunk in dimensions. Focus on writing your article, notes, and more.

## Dependencies

### Packages

- A wrapper for interacting with files.
- An image manipulation tool.
- A helper for building the CLI.
  - Step-based prompts.
  - Selection via space bar.
  - A file browser.

### Misc

- Template files
