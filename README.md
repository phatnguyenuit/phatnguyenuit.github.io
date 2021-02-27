# phatnguyenuit.github.io

## Prerequisites

- [Install Ruby & Jekyll](https://jekyllrb.com/docs/#instructions)

## Available Scripts

In the project directory, you can run:


### `bundle`

Install required dependencies

### `bundle exec jekyll serve`

Serve `jekyll` development mode.

#### Examples

```sh
$ bundle exec jekyll serve # serve
```

```sh
$ bundle exec jekyll serve --watch # serve & watch changes
```

```sh
$ bundle exec jekyll serve --drafts --watch # serve draft articles & watch changes
```

### `bundle exec jekyll build`

Build static web resource to deploy


### `bundle exec jekyll draft "NAME OF YOUR ARTICLE"`


Write a draft article

#### Example

```sh
$ bundle exec jekyll draft "my draft article"
```

It will created new file at `_drafts/my-draft-article.md`


### `bundle exec jekyll publish DRAF_FILE_PATH`

Publish selected draft articles

#### Example

Publish `my-draft-article`, assign date and move it into `_posts`

```sh
$ bundle exec jekyll draft _drafts/my-draft-article.md
```
