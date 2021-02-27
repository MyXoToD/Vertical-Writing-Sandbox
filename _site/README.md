# Vertical Writing Sandbox

We want to see what is possible with web typography and vertical text/writing. Vertical only and vertical/horizontal mixed. CSS only solutions are prefered but some demos might also include javascript.

### Demos / Testing

- [Main Page](https://myxotod.github.io/Vertical-Writing-Sandbox/)
- More demo links coming soon...

### How to add demos

1. Create new post file in `_posts` named `yyyy-mm-dd-demoname.html`
    1. Make sure to add `title`, `layout` & `stylesheet` to the frontmatter of this page
    2. `stylesheet` has to be the same name as the stylesheet name that will be created in step 2 (without `.scss`)
2. Create scss file for new demo in `assets/stylesheets/scss` named `demoname.scss`
    1. This stylesheet should include a class named `.demoname` wrapping everything else in it (`.demoname` will be appended as a body class)
3. Import this new scss file into main `assets/stylesheets/application.scss` file

If you followed these steps correctly, the newly created demo should be linked automatically on out index page.

### Contributors

- [IllDepence](https://github.com/IllDepence)
- [MyXoToD](https://github.com/MyXoToD)