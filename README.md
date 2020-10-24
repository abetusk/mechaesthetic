# [mechaesthetic](https://abetusk.github.io/mechaesthetic)

A blog of beautiful hardware, electronic and other engineering projects from the internet.

---

Unless otherwise stated, all content on this site is CC0.

---

Feel like contributing? Make a pull request and add to the top of the `index.md` file.

Some post guidelines:

* Add a short catchy title
* Add the date underneath (date of submission, not of project creation) as a tiny header (six '#')
* The first link should be to the project
* If possible add a picture, animated GIF or an embedded video, making
  sure to link to the project in question, if possible
* Add more information underneath the picture about the project
* Names should be put in brackets (`[]`)
* Address people as they want to be addressed, both for their names as they
  appear online and other identifying information (proper gender pronouns, etc.)
* Add a permalink to the archived web site (from [archive.org](https://archive.org/web/)), creating
  the archive link if necessary
* Add your name underneath as `Submitted by [<your_id>]` at the bottom as a tiny header (six '#')

All other assets (images, etc.) should go in the `theme` directory, specifically the `theme/img` directory for images.

To build:

```
mkdocs build --clean
```

To test locally:

```
mkdocs serve
```

Once satisfied, check in all changes, including the screenshots in `theme/imgs`, changes in `posts` and all
new files created in the `site/` directory and then issue a pull request.

---

If you're not comfortable cloning, editing, pushing and issuing a pull request, feel free to open an issue
for any suggestions!
