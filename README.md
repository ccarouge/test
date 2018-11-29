CMS Blog
========

The blog is viewable here:

http://climate-cms.org

See the Jekyll docs for info on creating posts - https://jekyllrb.com/docs/posts/

---
To create a new blog post:

1. `clone` the repo
2. Create new `branch`
3. 
    - If using a notebook:
        1. Create a new notebook under the `notebooks` directory, named `YY-MM-DD-title.ipynb`
        2. Convert to a post by running `make` from main directory
        3. Edit the metadata in the `_posts` directory as appropriate
    - If the post is not a notebook:
        1. Create a new blog post in `_posts`, named `YY-MM-DD-title.md` directly
4. `commit` changes and `push` branch back to `coecms/coecms.github.io`
5. Open Pull Request and select CMS team member to review
6. After review squash and merge PR
7. Delete `branch`

---
The new blog post should appear within a few minutes at http://climate-cms.org 

If it doesn't, check under "Github Pages" here for error messages:

https://github.com/coecms/coecms.github.io/settings

---

Create a local test server by running

    vagrant up

then going to http://localhost:8080

---


