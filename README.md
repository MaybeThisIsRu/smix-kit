# smix-post-creator
A Python CLI utility to create ready-to-edit Markdown files for your [Smix Eleventy blog](https://github.com/hirusi/smix-eleventy-starter).

Input:

- Select post type using your space bar key (article, note, image, reply)
  - In case of reply, paste reply context ready to go.
  - In case of note, skip title input and generate a random short string.
  - In case of article, ask for a post title.
  - In case of image, navigate your `~` and select one or more images. Images should be copied to a pre-configured directory and downsized to a pre-configured width. Markdown text for images should be pre-included in the body of the generated file.
- Date (pick from now or custom input written in plain language: `22 Feb 2022`)
- Tags
  - Pre-configure the utility and point it to a JSON file where tags are. Then be able to select one or more using your space bar key.

Output:

- A new Markdown file.
- Code editor opened to continue editing it.
