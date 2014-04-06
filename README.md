# Open Business Solutions Website

This is a mirrored site of http://www.openbusiness.com.sg as a demo.

It is built with [DocPad](http://docpad.org/) - an awesome Jekyll-inspired static site generator.

All pages (Home, Features, About Us, even Search!) are 100% static, which means you can host the entire site with minimal resources.

From a CMS Administrator's point-of-view, you only need to add/edit _jade_ or _markdown_ files in 

- /src/documents/pages

And see your changes immediately after page refresh!

## Demo
Since it's a pure static website, it's deployable to the GitHub Pages with ease.

Visit it at http://kennyki.github.io/openb

## Run locally

1. Install [Node.js and Docpad](http://docpad.org/docs/install).
1. Clone from this [repo](https://github.com/kennyki/openb.git).
1. Execute `npm install` in the root dir (will install bower dependencies as well).
1. Execute `docpad run` in the root dir.
1. Browse to `http://localhost:9778`.
1. Enjoy.

## Push modifications to GitHub Pages
1. Execute `docpad deploy-ghpages --env static`.
1. Or do it manually by follow the steps provided by [GitHub](https://pages.github.com/).