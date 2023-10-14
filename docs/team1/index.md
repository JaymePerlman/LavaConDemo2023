---
layout: page
title: Resources
---

* TOC
{:toc}
<hr/>

## Full-featured documentation site templates are available

For a fully-featured solution designed from the ground up to support documentation, take what you've learned here and apply it to a template such as [Just the Docs](https://github.com/just-the-docs/just-the-docs). Such no-cost templates provide a TON of actual docs-management functionality and other necessary features like navigation sidebars. They're much more complex, but then again, they're fully-built engines where this repo is just a sketch of certain possibilities.

## Learning to GitHub

Any search engine will turn up hundreds of options, but the [official GitHub training resources](https://docs.github.com/en/get-started/quickstart/git-and-github-learning-resources) are quite extensive. Many offerings are [fully interactive](https://skills.github.com/) - learn by doing, not reading.
 
## Linters 

The most complete linter/checking solution I’m aware of is [Vale](https://vale.sh/). 

If you’re running in Codespaces, VSCode, or another popular development environment, Vale's going to be a built-in plugin you can just select, install, and use. It can automatically check your content against the entire Microsoft Style Guide, for example. Or make sure your company name is capitalized correctly.

## Automate All the Things!

The best book I'm aware of on Actions is [Automating Workflows with GitHub Actions](https://www.amazon.com/Automating-Workflows-GitHub-Actions-applications/dp/1800560400) Until very recently, the author was a senior manager in our Premium Support org.

## Learn to script

If you can spend a little time with our API and ChatGPT, you can learn to write scripts of your own. 
With AI help, I wrote up a script that used the GitHub API to pull dates from two different sources, format and compare them, and then if the date in the file was wrong, update it. If the date field was missing or the content was invalid, it wrote the filename to an errata file so I can capture and track the task of fixing things. I went from exactly zero knowledge of Python to a fully functional script -- without asking Eng for help! -- in under three days.

## OpenAPI template repo

If you're getting started learning about OpenAPI, check out the [OSS Example Template Repo](https://github.com/therzka/OSS-Example-Repo) this is a great place to start learning how the files are written and how they work together.

The Swagger official docs contain a complete [template repo](https://swagger.io/blog/api-development/generator-openapi-repo/) available to clone and play with. Build a complete OpenAPI-enabled site in 20 minutes with Swagger? They say "No problem." _(Swagger donated the API specification that they developed to the OpenAPI initiative in 2015, and have since focused on building tools to implement that specification.)_

## Labels

I wrote an entire additional article on the [use of proper labeling](./labels.md). They're amazingly helpful if you do it right, and a horrific mess if you do it wrong.
