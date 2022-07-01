# My personal website

This is my personal site. It's built using Hakyll & hosted on GitHub Pages.

## Building the site

The site can be built by running

```bash
stack build
stack exec site build
```

## The `/docs` directory

Currently, Pages only allows sites to be hosted either from the root directory 
of the repository, or from `/docs`. As a result, Hakyll is configured to build
the site in the `/docs` directory.
