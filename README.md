# Fairway's Website

Fairway's website. We are using Jekyll, a static website generator.

## Adding content

### Member information

1. Go to `_data/members.yml`
2. Edit or add what you want

### News

1. Add a new file in `_posts/news/` (for example, by duplicating and renaming an existing one).
2. You can write the content in Markdown format
3. If the post has a picture, place it in assets/img/news.

## How to check changes you made locally

Please check that the site still works before you submit a pull request. You can do this by:

```sh
bundle install && jekyll serve
```

Then visit `localhost:4000` in your browser.

## How to branch, commit and push

Please don't commit directly to master, if you can avoid it.

1. Create a new branch from master: `git checkout -b my-branch-name`
2. Add and commit your changes. `git status` to check what you did, `git add ...` to add new files, `git commit -m "Put a comprehensive summary of your changes here"`
3. Push your new branch: `git push` (depending on your settings, git will complain and tell you what to do instead).
4. Go to https://github.com/fairway-kaist/fairway/ and create a new Pull Request for your branch.
5. Someone with authority will go on and merge your changes.
