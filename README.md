# smix-post-creator
A Python CLI utility to create ready-to-edit Markdown files for your Smix Eleventy blog.

Input:

- Select post type (article, note, image, reply)
  - In case of reply, paste reply context ready to go.
  - In case of note, skip title input and generate a random short string.
  - In case of article, ask for a post title.
  - In case of image, navigate your `~` and select one or more images. Images should be copied to a pre-configured directory and downsized to a pre-configured width.
- Date (pick from now or custom input written in plain language: `22 Feb 2022`)
- Tags

Output:

- A new Markdown file.
- Code editor opened to continue editing it.
