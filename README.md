# Data-flow Documentation
This is a compilation of all documentation sources for all things related to processing and production.

## To View

The live documentation website can be viewed [here](https://snoplus.github.io/data-flow-documentation/).

## To Contribute

The source exists on the `gh-pages` [branch](https://github.com/snoplus/data-flow-documentation/tree/gh-pages), and all changes **must** be made to that.

The easiest way to add or modify content is **directly in Github**; however, you can modify the files locally and commit them like normal although to test the website locally requires the installation of the static site generator in use, [Jekyll](https://jekyllrb.com/docs/).

Refer to the below guidelines before contributing.

## Example

Let's say we want to add a new section to the documentation for Grid-related documentation. To do so, we would:
* Navigate to the data-flow-documentation github page
* Ensure we are on the `gh-pages` branch
* Click **Add file** then **Create new file**
* It should show something like `data-flow-documentation/` with a box to let you type the name of the new file
* Since we want to add a new directory, we would type in `grid/` which will then add a subdirectory
* Now it should show `data-flow-documentation/grid/` with a space for you to add a file
* Type in the file name, and **ensure it ends with a .md extension** (this makes it a **markdown** file); an example is **grid.md**
* You can now follow the [Github Markdown Syntax Guide](https://guides.github.com/features/mastering-markdown/) for formatting and adding your content
* Once done, commit or propose your changes at the bottom of the page. Once merged, the changes will cause Jekyll to rebuild the site automatically, and in a few minutes, those changes will be live on the site
* To link to this new section, you can use the **relative path** to the file from another page. For example, if we wanted to link to this new page from the home page, we would edit **index.md** and write `[Grid documentation](./grid/grid.md)`

## Contributing Guidelines

* Use markdown formatting - a reference is provided below
* Keep it organized - place any new pages under a corresponding directory structure, and if no structure exists, create it (for example, **processing-related pages** should go under the **processing directory**)
* Use the the appropriate language syntax highlighting when including code examples in documentation - an example is (view the source of this readme to see how to include it for a few common languages):
```python
def main():
  print("Hello World!")
```
```bash
echo "Hello World!"
```

## Useful Resources for Contributing
* [Github Markdown Syntax Guide](https://guides.github.com/features/mastering-markdown/)
* [Official Github Pages + Jekyll Reference](https://docs.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll)
* [Jekyll Reference](https://jekyllrb.com/docs/)
* [just-the-docs Reference (the Jekyll theme we are using)](https://pmarsceill.github.io/just-the-docs/)
